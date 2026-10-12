# Personal Drive Sync

A public informational website and privacy policy for a personal [rclone Google Drive](https://rclone.org/drive/#making-your-own-client-id) OAuth client.

## GitHub Pages

Site: https://ronarendo-lgtm.github.io/  
Privacy: https://ronarendo-lgtm.github.io/privacy.html

Enable GitHub Pages under **Settings → Pages → Deploy from a branch → main → /(root)**.

## Google OAuth configuration

- App name: **Personal Drive Sync**
- Homepage: `https://ronarendo-lgtm.github.io/`
- Privacy policy: `https://ronarendo-lgtm.github.io/privacy.html`
- OAuth client application type: **Desktop app**
- This site is NOT an OAuth redirect URI. rclone uses local browser authorization.
- Whether a GitHub Pages subdomain is accepted as an authorized domain depends on Google's current domain ownership and verification requirements; do not assume publishing this site alone verifies the domain.

Never upload `rclone.conf`, access or refresh tokens, client secrets, or personal data. For an app used only by its owner, Google's Testing mode/test users may be sufficient; publishing can have additional verification requirements. Follow Google's current prompts and rclone's documentation.

Review the privacy policy periodically: it assumes a locally controlled personal rclone installation and no external application backend.
