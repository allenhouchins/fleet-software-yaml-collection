# Fleet YAML Files Update Metadata

## Last Update
- **Timestamp**: 2025-11-26 06:05:24 UTC
- **GitHub Actions Run**: https://github.com/allenhouchins/fleet-software-yaml-collection/actions/runs/19694175545
- **Total Files Generated**: 6942
- **macOS Files**: 390
- **Windows Files**: 6552

## Sources
- **Homebrew Casks API** (macOS PKG files)
- **Installomator Script** (macOS PKG files)
- **WinGet Repository** (Windows MSI/EXE files)

## Filter Criteria
- **macOS**: Only PKG installer files (excludes ZIP, DMG, TAR, MPKG)
- **Windows**: Only x64 MSI and EXE installer files
- **Architecture**: x64 only for Windows installers

## Output Directory
fleet_yaml_files (organized by platform)

## File Structure
All files follow consistent Fleet YAML structure with appropriate parameters:
- Standard fields: url, automatic_install, self_service, categories
- EXE files include: install_script, uninstall_script (with TODO placeholders)
- Helpful comments with Fleet API documentation links

## Automation
This directory is automatically updated via GitHub Actions workflow.
