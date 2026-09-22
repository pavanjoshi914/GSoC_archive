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

## 📂 Browse by Year

Quick access to proposals organized chronologically:

| Year | Archive Directory | Status |
| :--- | :--- | :--- |
| **2026** | [**📁 2026 Proposals**](./2026) | 🌟 Current / Accepting Proposals |
| **2025** | [**📁 2025 Proposals**](./2025) | 📂 Open for Contributions |
| **2024** | [**📁 2024 Proposals**](./2024) | 📂 Open for Contributions |
| **2023** | [**📁 2023 Proposals**](./2023) | 📂 Open for Contributions |
| **2022** | [**📁 2022 Proposals**](./2022) | 📂 Open for Contributions |
| **2021** | [**📁 2021 Proposals**](./2021) | 📂 Open for Contributions |

*(Future years such as `2027/`, `2028/`, etc. will follow the same numerical sequence).*

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

Proposals from any year (2026, 2025, 2024, etc.) are warmly welcomed! You can submit your proposal using either method:

---

### Method 1: Submit via Pull Request (Standard & Recommended)

This is the classic open-source developer way!

1. **Fork this repository** using the **Fork** button on GitHub.
2. **Clone your fork** to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/GSoC_archive.git
   ```
3. **Navigate to the repository**:
   ```bash
   cd GSoC_archive
   ```
4. **Add upstream remote**:
   ```bash
   git remote add upstream https://github.com/pavanjoshi914/GSoC_archive.git
   ```
5. **Sync with upstream**:
   ```bash
   git pull upstream main --rebase
   ```
6. **Create a new feature branch**:
   ```bash
   git checkout -b add-proposal-<year>-<org-name>
   ```
7. **Add your proposal file**:
   - Navigate to the year folder (e.g., `2026/`).
   - Create a folder for your organization (e.g., `2026/Python Software Foundation/`) if it doesn't already exist.
   - Create an `Accepted/` (or `Rejected/`) subfolder.
   - Save your PDF using the naming format:
     ```text
     <sub-org-name(if any)>_<project-topic>_<username>.pdf
     ```
     *(Example: `2026/Python Software Foundation/Accepted/cpython_asyncio-improvements_johndoe.pdf`)*
8. **Commit and push your changes**:
   ```bash
   git add .
   git commit -m "Add GSoC <Year> proposal for <org-name>"
   git push origin add-proposal-<year>-<org-name>
   ```
9. **Open a Pull Request**:
   - Go to your fork on GitHub.
   - Click **Compare & pull request** and submit!

> 💡 **Recognition**: When your PR is merged, our automated bot will automatically add your GitHub avatar to the [Contributors](#-contributors) section! 🎉

---

### Method 2: Submit via GitHub Issue (Quick Alternative — No Git CLI Needed)

If you'd like to contribute quickly without cloning or using Git:

1. Click [**New Issue ➔ Submit GSoC Proposal**](https://github.com/pavanjoshi914/GSoC_archive/issues/new?template=submit-proposal.yml).
2. Select your **Year**, type your **Organization Name**, and enter your **Project Topic**.
3. **Drag and drop your proposal PDF** directly into the upload area.
4. Click **Submit new issue**.

> 🤖 **Automated Processing**: Our GitHub Action will automatically download your PDF, place it in the correct directory, commit it to the archive, close the issue, and feature your avatar on the [Contributors](#-contributors) wall!


---

## 📜 Disclaimer
All proposals uploaded to this repository belong to their respective authors. They are shared here for educational purposes and reference to help future GSoC applicants learn how to craft strong, well-structured proposals. Please respect the authors and do not plagiarize.
