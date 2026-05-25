Synchronizer for N8N self-hosted thru Docker desktop

Allows working of self-hosted n8n in different computers through Git repository.

Initialization:

1. Create variables.ps1.
2. Copy contents of variablestemplate.ps1 and paste in variables.ps1.
3. Provide the new values.
4. Run init.ps1

---

NOTE: If you want to use Git to edit and sync workflows across devices, update useGit in variables.ps1 to true.
toGIT.ps1 pushes your workflow to Git, and toN8N pulls your workflow from Git and load it in n8n.
