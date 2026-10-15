# Security and maintenance

This repository contains educational prompts, instructions and a demonstration recording. It contains no generated application source or dependency lockfile, so there is no application dependency tree here to audit or upgrade.

## Before deploying an app built from these prompts

- Review the generated source, dependencies and deployed backend configuration. Keep dependencies and runtimes supported and patched; review advisories and test updates regularly.
- Keep transcription/AI credentials in server-only secrets. Use restricted test keys, spending caps and expiration where available. Never put secrets in prompts, browser bundles, public issues or recordings.
- Require authentication and server-side ownership checks for every clip, transcript, edit, storage operation and MCP tool. Use deny-by-default database and storage rules. A supplied project ID is not proof of authorization.
- Test isolation with two separate accounts and a signed-out client, including direct API/storage/MCP calls. Each account must be denied access to the other's data, and signed-out callers must not trigger paid requests.
- Validate upload size, duration and supported formats before processing. Enforce per-user quotas and rate limits on the server before invoking paid services.
- Review data retention, deletion and logging. Use the included public sample clip while learning; get appropriate permission before processing anyone else's recordings.
- Inspect requested assistant permissions and revoke connections and test keys when finished. Review cuts and exported playback, and keep the original recording.

The 15 October 2026 review strengthened the guidance and prompts and synchronized the ZIP. It did not review, update or deploy a generated Lovable app. No review guarantees that no vulnerability exists or will be discovered. Existing projects, forks and downloaded copies need their own ongoing maintenance.

## Reporting an issue

Report suspected vulnerabilities privately to support@bytegrad.com with the relevant file and commit/version. Do not post secrets, private recordings, personal data or exploit details in public issues. Existing course support and mandatory legal rights remain unchanged.
