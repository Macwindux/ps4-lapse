PS4 Lapse – GoldHEN Updated Host

A community-maintained adaptation of zecoxao's PS4 "ntfonto" exploit host, featuring an updated GoldHEN payload.

Overview

This project preserves the original CSSFontFace + Lapse exploit chain while updating the bundled GoldHEN payload.

The goal is to provide a simple, fast, browser-based host for compatible PlayStation 4 consoles.

This is not a new exploit. It is a modified distribution of an existing host.

Compatibility

Component| Details
Console| PlayStation 4
Tested firmware| 11.00
Entry point| CSSFontFace
Kernel exploit| Lapse
Payload| GoldHEN 2.4b18.14 (user-supplied build)
Execution| Browser-based, automatic payload loading

Tested successfully with GoldHEN 2.4b18.14 on PS4 firmware 11.00. Other firmware versions and console configurations have not been verified.
GoldHEN 2.4b18.14 adds firmware 14.02 support; compatibility with this host has not been verified on that firmware.

Usage

1. Fully restart the PS4 if GoldHEN is already running.

2. Open the PS4 Internet Browser.

3. Visit:
   
   https://macwindux.github.io/ps4-lapse/index.html

4. Follow the host's on-screen instructions.

5. Verify the loaded GoldHEN version.

Do not intentionally run the exploit again while GoldHEN is already active.

Changes from the Original

- Replaced the bundled GoldHEN payload with a newer build.
- Updated the application cache manifest.
- Preserved the original CSSFontFace + Lapse implementation.
- Preserved automatic payload loading.

The payload is served by the web host. This adaptation does not implement direct loading from the PS4 internal HDD or automatic USB payload updates.

Credits

- zecoxao — Original "ntfonto" host and project distribution.
- CSSFontFace and Lapse contributors — Original exploit research and implementation. See upstream projects for individual attribution.
- SiSTRo and GoldHEN contributors — GoldHEN development.
- Macwindux — Host adaptation, deployment, integration testing and maintenance.
- ChatGPT (OpenAI) — Technical assistance with the adaptation and deployment workflow.

All original components remain the work of their respective authors.

Original Projects

- https://github.com/zecoxao/zecoxao.github.io
- https://github.com/GoldHEN/GoldHEN

Disclaimer

This project is provided as-is, without warranties.

Running exploits or kernel payloads may cause crashes, unexpected shutdowns, storage checks or data loss.

Back up important data before experimenting.

This project is unofficial and is not affiliated with Sony Interactive Entertainment, zecoxao, SiSTRo or the GoldHEN development team.

Redistribution and Licensing

The original projects and their respective authors retain all applicable rights.

Redistribution of bundled components must comply with their individual licenses and permissions. Publication of source code does not automatically grant permission to redistribute every included binary.

Project Status

Tested successfully with GoldHEN 2.4b18.14 on PS4 firmware 11.00.

Contributions, technical feedback and compatibility reports are welcome.
