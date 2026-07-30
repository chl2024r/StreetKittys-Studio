# Street Kittys Studio Release Checklist

Use this checklist before publishing any Street Kittys Studio installer.

## Identity

- [ ] Customer-facing version is correct
- [ ] Internal revision is correct
- [ ] Installer name uses `StreetKittys_Studio`
- [ ] Platform and architecture are clearly identified
- [ ] Included modules are listed accurately
- [ ] Beta status is visible

## Testing

- [ ] Fresh installation tested
- [ ] Upgrade installation tested
- [ ] Existing user data is preserved
- [ ] One Street Kittys Studio launcher is created
- [ ] Module tiles register correctly
- [ ] Open, update, repair, and remove actions were checked
- [ ] Regular users are not required to use Terminal or Bash
- [ ] Known issues are documented

## Security

- [ ] No passwords, tokens, private keys, or customer data are included
- [ ] Package contents were reviewed
- [ ] Malware scan completed
- [ ] SHA-256 checksum generated and verified
- [ ] Release signature verified when signing is available
- [ ] Private signing key remains outside GitHub

## GitHub release

- [ ] Tag follows `v1.0.0-beta-rXX`
- [ ] Release title follows `Street Kittys Studio 1.0.0 Beta — rXX`
- [ ] Release is marked as a pre-release
- [ ] Correct installer attached
- [ ] SHA-256 checksum attached or shown in release notes
- [ ] Supported Linux Mint versions and architecture stated
- [ ] Installation and upgrade instructions included
- [ ] Known limitations included
- [ ] Beta Evaluation License included or referenced

## Final approval

- [ ] Exact installer filename confirmed
- [ ] Exact checksum confirmed
- [ ] Release notes reviewed
- [ ] Final installer downloaded from GitHub and retested
