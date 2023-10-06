# Dolby Vision Profile 7 to 8 Converter and Utilities

This repository serves as a comprehensive toolkit for managing Dolby Vision profiles. It not only allows you to convert Dolby Vision Profile 7 to Profile 8 but also includes utilities for verifying Dolby Vision profiles and fetching Dolby Vision files from Plex.

## Table of Contents

- [Usage](#usage)
  - [Dolby Vision Tool (DDVT)](#dolby-vision-tool-ddvt)
  - [Verifying Dolby Vision Profiles](#verifying-dolby-vision-profiles)
  - [Profile 7 to 8 Converter](#profile-7-to-8-converter)
  - [Fetching Dolby Vision Files from Plex](#fetching-dolby-vision-files-from-plex)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Usage

### Dolby Vision Tool (DDVT)

Download the latest version of the Dolby Vision Tool from [Mega](https://mega.nz/folder/E5MjzAYD#xz9bKC8fnuQmOMo_ncjniQ).

To add DDVT to your context menu:
1. Navigate to `Dolby_Vision_Tool_v0.52/dolby_context_menu`.
2. Run `install_context_menu.ps1`.

This will add DDVT and its various tools as a submenu in your context menu.

### Verifying Dolby Vision Profiles

Run the `verify_dolby_status.ps1` script. This script utilises `mediainfo-cli` to check the Dolby Vision profile of a media file.

### Profile 7 to 8 Converter

The `profile7_to_profile8_converter` folder houses all you need for converting Profile 7 to Profile 8. It also includes options to add or remove this feature from your context menu for easy folder-level conversions.

To use:
1. Navigate to `profile7_to_profile8_converter`.
2. Execute `run_conversion.ps1`.

### Fetching Dolby Vision Files from Plex

Run `fetch_dolby_files_from_plex.py` to list all Profile 7 Dolby Vision files in your Plex library.

## Dependencies

All dependencies are included in the respective tool folders.

## Contributing

If you have suggestions for improvements or bug fixes, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See [LICENSE.md](LICENSE) for details.
