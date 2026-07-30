# Development Notes

## Cleanroom Pro 4.0.0

The 4.0.0 rebuild turns the plugin into a complete Pro build for GitHub use. I stripped the old free/pro split has been stripped out because it made the admin feel like a corridor full of locked doors.

The feature class owns the new moving parts:

- upload log table setup and repair
- upload preflight rules
- user storage quotas
- role and user file extension rules
- attachment logging
- media library columns
- CSV export
- statistics helpers

The admin class owns menus, tabs, assets, and the original upload limit settings. That split is boring in the correct way.

## Notes on Older Versions

Version 1.x solved the basic file-size problem.

Version 2.x brought system status and memory controls. Good instincts, rough edges.

Version 3.x added role-based limits. Useful, but it still lived beside too much locked-feature copy.

Version 4.x makes the media workflow visible: who uploaded what, how large it is, where it is probably used, and whether a user should have uploaded it in the first place.

## Future Ideas

A background storage index would make quota screens faster on very large sites.

Usage detection could eventually parse block attributes and common page-builder JSON. That should happen in a queued process, not while an admin waits for a table to load.

Custom MIME registration might be useful, but it should stay separate from file type restrictions. Allowing more file types and restricting file types are not the same job, whatever a settings page may try to imply after midnight.