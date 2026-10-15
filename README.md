# Step Race support website

Bilingual static website for GitHub Pages. Upload the contents of this directory to the root of a public `step-race-support` repository. Enable Settings → Pages → Deploy from a branch → main → /(root). No dependencies, build process, external fonts or analytics.

Pages: tr/index.html, tr/privacy.html, tr/terms.html, tr/delete-account.html, and corresponding en pages. The account-deletion email link is a manual support request, not automatic deletion.

## Owner review before store submission

Confirm developer identity, currently deployed data model, remote-notification providers, hosting regions, log retention, backup existence and backup deletion/expiry. Current copy describes uncertainty rather than promising deletion from logs/backups. Set actual retention periods and operational support procedure before final store submission. Review the full privacy/terms text as the service operator. No legal-compliance guarantee is implied.

Support: steprace.support@gmail.com. Huawei Health and paid billing are excluded from this release.

Source checks: backend delete-account.service.js and step-record.model.js; mobile provider/session/settings code. Current public guidance reviewed 2026-10-15: https://support.google.com/googleplay/android-developer/answer/13327111 and https://developer.apple.com/distribute/app-review/
