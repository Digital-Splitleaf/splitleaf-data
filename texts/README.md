# Welcome to the Digital Splitleaf Texts Repository

Welcome to the **Digital Splitleaf** text‑submission and editorial workspace. This repository provides a structured way for contributors, editors, and collaborators to submit new psalter editions, track editorial progress, and ensure consistent, high‑quality publication of digital psalm‑singing resources.

---

## 🚀 How to Contribute: The "Two-Touch" Workflow

To ensure the highest accuracy for our texts and tunes, every file must be edited or verified by **two different people** before an Admin publishes it to the live site.

### Step 1: The Initial Edit (Editor 1)
If you are the first person to work on a draft:
1.  **Switch to the Development Branch:** Click the branch selector button (usually labeled `main`) at the top left of the file list and select **`development`**.
2.  **Find your File:** Navigate through the folders to the XML file you wish to edit.
3.  **Edit:** Click the **Pencil Icon** (Edit this file) in the top right header of the file view. 
4.  **Save:** Once finished, scroll to the bottom, write a short note about what you changed (e.g., *"Corrected lyrics for Psalm 23"*), and click **Commit changes**.
5.  **Propose for Publication:** At the top of the repository page, click the green **"Compare & pull request"** button. Ensure the "base" branch is `main` and the "compare" branch is `development`. Click **Create pull request**.

### Step 2: The Peer Review (Editor 2)
If you see a pending Pull Request created by someone else:
1.  **Review:** Open the Pull Request and click the **Files changed** tab to see the proposed edits.
2.  **Verify:** Check the XML against the original printed source material.
3.  **Approve:** If it looks correct, click the green **Review changes** button, select **Approve**, and submit your review.
    * *Note: If you find further errors, you can go back to the `development` branch and fix them yourself before approving!*

### Step 3: Admin Final Approval
Once a file has been edited and then approved by a second user, the **Digital Splitleaf Admins** are automatically notified via the `CODEOWNERS` system. We will perform a final technical check of the XML formatting and "Merge" the file into the `main` branch, which automatically updates the live website.

---

## 🛠 Useful Links & Resources
* **Active Drafts:** [View the Development Branch]([https://github.com/Digital-Splitleaf/splitleaf-data/tree/Development/texts)
* **Code of Conduct:** [Read our community standards](https://github.com/Digital-Splitleaf/splitleaf-data/blob/main/CODE_OF_CONDUCT.md)
* **Contribution Guidelines:** [Full workflow details](https://github.com/Digital-Splitleaf/splitleaf-data/blob/main/CONTRIBUTING.md)

> **💡 Need Help?** If you are new to GitHub and feel stuck, please open an **Issue** [here](https://github.com/orgs/Digital-Splitleaf/discussions/categories/q-a) or contact a maintainer. We are happy to walk you through your first few edits!
