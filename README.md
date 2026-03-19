# github-actions-sg

Automatically uploads files to `gs://gs_actions_bucket/uploads/` via GitHub Actions.

## Usage

Drop files into the `files/` folder and push to `main`:

```bash
cp ~/your-file.csv files/
git add files/your-file.csv
git commit -m "Add file"
git push
```

The workflow triggers automatically and uploads to GCS.
