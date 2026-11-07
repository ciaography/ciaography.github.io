# Ciaography — hosting & updating

1. Create a GitHub repo, upload `index.html`, `photos.json` and the `images` folder.
2. Settings → Pages → Deploy from branch → `main` / root. Your site goes live.
3. Contact form: send a test message, then click the activation link FormSubmit emails you.

## Updating without touching files
1. GitHub → Settings → Developer settings → Fine-grained tokens → Generate.
   Select ONLY this repository; Permissions → Contents: Read and write.
2. Open `https://YOUR-SITE/?admin`, press "+ Manage photos", paste the token (saved only in your browser).
3. Upload photos, profile photo or Behance cover. The site updates in ~1 minute.
   ✎ edits a caption, × removes a photo (visible only in admin mode).

Text, links and services: edit the CONFIG block at the top of the script in `index.html`.
