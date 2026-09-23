# Changelog

Notable changes to Podcast Forecast. The version matches `APP_VERSION` in `index.html`.

Add new notes under **Unreleased**. When you ship them, move those notes into a dated version section and set `APP_VERSION` to that version.

## [Unreleased]

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
