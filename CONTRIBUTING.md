# 🤝 mcgonagle's GitHub Repository of Work

Welcome to my GROW!  
This repository is more than a notebook, it's my public record of learning and a contribution to the Kubernetes community.

Whether I'm updating my weekly reflections, sharing a new lab, or improving documentation—you’re making this repo stronger. Thank you! 🙌

---

## 📦 What You Can Contribute

- ✅ **Reflections** in `99-reflections/weekX.md`
- ✅ **Custom Labs** in your own folder (e.g., `06-my-lab/`)
- ✅ **Fixes or suggestions** to existing lab guides
- ✅ **Pull Requests** with questions or insights
- ✅ **Issues** if you're stuck or see a gap

---

## 🛠 How to Contribute

### 1. Fork the Repository

Click the "Fork" button and clone it locally:

```bash
git clone https://github.com/mcgonagle/grow.git
cd grow
```

---

### 2. Folder Structure

Here's how the repostiory is organized:

```bash
grow/
├── 00-getting-started/ # Setup instructions and onboarding
├── 01-kubernetes-fundamentals/ # Pod and deployment labs
├── 02-gitops/ # FluxCD GitOps exercises
├── 03-security/ # PodSecurityContext and PSP labs
├── 04-services-ingress/ # Service and Ingress labs
├── 05-stateful-deploy/ # PersistentVolume and Stateful lab
├── 99-reflections/ # Weekly reflections (week1.md, week2.md, etc.)
├── docs/ # GitHub Pages content (MkDocs)
├── mkdocs.yml # Site configuration file
├── CONTRIBUTING.md # Contribution guidelines
└── README.md # Student portfolio overview
```


### 📌 Guidelines

- Add new labs in a new numbered folder (e.g., `06-statefulsets/`)
- Weekly reflections should go in `99-reflections/weekX.md`
- Markdown files for GitHub Pages go in `docs/`
- All YAML manifests should live alongside their lab's `lab-guide.md`




---

### 3. Make Your Changes

- Add your new lab YAMLs and `lab-guide.md` to a new folder (e.g., `06-volumes-lab/`)
- Add your reflection to `99-reflections/weekX.md`
- Update or fix an existing `lab-guide.md`
- Create a `questions/` file if you have something you’re stuck on

---

### 4. Commit and Push

```bash
git checkout -b add-my-lab
git add .
git commit -m "Add new lab for Week 6"
git push origin add-my-lab
```


Please use clear and consistent commit messages. This helps maintain a readable project history and reinforces best practices.

Suggested Format: `<type>: <short summary>`

Types:
- `lab:` for new or updated lab files
- `reflection:` for weekly updates in `99-reflections/`
- `fix:` for bug fixes or typo corrections
- `question:` for PRs that include questions or requests for help
- `docs:` for general documentation updates

Examples:
`lab: add Week 6 StatefulSet lab`
`reflection: add insights to week5.md`
`fix: corrected service port in web-service.yaml`
`question: flux kustomization sync issue`
`docs: update mkdocs.yml with new section`

---

### 5. Submit a Pull Request

Your PR title should follow one of these formats:

- `lab: add Week 6 StatefulSet lab`
- `reflection: add week5.md`
- `question: how to set up IngressClass`

---

## 🧠 Ask Questions via PR or Issue

- Want to ask a question? Open a **Pull Request** with your question in a Markdown file, or
- Use the **GitHub Issues tab** and select **"Ask a Question"**

We’ll respond right there and help guide you.

---

## 📣 Get Featured

The best contributions (labs, questions, portfolios) may be:

- Showcased on the KubeSkills blog
- Included in official GROW resources
- Shared on social media with attribution

---

## 🎥 Want to Create a GROW Video Tutorial?

If you enjoyed building a lab or explaining a concept, **teach it to others!**

### ✅ What You Can Record
- A walk-through of your lab or YAML files
- A demo of `kubectl` commands and output
- A live explanation of your weekly reflection
- A “what I learned” short video (2–10 mins)

### 🛠 Tools You Can Use
- [Loom](https://loom.com) or [OBS Studio](https://obsproject.com/)
- Screen recording tools like QuickTime or ShareX
- Your phone (just show your terminal and narrate)

### 💡 Tips
- Keep it short and focused on 1 concept
- Speak clearly and show the commands you're running
- Link to the files in your student notebook repo

### 📣 Where to Share
- Upload to YouTube, LinkedIn, or your GitHub README
- Tag with `#KubeSkillsGROW`
- Email your link to: [notebooks@kubeskills.com](mailto:notebooks@kubeskills.com)


We’ll feature the best ones in our community and learning portal!




---

## 🖥️ Preview Your Changes with MkDocs

Before submitting a Pull Request, you can preview your notebook or lab using [MkDocs](https://www.mkdocs.org/).

### Step 1: Install MkDocs

```bash
pip install mkdocs mkdocs-material
```

### Step 2: Run the Local Server

from the root of the project (where mkdocs.yml lives):
```bash
mkdocs serve
```
Then visit: http://localhost:8000

### Step 3: Troubleshoot

- If the site fails to build, check for:
  - Bad links or missing files in `docs/`
  - Indentation issues in `mkdocs.yml`
  - Missing frontmatter headers (`# Title`) in Markdown

✅ Good to Know
- All docs are located under `docs/`
- MkDocs auto-reloads as you save changes
- This is the same setup used to publish your portfolio site via GitHub Pages

---

## 📜 License

By contributing, you agree that your work may be publicly shared and used as part of the GROW initiative under the MIT License.

---

**Let’s learn together, grow in public, and prove our skills.**  
Thanks for being part of the community! 🌱
