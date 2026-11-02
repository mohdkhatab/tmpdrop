# Note 49: Sharing code, patches, and text files with tmpdrop

Tmpdrop works well for more than photos and documents. It is also a handy way to share a small code file, a patch, or a snippet of text.

## What shares well

- A single source file, such as a script or a configuration file, that a colleague needs to try out.
- A patch or diff file, so a reviewer can see exactly what changed without a full repository checkout.
- A log file or an error trace, when someone is helping you debug a problem.

## Make the file easy to use

1. Give it a clear name and the right extension, for example `fix-login.patch` or `server-config.yaml`, so the recipient's editor recognises it.
2. If the file is a snippet, add a short comment at the top saying what it does and where it belongs.
3. Tell the recipient what to do with it: "Apply this patch with git apply", or "Drop this file into the config folder and restart."

## What does not share well this way

- A whole project with many files and dependencies. For that, use a repository or a proper archive, not a single temporary link.
- Secrets. Never share a file containing passwords, API keys, or private tokens through a temporary link. Remove secrets first, or share them through a dedicated secret-sharing tool.

## Tip

For code, a temporary link is for a quick look or a quick test. If the code is meant to last, put it in version control instead, and use tmpdrop only for the fast handoff.
