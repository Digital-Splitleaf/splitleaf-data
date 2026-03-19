# Welcome to the Digital Splitleaf Texts Repository

Welcome to the **Digital Splitleaf (DS)** text‑submission and editorial workspace. This repository provides a structured way for contributors, editors, and collaborators to submit new psalter editions, track editorial progress, and ensure consistent, high‑quality publication of digital psalm‑singing resources.

---

## 🚀 How to Contribute: The "Two-Touch" Workflow

To ensure the highest accuracy, every file must be edited or verified by **two different people** before an Admin publishes it to the live site.

### Step 1: The Initial Edit (Editor 1)
1.  **Switch to Development:** Click the branch selector (labeled `main`) at the top left and select **`development`**.
2.  **Find your File:** Navigate to the XML file you wish to edit.
3.  **Edit:** Click the **Pencil Icon**. Edit the file according to the **Community Editing Priorities** below.
4.  **Save:** Scroll to the bottom, write a short note of your changes, and click **Commit changes**.
5.  **Propose:** Click the green **"Compare & pull request"** button. Ensure the "base" is `main` and "compare" is `development`. Click **Create pull request**.

### Step 2: The Peer Review (Editor 2)
1.  **Review:** Open a pending Pull Request and click the **Files changed** tab.
2.  **Verify:** Check the XML against the original source and the **Community Priorities** below.
3.  **Approve:** Click **Review changes**, select **Approve**, and submit.

### Step 3: Admin Final Approval
Admins are automatically notified via `CODEOWNERS`. We perform a final technical check and **Merge** the file to `main`, which pushes it live to the website.

---

## 🛠️ Community Editing Priorities

Please use the following checklist to guide your editing and review process:

### 1. Replace Placeholder Text
Many files contain placeholders such as `AUTHOR_HERE`. Replace these with accurate information based on the text you are editing. Ensure no placeholders remain before proposing a merge.

### 2. Verify Syllable Divisions
**All syllable boundaries were produced automatically and must be manually verified.**
* ⚠️ **Important:** Musical lyrics do not always follow standard dictionary hyphenation.
* **Practice:** Ensure divisions reflect lyrical and musical practice.
* **Tool:** Use [Juicio Brennan's Lyric Hyphenator](https://juiciobrennan.com/hyphenator/) for assistance.

### 3. General Content Review
Verify the accuracy of the following:
* **Spelling & Transcription:** Match the printed source exactly.
* **TEI Structure & Metadata:** Ensure the logical structure is complete.
* **Punctuation & Formatting:** Maintain the integrity of the original text.

### 4. Improve the `<teiHeader>`
Enhance the metadata quality following [TEI P5 Guidelines](https://tei-c.org/release/doc/tei-p5-doc/en/html/index.html). 
* Use only valid TEI elements and attributes.
* Maintain correct hierarchical structure.
* Add XML comments `` if something requires later admin review.

---

## 🛠 Useful Links & Resources
* **Active Drafts:** [View the Development Branch]([https://github.com/Digital-Splitleaf/splitleaf-data/tree/Development/texts)
* **Code of Conduct:** [Read our community standards](https://github.com/Digital-Splitleaf/splitleaf-data/blob/main/CODE_OF_CONDUCT.md)
* **Contribution Guidelines:** [Full workflow details](https://github.com/Digital-Splitleaf/splitleaf-data/blob/main/CONTRIBUTING.md)

> **💡 Need Help?** If you are new to GitHub and feel stuck, please open an **Issue** [here](https://github.com/orgs/Digital-Splitleaf/discussions/categories/q-a) or contact a maintainer. We are happy to walk you through your first few edits!
