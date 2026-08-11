# DS Collaboration Frameworks — GitHub Flow Practice

A template repository for the 2026 MS-DS Bootcamp. Use it to practice the full **GitHub Flow** — issues → branch → commit → pull request → review → merge — on a tiny data science task, including creating and resolving a real merge conflict.

The file you'll work in is **`shape_attributes.py`**: it calculates the area, circumference, and diameter of a circle and a sphere of radius `r`.

---

## The exercise — GitHub Flow, in a pair

One team member creates a **private** repo from this template (**Use this template → Create a new repository**), then adds the second team member as a **collaborator** (**Settings → Collaborators**).

- **Team Member 1** opens **Issue #1 — "Define function for area of a sphere"** and assigns it to **Team Member 2**.
- **Team Member 1** opens **Issue #2 — "Define function for area of a circle"** and assigns it to **themselves**.

Now each of you complete your assigned issue:

1. Clone the repo: `git clone <URL>`
2. Create a branch named for your issue: `git checkout -b <branch_name>`
3. In a text editor, add your function at **line 11** of `shape_attributes.py` (under `### Area`), then save.
4. Commit your change: `git commit -am "your message here"`
5. Push your branch: `git push -u origin <branch_name>`
6. Open a **pull request**. In the description, write **`Closes #<your issue number>`** so the issue closes automatically on merge.

Then:

- **Team Member 1** reviews **Team Member 2's** pull request → **Merge** → **Delete branch** → close. Now pull up the Issues — is that issue closed?
- **Team Member 2** reviews **Team Member 1's** pull request → **UH OH, a conflict!** You both edited the same line. Team Member 2 resolves it right on GitHub using the web editor (keep **both** functions, delete the `<<<<`/`====`/`>>>>` markers) → **Merge** → **Delete branch** → close.

That's the whole loop. `main` now has both functions, both PRs are merged, and both issues are closed.

### Want more practice?

Run the exact same flow again for the **Circumference** functions — add them under `### Circumference` instead of `### Area`. Same steps, different section.

---

## Resources (from the session)

- **Vanderbilt data classification** — which AI/compute you can use for which data sensitivity level: <https://www.vanderbilt.edu/cybersecurity/guidelines/data-classification/>
- **GitHub Flow** overview: <https://docs.github.com/en/get-started/using-github/github-flow>
- **Connecting to GitHub with SSH** (keys + setup): <https://docs.github.com/en/authentication/connecting-to-github-with-ssh>
- **GitHub CLI (`gh`)**: <https://cli.github.com>
- **Claude Code**: <https://code.claude.com/docs>
- **LM Studio** — run open-source LLMs locally: <https://lmstudio.ai>
- **Hugging Face** — models: <https://huggingface.co>
