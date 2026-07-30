# Tabarc Maximum Upload File Size Pro

A complete WordPress media handling plugin for upload limits, role rules, user storage quotas, file type restrictions, upload logs, media size columns, statistics, and CSV reports.

This is the GitHub-ready Pro build. No locked sales page. No licence gate. No feature pretending to exist just out of reach.

## Top Features at a Glance

- **Upload Logs & Tracking**: Records user, file name, size, extension, MIME type, source, and timestamp.
- **Attachment Usage Detection**: Finds common usage in featured images, post/page content, and product galleries.
- **Set User Storage Disk Limit**: Adds total storage quotas per user.
- **File Type Restriction**: Restricts allowed extensions by role or individual user.
- **Role-Based Restrictions**: Sets upload limits for built-in and custom WordPress roles.
- **Media Manager**: Adds media library file size and uploader columns, plus a recent-media view.
- **Upload Statistics Dashboard**: Shows upload totals, storage use, top uploaders, and largest files.
- **Advanced Reporting**: Exports upload logs to CSV.
- **Auto Setup & Repair**: Creates and repairs the upload log table on activation and version changes.
- **Better Security**: Blocks quota or file type breaches before the upload lands.

## Installation

1. Copy the plugin folder to `wp-content/plugins/tabarc-maximum-upload-file-size`.
2. Activate **Tabarc Maximum Upload File Size Pro** in WordPress.
3. Open **Media > Tabarc MUFS Pro**.
4. Configure upload limits, quotas, file type rules, logs, statistics, and reports.

## What This Plugin Controls

The plugin can adjust WordPress-side upload behaviour, including upload size limits, execution time requests, memory limit requests, role upload limits, user storage quotas, and upload validation.

It cannot overrule a stricter host-level limit. If the server says 64 MB, WordPress can ask for 512 MB until it is blue in the face. The server still wins.

## Version Notes

### 4.0.0

Cleanroom Pro rebuild.

- Added upload log table and CSV export.
- Added user storage quotas.
- Added file type rules by role and user.
- Added media library size/uploader columns.
- Added media manager, statistics, reports, and feature overview tabs.
- Removed old locked screens and gated feature copy.
- Updated internal build ID to `cleanroom-pro-2026.07.29.1`.

### Earlier Versions

- `1.x`: upload size control.
- `2.x`: system status, memory controls, and cleaner settings.
- `3.x`: role-based limits.
- `4.x`: the point where the plugin stops gesturing at media management and actually does it.

## Future Ideas

- Background storage indexing for very large media libraries.
- Scheduled CSV reports for site owners who enjoy receiving tidy evidence.
- Deeper block parsing for attachment usage detection.
- Optional custom MIME registration, kept separate from restrictions so security remains readable.

## Development Notes

The code keeps comments short and practical. A few notes are left where past versions made an odd choice or where a future improvement is obvious. The tone is intentional: useful, slightly dry, and not written like a brochure wearing a lanyard.

## Licence

GPLv2 or later.