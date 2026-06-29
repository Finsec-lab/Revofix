# Changelog

## 1.0.3

- Info tab restructured: About, Contact, Privacy (three sections).
- Project scope narrowed to Revolut only.
- Fixed: state misclassification when a pending uninstall marker was present.
- Fixed: install failures with exit 0 now report as errors instead of "ready".
- Fixed: uninstall now updates the UI immediately to "Installed — reboot to activate".
- Fixed: install no longer hangs when root is unavailable.

## 1.0.2

- Added detection for the "no superuser prompt appeared" failure mode, with a
  one-tap deep-link to the Magisk overlay permission settings page.
- Added install fallbacks for KernelSU (`ksud`) and APatch (`apd`).
- Added support for `/product/bin/magisk` (Samsung One UI 7+).
- Wide-phone, tablet, foldable, and landscape layouts.

## 1.0.1

- Recoloured the primary action and brand to anthracite.
- Rewrote state detection to correctly differentiate "ready", "installed –
  reboot to activate", and "active".

## 1.0.0

- First public release.
