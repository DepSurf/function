# Function: <code>__fw_state_set</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e3051)
Location: drivers/base/firmware_class.c:145
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f7cc3)
Location: drivers/base/firmware_class.c:142
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165fc72)
Location: drivers/base/firmware_class.c:144
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:firmware_loading_store
  - drivers/base/firmware_class.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169aaf2)
Location: drivers/base/firmware_loader/firmware.h:102
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b7d3)
Location: drivers/base/firmware_loader/firmware.h:102
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816bb2fb)
Location: drivers/base/firmware_loader/firmware.h:102
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bc053)
Location: drivers/base/firmware_loader/firmware.h:102
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f5b34)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816f66d7)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81719f34)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8171aad7)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d5f59)
Location: drivers/base/firmware_loader/firmware.h:108
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817d6b33)
Location: drivers/base/firmware_loader/firmware.h:108
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff817d7225)
Location: drivers/base/firmware_loader/firmware.h:108
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ea9ca)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb6d9)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff817ebbb2)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817cf12d)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817cfe87)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff817d03a4)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81859812)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8185a6a6)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff8185abd4)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff819a0412)
Location: drivers/base/firmware_loader/firmware.h:114
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff819a1006)
Location: drivers/base/firmware_loader/firmware.h:114
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a1835)
Location: drivers/base/firmware_loader/firmware.h:114
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b11f9d)
Location: drivers/base/firmware_loader/firmware.h:112
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff81b12d06)
Location: drivers/base/firmware_loader/firmware.h:112
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b135d5)
Location: drivers/base/firmware_loader/firmware.h:112
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b6028d)
Location: drivers/base/firmware_loader/firmware.h:112
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff81b60ff6)
Location: drivers/base/firmware_loader/firmware.h:112
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b618db)
Location: drivers/base/firmware_loader/firmware.h:112
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb3ccd)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback_platform.c (ffffffff81bb4a86)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb536b)
Location: drivers/base/firmware_loader/firmware.h:113
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090d690)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffff80001090e008)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f66ec)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (c09f6f50)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009adc30)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (c0000000009aeb00)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000592154)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffe000592a62)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816e0264)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816e0e07)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba8a4)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bb447)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170d868)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:_request_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e4d7)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81728595)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817290f7)
Location: drivers/base/firmware_loader/firmware.h:104
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
</details>
</li>
</ul>

## Differences
