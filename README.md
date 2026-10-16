# Open Source 101

### Bio Upload Instructions

Your first open-source contribution can be simple! Follow these steps to add your bio to the repository.

#### Step 1: Fork the Repository
- Open the GitHub repository.
- Click the **Fork** button in the top-right corner.
- This creates a copy of the repository under your GitHub account.

#### Step 2: Clone Your Fork
- Open your forked repository.
- Click the green **Code** button and copy the repository URL.
- Open your terminal and run:

```bash
git clone <your-forked-repository-url>
cd <repository-name>
```

#### Step 3: Create Your Bio File
- Open the `Participants` folder in the repository.
- Create a new Markdown file named after yourself, using lowercase letters.

For example: `participants/rashika-karki.md`

- Add a short bio about yourself. You can include:
  - Your name and where you're from
  - What you do or what you're studying
  - Your interests and technical skills
  - Your GitHub profile or other social links

**Example bio:**

```markdown
# Rashika Karki

Hi! I'm Rashika, a software developer from Nepal.
I'm interested in open source, AI, and building useful
projects.

- GitHub: https://github.com/rashikakarki
- Interests: Open source, AI, and web development
```

#### Step 4: Commit Your Changes

Save your file, then run the following commands:

```bash
git add participants/rashika-karki.md
git commit -m "Add Rashika Karki's bio"
git push origin main
```

Replace the filename, name, and branch (`main`, if your fork uses a different default branch) with the appropriate values.

#### Step 5: Create a Pull Request (PR)
- Go to your fork on GitHub.
- Click **Contribute** and then **Open pull request**. If you don't see this option, open the **Pull requests** tab and select **New pull request**.
- Make sure the base repository is the original project, not your fork.
- Add a clear title, such as `Add Rashika Karki's bio`.
- Briefly describe your changes and submit the PR.

#### Step 6: Wait for Review
- Check that your pull request was created successfully.
- If the maintainers request changes, make the updates and push them to your fork. They'll appear in the same PR automatically.

### Before You Submit

- [ ] Your file is inside the `Participants` folder.
- [ ] Your filename uses lowercase letters.
- [ ] Your bio is written in Markdown (`.md`).
- [ ] Your changes are committed and pushed.
- [ ] Your pull request targets the original repository.

**That's it! You've made your first open-source contribution. 🎉**

Take a breath, explore the project, and celebrate your contribution!
