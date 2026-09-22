<p align="center">
  <img src="https://raw.githubusercontent.com/Rishabh04-02/The-Beginners-Guide-to-Google-Summer-of-Code-GSoC/master/gsoclogo.svg" alt="Google Summer of Code Logo" width="180"><br><br>
  <strong>Google Summer of Code (GSoC) Proposals Archive</strong><br>
  A comprehensive community archive of accepted (and reference) GSoC proposals across all years.<br>
  Read, compare, and learn what makes a technically sound, structured, and winning proposal!
</p>

<p align="center">
  <a href="#-contributing-a-proposal"><strong>Submit Your Proposal »</strong></a>
</p>

### <p align="center">⭐ Star this repo to bookmark it for future reference! ⭐</p>

---

## 👥 Contributors
<!-- CONTRIBUTORS_START -->
<a href="https://github.com/pavanjoshi914"><img src="https://github.com/pavanjoshi914.png" width="50px" alt="pavanjoshi914" /></a>
<!-- CONTRIBUTORS_END -->

> Every contributor who gets their proposal PR merged will be automatically added above! 🎉

---

## 📁 Directory & Folder Structure

To organize proposals cleanly across multiple years and organizations, all submissions follow this nested structure:

```text
<Year>/
└── <Organization Name>/
    ├── Accepted/
    │   └── <sub-org-name(if any)>_<project-topic>_<username>.pdf
    └── Rejected/ (optional for learning/comparison)
        └── <sub-org-name(if any)>_<project-topic>_<username>.pdf
```

### Examples:
- `2026/Python Software Foundation/Accepted/cpython_asyncio-improvements_johndoe.pdf`
- `2026/OpenVINO Toolkit/Accepted/model-optimization_alexsmith.pdf`
- `2025/TensorFlow/Accepted/keras-cv_enhancements_janedoe.pdf`

---

## 🚀 Contributing a Proposal

Proposals from any year (2026, 2025, 2024, etc.) are warmly welcomed! You can contribute either **via the GitHub Web Interface** (easiest, no Git installation required) or **via Git Command Line**.

### Method 1: Using GitHub Web Interface (Easiest)

1. **Fork** this repository by clicking the **Fork** button at the top right.
2. In your fork, click **Add file** ➔ **Upload files**.
3. Choose your proposal PDF file.
4. Set the full target path in the commit box:
   ```text
   <Year>/<Organization Name>/Accepted/<sub-org-name(if any)>_<project-topic>_<username>.pdf
   ```
   *(e.g., `2026/Python Software Foundation/Accepted/cpython_asyncio-improvements_johndoe.pdf`)*
5. Add a commit message: `Add GSoC <Year> proposal for <Organization Name> by @<your-username>`.
6. Click **Commit changes**.
7. Go to the **Pull requests** tab of your fork and click **New pull request** ➔ **Create pull request**.

---

### Method 2: Using Git Command Line

1. **Fork this repository** using the "Fork" button on GitHub.
2. **Clone your fork** to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/GSoC_archive.git
   ```
3. **Navigate to the repository**:
   ```bash
   cd GSoC_archive
   ```
4. **Add the upstream repository**:
   ```bash
   git remote add upstream https://github.com/pavanjoshi914/GSoC_archive.git
   ```
5. **Sync your fork** with upstream:
   ```bash
   git pull upstream main --rebase
   ```
6. **Create a new branch**:
   ```bash
   git checkout -b add-proposal-<year>-<org-name>
   ```
7. **Add your proposal file**:
   - Create a folder for the year (e.g., `2026/`) if it doesn't exist.
   - Create a folder for the organization inside it (e.g., `2026/Python Software Foundation/`).
   - Create the `Accepted/` folder inside the organization folder.
   - Place your proposal PDF file inside using the format:
     ```text
     <sub-org-name(if any)>_<project-topic>_<username>.pdf
     ```
8. **Commit and push your changes**:
   ```bash
   git add .
   git commit -m "Add GSoC <Year> proposal for <org-name>"
   git push origin add-proposal-<year>-<org-name>
   ```
9. **Open a Pull Request**:
   - Go to your fork on GitHub.
   - Click **Compare & pull request**.
   - Fill in the PR template details and submit!

---

## 📜 Disclaimer
All proposals uploaded to this repository belong to their respective authors. They are shared here for educational purposes and reference to help future GSoC applicants learn how to craft strong, well-structured proposals. Please respect the authors and do not plagiarize.
