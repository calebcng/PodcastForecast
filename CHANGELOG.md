# Changelog

Notable changes to Podcast Forecast. The version matches `APP_VERSION` in `index.html`.

## [Unreleased]

## [1.1.0] - 2026-09-25

### Added

- Undo and redo for schedule changes, from the toolbar or with the usual keyboard shortcuts.
- Rearrange timeline rows. Each writing and editing team is its own row, so those lanes can sit next to each other, and production, post-production, and release can sit between them. The order is kept until you reset, and a customized order is included in the share link. Settings stay in the fixed track order.

## [1.0.0] - 2026-09-23

### Added

- A version label at the bottom of the page, beside the share hint.
- Drag an episode onto another team on the same Writing or Editing track. The move follows the current On drag setting, and that team's chunk ranges split or merge so track setup matches the board.
- More than one episode range on the same chunk for a team, with add and remove.
- Compact share links in the URL fragment, so a full schedule opens in a new tab without the long query string GitHub Pages rejects.
- On drag choices: ask each time, readjust all following episodes, readjust the chunk, readjust following episodes in the chunk, or move only that episode.
- Editing and post-production tracks. Production and post-production can be timed runs or an episodes-per-week schedule, and those runs can be dragged on the calendar.
- Drag episodes to reschedule them. Writing, editing, and release can run at a weekly pace or on specific weekdays, with breaks and more than one team.
- Episode chunks, schedule notes, an editable title, zoom, and week counting from the earliest start date or from the start of that week.
- Light and dark themes, remembered in the browser.
- Copy link with these settings, which reopens the same configuration.

### Changed

- Pace fields accept whole numbers of at least 1.

### Fixed

- Pace mode controls for writing and release stay wired to the correct fields.
