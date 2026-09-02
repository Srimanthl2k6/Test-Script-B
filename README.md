# Mastershot Auditions — Test Script B

A minimal static website that opens directly to the audition script PDF and provides a download button.

## Project structure

```text
.
├── index.html
├── styles.css
├── vercel.json
└── public/
    └── test-script-b.pdf
```

## Local preview

From the project folder, run any static server, for example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework Preset: **Other**.
4. Leave Build Command empty.
5. Leave Output Directory empty / use the repository root.
6. Deploy.

No environment variables or backend are required.

## Replace the script later

Replace `public/test-script-b.pdf` with another PDF using the same filename. No code changes are required.
