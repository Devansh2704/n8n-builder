# n8n-builder

This repository has been split, and the Prmpt.in leadgen assets now live under `prmptin-leadgen/` for extraction into a standalone repository.

## Next step
Create a new remote repository, then push from `prmptin-leadgen/`:

```bash
cd prmptin-leadgen
git init
git add .
git commit -m "Initial commit: Prmpt.in leadgen assets"
git branch -M main
git remote add origin <new-repo-url>
git push -u origin main
```
