# Note 50: Keeping tmpdrop links out of public code and documents

A temporary link is easy to paste in the wrong place. Once it is in a public repository, a document, or a screenshot, you cannot reliably take it back before it expires.

## Places links leak by accident

- Committed into a repository: a link pasted into a README, a comment, or a configuration file, and then pushed.
- Left in a shared document or a slide deck that is later published or forwarded.
- Visible in a screenshot or a screen recording, for example in a browser tab bar or a chat window.
- Quoted in a reply: someone replies to your message with the whole thread, including the link, and forwards it further.

## How to avoid it

1. Send the link in a private message, not in a shared channel or a public issue, whenever the file is not meant to be public.
2. Before committing or publishing anything, search it for `http` and for the tmpdrop domain. A quick search catches most accidental pastes.
3. Before taking a screenshot, close tabs and windows that show links you do not want to share.
4. If a link does leak, do not panic and do not draw attention to it: the link will expire on its own. If the file is sensitive, re-uploading does not help — the leaked copy is already downloadable until expiry — so treat the file as shared and change anything in it that should not have been, such as a password or a token.

## Tip

Treat a tmpdrop link like a password in one respect: share it only with the people who need it, and only through the channel you chose for it.
