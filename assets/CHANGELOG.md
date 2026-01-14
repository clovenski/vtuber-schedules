# Changelog

All notable changes to this project will be documented in this file.

## [v4.1.0] - 2026-01-13

### Changed

- Copyright year to be 2026
- The max oshi limit; increased from 20 to 40

## [v4.0.0] - 2025-11-29

### Changed

- Limited the window of streams showing here to be at most 7 days in past and future only

## [v3.0.5] - 2024-08-16

### Fixed

- Streamer preferences issue not applying when too many preferences

## [v3.0.4] - 2024-05-19

### Fixed

- Left docked panel being pushed up a bit on certain resolutions when scrolling to the end

## [v3.0.3] - 2024-04-22

### Added

- Viewer count to live streams
- Link in home page to request onboarding VTubers onto this website

### Changed

- Left docked panel to show scheduled start time for upcoming streams (without needing to hover over them)

## [v3.0.2] - 2024-04-16

### Added

- Popup to notify user when their 推し was offboarded (removed) from the application

## [v3.0.1] - 2024-04-15

### Fixed

- Badges that show number of YT VTubers supported, number of Twitch VTubers supported, etc.

## [v3.0.0] - 2024-04-14

### Added

- Upcoming streams in left docked panel
- My 推し Schedules - view a customized schedules page with your selected VTubers

### Changed

- Pagination in left docked panel
  - default / min page size decreased fro 20 to 15
  - page size incr / decr amount decreased from 10 to 5
- Settings page topmost divider to be less wide
- Left docked panel to be a little bit more aligned horizontally in text
- Filter in side navigation panel to not show streamers who don't have any streams found for them
- Onboarding documentation to have an alternative way to onboard VTubers than creating a GitHub issue
  - by reaching out to me on Discord or X (formerly Twitter)

### Removed

- Live viewer count until further notice

## [v2.2.1] - 2024-04-08

### Added

- Link to YouTube terms of service in footer and bottom of side navigation panel
- Added terms of service for this website, with link in footer and bottom of sidenav panel

### Changed

- Size of platform icon to be in compliance with YouTube TOS
- Left docked panel
  - Removed platform icon
  - Put platform below the live viewers count

## [v2.2.0] - 2024-04-07

### Added

- Docked left panel to quickly show who is currently live
- Platform logos in filter popup
- Curated sorting to have your commonly visited streamers higher in the list
- Settings page
  - Includes all previously implemented settings (dark mode, compact view, etc.)
  - New setting to toggle curated sorting
  - New setting to reset streamer preference metrics
  - New setting to opt out of streamer preferences

### Changed

- Viewer icon to be red instead of white while in dark mode on the home page

## [v2.1.6] - 2024-02-13

### Added

- Order for globie VTubers

## [v2.1.5] - 2024-02-12

### Added

- Back button for the reminders page

### Changed

- Copyright year

## [v2.1.4] - 2024-02-05

### Changed

- The styling for the affiliation link buttons in the home page and side navigation menu

## [v2.1.3] - 2024-02-05

### Added

- Order for FIRST STAGE PRODUCTION EN

### Fixed

- Styling of affiliation link buttons on home page + side navigation menu

## [v2.1.2] - 2024-01-24

### Added

- HELLø LAND V&U VTubers order

## [v2.1.1] - 2023-12-17

### Added

- Order for Phase Connect Gen 3 VTubers

## [v2.1.0] - 2023-12-06

### Added

- Setting favorite affiliations
- Info / links to footer

### Removed

- Affiliations buttons on home page for mobile

## [v2.0.6] - 2023-11-30

### Added

- Ordering for EIEN Project VTubers

## [v2.0.5] - 2023-11-20

### Added

- Ordering for V4Mirai VTubers

### Fixed

- Ordering for VReverie VTubers

## [v2.0.4] - 2023-11-18

### Added

- Ordering for HOLOSTARS EN Armis and VReverie

## [v2.0.3] - 2023-10-25

### Added

- Ordering for new Nijisanji EN VTubers

## [v2.0.2] - 2023-10-14

### Added

- Ordering for new kawaii VTubers and V&U agency

### Changed

- Browser tab title to be dynamic only for valid agencies

## [v2.0.1] - 2023-10-12

### Changed

- Streams that ended now show the time it started, along with the time it ended
- FAQ section to include instructions for the reminders feature

## [v2.0.0] - 2023-10-11

### Added

- Ordering for kawaii VTubers
- Dynamic browser tab title according to the page
- Relative time display (ex. how long until stream starts, stream ended how long ago, etc.)

### Changed

- Stream information to be compact and only show relevant info

## [v1.1.0] - 2023-10-08

### Added

- Feature to create calendar reminders of upcoming streams

## [v0.0.12] - 2023-09-30

### Added

- Mascot png to readme

## [v0.0.11] - 2023-09-30

### Fixed

- Mobile view being cut off at the bottom when address bar is present

## [v0.0.10] - 2023-09-30

### Added

- Button to jump to today's schedule
- Compact mode; being enabled by default on mobile

### Changed

- Past streams to be shown by default
- Dark mode toggle icon and text change when in dark mode

### Fixed

- Border color not changing right away when toggling dark mode

## [v0.0.9] - 2023-09-27

### Changed

- Affilition link buttons on home page to be more compact
- Side nav menu scrollbar styling to be more aligned with main content
- Inactivity prompt in home page to be below affiliation link buttons

### Fixed

- Inactivity prompt in home page and side nav menu header to adapt to smaller screen widths
- Scroll to top button not sticky on mobile (potentially)

## [v0.0.8] - 2023-09-26

### Fixed

- Past streams divider not showing when there are no live streams, but there are upcoming streams
- Stream titles truncation
  - Long titles not getting truncated properly
  - Short titles getting truncated when they shouldn't
- Styling for long streamer names (i.e. truncate them)
- Scrollbar changing length when scrolling to the top
- Scroll to top button not sticky on mobile (potentially)

## [v0.0.7] - 2023-09-23

### Added

- Ordering for affiliations
  - hololive-EN
  - hololive-ID
  - HOLOSTARS-EN
  - idol-EN
  - Phase Connect
  - PixelLink
  - PRISM Project

### Changed

- Default streamer filter ordering to use streamer name instead of channel id
- Minimum width of affiliation link buttons in home page
- Side nav header to be sticky top, with proper background color

### Fixed

- Divider showing at the end of streams list when not needed
- Onboarding prompt being shown when filtering out all streamers

## [v0.0.6] - 2023-09-23

### Added

- Badges in readme and onboarding doc regarding onboarding statistics

## [v0.0.5] - 2023-09-23

### Added

- Support for Twitch streamers

### Changed

- FAQ to reflect support for Twitch

## [v0.0.4] - 2023-09-22

### Added

- Viewer count for live streams
- Platform logo

## [v0.0.3] - 2023-09-14

### Added

- Back to top button
- Fix for toolbar styling issue when scrolling to live streams
- Fix for filter page not forcing refresh on resume button click

### Changed

- Scrollbar styling

## [v0.0.2] - 2023-09-13

### Added

- Phase Connect VTubers
- Ririsya, Shabel Tonya Independent VTubers
- Footer

### Changed

- Home page to show live streams in order (based on start time)

## [v0.0.1] - 2023-09-06

### Added

- The website
