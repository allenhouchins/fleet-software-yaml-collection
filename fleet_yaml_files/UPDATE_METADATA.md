# Fleet YAML Files Update Metadata

## Last Update
- **Timestamp**: 2026-10-25 10:30:13 UTC
- **GitHub Actions Run**: https://github.com/allenhouchins/fleet-software-yaml-collection/actions/runs/40184858148
- **Total Files Generated**: 10066
- **macOS Files**: 454
- **Windows Files**: 9612

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
