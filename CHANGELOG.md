# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [2025-08-17]
### Added
- **Miscellaneous styling rules**:  
  - Global `box-sizing: border-box` with `Space Mono` font at 14px and 18px.  
- **Global styling rules**:  
  - `body:style(...)` injection for font family + size.  
  - `h1:style(...)` injection for font family + size.  
  - `.notice`  
  - `.packet.ineligible`  
  - `.banner-wrapper`  
  - `.floating-whatsapp`, `.floating-telegram`  
  - `.movie-wrapper`, `.livetx-wrapper`, `.game-list`  
  - `div#downloadapp`, `div#icons-container`  
  - `marquee > span`  
- Script now supports multiple rule types (`##` cosmetic, `#$#` CSS injection).

## [2025-08-13]
### Changed
- Standardized all domains in `filters/Clarity UI Gambling Site Filters.txt` to use the same set of 14 cosmetic selectors.
- Added two new universal selectors for all domains:
  - `##div.swal2-popup.swal2-modal.notice-popup.swal2-show`
  - `##div[style*="padding-bottom: 1%"]`

## [2025-08-11]
### Added
- Add MIT license to repository.
- Add README and LICENSE and CHANGELOG files created.
- Update README in MAIN with usage instructions.
- Fixed typo's.
- Update README in FILTERS folder with usage instructions.

## [2025-08-10]
- Update and rename gambling site filters.txt to Clarity UI Gambling Site Filters.txt , Revap!.

## [2025-08-09]
- Add more domains to the list over 20+.

## [2025-08-08]
- Update README.md.
- Update 1; aus-gambling-sites-adguard.
- Update 2; aus-gambling-sites-adguard.
- Disabled pokiesww.org, removed inactive domain wonpokies.com, and added new domains popmolly.net and anzspin.org.
- Update 3; rename aus-gambling-sites-adguard to aus-gambling-site-filters.
- Create README for the filters folder.

## [2025-08-07]
- Project created.
- Uploaded first version of the gambling site filter list.
