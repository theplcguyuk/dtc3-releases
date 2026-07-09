# DTC3 Releases

Public firmware release assets for the DTC3 ecosystem.

- Signed OTA releases: tagged `DTC3-<Project>-v<X.Y.Z>`, consumed by each
  device's own SecureOTA update flow (browser bridge over the device's Wi-Fi
  AP, or the commissioning-station tool).
- Raw USB-flash bins: tagged `DTC3-<Project>-raw-v<X.Y.Z>`, consumed by
  `shared/tools/flash-tool/flash.html` (ESP Web Tools, Web Serial) for
  bench/field USB bootstrap flashing.

Source lives in the private DTC3 monorepo; this repo only hosts public
release binaries.
