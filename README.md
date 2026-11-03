# Campaign Documentation for the Central Bureau of Communication

A document review portal provided by Adonmo Private Limited.

The GitHub Pages distribution contains a generic application and an encrypted campaign-document index. An authorised reviewer enters the separately supplied access code to unlock the collection. Document links keep their existing Google Drive permissions.

## Access and security

The data uses AES-256-GCM encryption with a random salt and IV, and PBKDF2-SHA256 at 600,000 iterations. The code and decrypted data are held in browser memory; reload, Lock workspace and 15 minutes of inactivity require the code again. No analytics, browser-storage session or third-party application scripts are used.

This is shared-code access, not individual identity management. Anyone possessing the code can decrypt the published package. Changing the code cannot revoke previously downloaded copies. The code is managed outside this repository.

## Publication

Publish the root of main with GitHub Pages. All asset paths are relative to the repository URL. Only reviewed encrypted publication files belong in this repository. Plaintext data, internal correspondence, drafts and access credentials must remain outside Git history.

Hosting reference: https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
