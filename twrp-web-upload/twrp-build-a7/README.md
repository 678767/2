# TWRP build repo — EEBBK A7 (ums512_1h10)

本仓库用于 GitHub Actions 云端编译 TWRP recovery.img。

- 设备：EEBBK A7 平板，Unisoc ums512_1h10，Android 11，kernel 4.14.193（prebuilt）
- 源码：minimal-manifest-twrp `platform_manifest_twrp_aosp` @ `twrp-12.1`（TWRP 3.7.1）
- 用法：仓库页面 → Actions → "Build TWRP for EEBBK A7" → Run workflow
- 产物：工作流结束后的 Artifacts 里下载 `twrp-recovery-ums512-1h10`（内含 recovery.img）
