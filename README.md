<p align="center">
  <img src="https://raw.githubusercontent.com/Rishabh04-02/The-Beginners-Guide-to-Google-Summer-of-Code-GSoC/master/gsoclogo.svg" alt="Google Summer of Code Logo" width="180"><br><br>
  <strong>GSoC 2026 Proposals Archive</strong><br>
  Accepted Google Summer of Code (GSoC) 2026 proposals archive for reference, guidance, and inspiration from the community.<br>
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

## 📚 Previous Years' Archives

Looking for past years' proposals? Check out these archives:
- **GSoC 2025**: [SammanSarkar/GSoC_archive_2025](https://github.com/SammanSarkar/GSoC_archive_2025)
- **GSoC 2024 and earlier**: [Aritra8438/GSoC_archive](https://github.com/Aritra8438/GSoC_archive)
- **GSoC 2026 (Sister Archive)**: [satwiksps/GSoC_archive_2026](https://github.com/satwiksps/GSoC_archive_2026)

---

## 📁 Folder Structure

Proposals should follow this directory and file naming pattern:

```text
Organization Name/
└── Accepted/
    └── <sub-org-name(if any)>_<project-topic>_<username>.pdf
```

*(You may also contribute to a `Rejected/` folder if you'd like your proposal to serve as a helpful comparison/learning resource for the community).*

### Example:
`Python Software Foundation/Accepted/cpython_asyncio-improvements_johndoe.pdf`

---

## 🚀 Contributing a Proposal

You can contribute either **via the GitHub Web Interface** (easiest, no Git CLI needed) or **via Git Command Line**.

### Method 1: Using GitHub Web Interface (Easiest)

1. **Fork** this repository by clicking the **Fork** button in the top right.
2. In your fork, click **Add file** ➔ **Upload files**.
3. Choose your proposal PDF file.
4. Set the path in the commit box by typing `<Organization Name>/Accepted/<sub-org-name(if any)>_<project-topic>_<username>.pdf` (or navigate into the organization folder if it already exists).
5. Add a commit message: `Add proposal for <Organization Name> by @<your-username>`.
6. Click **Commit changes**.
7. Go to the **Pull requests** tab of your fork and click **New pull request** ➔ **Create pull request**.

---

### Method 2: Using Git Command Line

1. **Fork this repository** using the "Fork" button on GitHub.
2. **Clone your fork** to your local machine:
   ```bash
   git clone https://github.com/YOUR_USERNAME/GSoC_archive_2026.git
   ```
3. **Navigate to the repository**:
   ```bash
   cd GSoC_archive_2026
   ```
4. **Add the upstream repository**:
   ```bash
   git remote add upstream https://github.com/pavanjoshi914/GSoC_archive_2026.git
   ```
5. **Sync your fork** with the upstream main branch:
   ```bash
   git pull upstream main --rebase
   ```
6. **Create a new branch**:
   ```bash
   git checkout -b add-proposal-<org_name>
   ```
7. **Add your proposal**:
   - Create a folder named after your organization (e.g. `Python Software Foundation/`) if it does not already exist.
   - Create an `Accepted/` folder inside it.
   - Place your proposal PDF file inside using the format: `<sub-org-name(if any)>_<project-topic>_<username>.pdf`
8. **Commit and push your changes**:
   ```bash
   git add .
   git commit -m "Add proposal for <org_name>"
   git push origin add-proposal-<org_name>
   ```
9. **Open a Pull Request**:
   - Go to your fork on GitHub.
   - Click **Compare & pull request**.
   - Fill in the PR template details and submit!

---

## 📜 Disclaimer
All proposals uploaded to this repository belong to their respective authors. They are shared here for educational purposes and reference to help future GSoC applicants learn how to craft strong proposals. Please do not plagiarize.
