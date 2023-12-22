# SAE Aero Design 2024 Repository

This is a repository meant for WatArrow to share competition materials regarding the SAE Aero Design 2024 Competition. All contents of this repository are private until open sourced in the future.

---

## CAD Usage

### Making Changes

1. Create a new branch (thomasjuhonkim/test-branch)
2. Switch to your branch
3. Make your changes
   1. Open your **subsystem's** assembly file **(It is crucial you make your changes in subsystem assembly files NOT the full assembly file)**
   2. Make your CAD changes
   3. Save your work
4. Add your changes on GitHub Desktop
5. Make commits
6. Push your branch to GitHub

### Making Your Work Official

1. Create a Pull Request (thomasjuhoonkim/test-branch -> main)
2. Verify your changes
3. Write a descriptive title and description (Remember to utilize **Markdown Syntax**)
4. Add metadata
   1. Add yourself as the assignee
   2. Add supervisors as reviewer(s)
5. Complete the pull request
6. Wait for approval
7. Once approved, **Squash and Merge**

---

## Notes

- MAKE SURE TO CHECKOUT FILES ON THE **[FILE VAULT](https://github.com/orgs/watarrow/projects/1/views/1)**
- MAKE SURE TO CREATE/DELETE FILES ON THE FILE VAULT
- ~~Automation workflows are set up such that tracking the File Vault is handled automatically.~~
  - ~~If you are creating or deleting assemblies, creation and deletion of issues on the File Vault are handled upon Pull Request merge.~~
- DO NOT DELETE `Full Assembly.SLDASM` This is the master assembly that is crucial to our asynchronous workflows.
- DO NOT DELETE `.gitignore` as this file prevents temporary files such as `~${your-file.SLDPRT}` from being committed.

---

**If you run into any problems or have any questions, please message the #GitHub channel on the WatArrow Discord.**
