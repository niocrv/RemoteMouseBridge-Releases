# RemoteMouseBridge Downloads

Public download packages for **RemoteMouseBridge**, a Windows x64 utility that
converts absolute pointer updates from remote-desktop applications into relative
mouse movement suitable for 3D games.

## Download

Open the [v1.1.1 preview release](https://github.com/niocrv/RemoteMouseBridge-Releases/releases/tag/v1.1.1)
and download **RemoteMouseBridge-Windows-x64.zip**.

Current preview version: **1.1.1**

## Quick start

1. Connect from the local computer to the remote computer with your remote-desktop application.
2. On the remote computer, run RemoteMouseBridge.exe and choose **Host**.
3. On the local computer, run the same EXE and choose **Client**.
4. Press F7 near two opposite corners of the visible remote image.
5. Press F8 to enable or release pointer capture.
6. Use PageUp and PageDown on Host to adjust sensitivity. The default is 4.0x.

## Security

The EXE is unsigned and installs low-level input hooks while running. This can
trigger antivirus warnings. Do not disable antivirus protection. Verify the ZIP
against SHA256SUMS.txt before running it.

The published 1.1.1 ZIP was scanned locally with Microsoft Defender on
2026-09-17; no threats were reported. This is a test result, not a security
guarantee.

---

# Загрузки RemoteMouseBridge

Публичные проверяемые сборки RemoteMouseBridge для Windows 10/11 x64.

Скачайте **RemoteMouseBridge-Windows-x64.zip** из раздела
[Releases](https://github.com/niocrv/RemoteMouseBridge-Releases/releases).
На удалённом компьютере выберите **Host**, на локальном компьютере — **Client**.
F7 задаёт границы удалённого изображения, F8 включает и отключает захват,
PageUp/PageDown меняют чувствительность.

Перед запуском сравните SHA-256 архива с SHA256SUMS.txt. Не отключайте Defender
и не добавляйте неизвестные файлы в исключения.