# Weavien public homepage deployment

This is a standalone public website repository. It contains the landing page and user-facing guides, but no application source code. The complete application source is kept in a separate private repository.

## First deployment

1. Push these files to the `main` branch of the public homepage repository.
2. Open **Settings → Pages → Build and deployment** and select **GitHub Actions**.
3. Confirm the `Publish Weavien homepage` action succeeds.

The workflow publishes only `website/`. At deployment, it copies the sponsor images and favicon and writes the public repository links into `website/repository.js`. Release links point to Releases for this public repository.

The sponsor images are placeholders and cannot accept payments. Replace and scan-verify both images before presenting live donation codes.
