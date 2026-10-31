# Weavien Public Homepage

This repository contains the public Weavien landing page, user guides, and the GitHub Pages deployment workflow. **It does not contain the Weavien application source code.** The full application source is maintained separately in a private repository.

## Publish the homepage

1. Create a public GitHub repository for this package and upload the contents of this folder to its `main` branch.
2. In **Settings → Pages**, choose **GitHub Actions** as the deployment source.
3. Check the **Actions** tab for the `Publish Weavien homepage` workflow.

The workflow publishes only `website/`; it generates repository, documentation, and Releases links from the public homepage repository. To publish a Windows download, attach the ZIP to a release in this public repository.

The WeChat and Alipay images are clearly marked non-payment placeholders. Replace them and verify both codes before enabling real support.

The included `LICENSE` is a restrictive preview evaluation license, not an open-source license.
