# Changelog


## v3.0


- Bump version to v3.0
- Add CHANGELOG.md with initial release entry
- Improve README with prerequisites and install details
- Add release workflow with version check, changelog, and auto-update
- Add CI workflow with ShellCheck and zip verification
- Add cliff.toml for git-cliff changelog generation
- Add pre-commit hook for ShellCheck linting
- Update Makefile with setup target, atomic update, and expanded zip exclusions
- Expand .gitattributes with export-ignore for all dev files
- Expand .gitignore with build artifacts and local-only files
- Add shebang to customize.sh for shellcheck compatibility
- Add updateJson to module.prop for Magisk auto-update
- Refresh update-binary from upstream Magisk


## v2.0

- Added parted
- Added gptdisk utils

## v1.0

- Initial release
- Disk tools (fdisk, sfdisk, cgdisk, gdisk, sgdisk, fixparts, parted) for Android (aarch64)
