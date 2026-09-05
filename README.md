# Authorization callback compatibility

Static authorization completion pages for existing Redexa Social installations.
These routes preserve the registered Instagram and TikTok callback URLs after
the application repository was renamed to `redexa-social`.

The pages do not redirect, run scripts, collect data or change the URL. The
desktop application reads the authorization response from its own login window.

[Redexa Social](https://github.com/AurelioAvila/redexa-social)
