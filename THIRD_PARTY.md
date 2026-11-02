# Third-party components

- **OpenXR SDK** (Khronos Group), <https://github.com/KhronosGroup/OpenXR-SDK>, tag `release-1.1.62`. License: Apache-2.0
  (the headers are Apache-2.0 OR MIT). Monitor in VR Game's layer (`monitor_in_vr_game.dll`) is built against the OpenXR
  **headers** only; no OpenXR code is linked into or shipped with it. The OpenXR loader (`openxr_loader.dll`) is built only
  for the test programs and is not part of the installer.
- **Windows SDK components** used through the operating system (not redistributed): Direct3D 11, Direct3D 12 and
  D3D11On12, DXGI (Desktop Duplication), D3DCompiler, Windows.Media (the system media session), WASAPI (per-app volume), GDI
  (the on-panel labels and the control pictures).

Monitor in VR Game ships no third-party binary: the installer contains only its own layer DLL, its manifest, the default
`config.ini` and the documentation.
