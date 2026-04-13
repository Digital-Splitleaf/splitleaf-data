# Welcome to the Digital Splitleaf Tunes Repository

Welcome to the **Digital Splitleaf (DS)** tune‑submission and editorial workspace. This repository provides a structured way for contributors, editors, and collaborators to submit new psalter editions, track editorial progress, and ensure consistent, high‑quality publication of digital psalm‑singing resources.

---

## 🚀 How to Contribute: The "Two-Touch" Workflow

To ensure the highest accuracy, every file must be edited or verified by **two different people** before an Admin publishes it to the live site.

### Step 1: The Initial Edit (Editor 1)
1.  **Switch to Development:** Click the branch selector (labeled `main`) at the top left and select **`development`**.
2.  **Find your File:** Navigate to the XML file you wish to edit.
3.  **Edit:** Click the **Pencil Icon** at the top right of the code pane. Edit the file according to the **Community Editing Priorities** below.
4.  **Add:** Add your name and initials to the header file under Validator 1.
5.  **Save:** Scroll to the bottom, write a short note of your changes, and click **Commit changes**.
6.  **Propose:** Click the green **"Compare & pull request"** button. Ensure the "base" is `main` and "compare" is `development`. Click **Create pull request**.

### Step 2: The Peer Review (Editor 2)
1.  **Review:** Open a pending Pull Request and click the **Files changed** tab.
2.  **Verify:** Check the XML against the original source and the **Community Priorities** below.
3.  **Add:** Add your name and initials to the header file under Validator 2.
4.  **Approve:** Click **Review changes**, select **Approve**, and submit.

### Step 3: Admin Final Approval
Admins are automatically notified via `CODEOWNERS`. We perform a final technical check and **Merge** the file to `main`, which pushes it live to the website.

---

## 🛠️ Community Editing Priorities

Please use the following checklist to guide your editing and review process:

### 1. Replace Placeholder Text
Many files contain placeholders such as `AUTHOR_HERE`. Replace these with accurate information based on the text you are editing. Ensure no placeholders remain before proposing a merge.

### 2. Verify Accuracy of Musical Content
**Most music files will have been transferred from notation software.**
* **Dowload:** Unless you are accustomed to reading MEI files, we strongly recommend that you download the file you wish to edit. To do this, click "Download Raw File", which is to the left of the pencil icon.
* **Load:** Load your score into an MEI editor such as [mei-friend](https://mei-friend.mdw.ac.at/). Just click on **File** > **Open file** and select the downloaded MEI file. 
* **Review:** Review the rhythms and pitches for all voices. If you are uncertain about editing the code directly, you can find many simple functions in the **Manipulate** and **Insert** menus.
* **Add:** In the coding pane of mei-friend, add your name and initials as a Validator.
* **Save:** Save and download your updated file by clicking **File** > **Save MEI**. **NOTE:** Be sure you do not rename the file.
* **Upload:** Back in GitHub, make sure you are in the **Development** branch, and upload your updated MEI file. Navigate to the correct folder, which should be your tune's metre. 
* **Tool:** Use [Juicio Brennan's Lyric Hyphenator](https://juiciobrennan.com/hyphenator/) for assistance.

### 3. Improve the `<meiHeader>`
Enhance the metadata quality following [MEI Guidelines](https://music-encoding.org/guidelines/v5/content/index.html). However, please do not remove any of the existing code. It is crucial to the operation of the Digital Splitleaf.
* Use only valid MEI elements and attributes.
* Maintain correct hierarchical structure. [mei-friend](https://mei-friend.mdw.ac.at/) can help to identify any issues that may arise. You can also find help for adding specific elements using [Deep Wiki](https://deepwiki.com/music-encoding/music-encoding)
* Add XML comments, adding the characters `` to the start of the line, if something requires later admin review.

---

## 🛠 Useful Links & Resources
* **Active Drafts:** [View the Development Branch]([https://github.com/Digital-Splitleaf/splitleaf-data/tree/Development/texts)
* **Code of Conduct:** [Read our community standards](https://github.com/Digital-Splitleaf/splitleaf-data/blob/main/CODE_OF_CONDUCT.md)
* **Contribution Guidelines:** [Full workflow details](https://github.com/Digital-Splitleaf/splitleaf-data/blob/main/CONTRIBUTING.md)

> **💡 Need Help?** If you are new to GitHub and feel stuck, please open an **Issue** [here](https://github.com/orgs/Digital-Splitleaf/discussions/categories/q-a) or contact a maintainer. We are happy to walk you through your first few edits!
