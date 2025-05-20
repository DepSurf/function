# Function: <code>__fw_state_check</code>

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
In drivers/base/firmware_class.c (ffffffff815e1e1a)
Location: drivers/base/firmware_class.c:167
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_loading_show
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
In drivers/base/firmware_class.c (ffffffff815f6a9c)
Location: drivers/base/firmware_class.c:160
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_loading_show
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
In drivers/base/firmware_class.c (ffffffff8165e9fc)
Location: drivers/base/firmware_class.c:162
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:firmware_loading_show
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
In drivers/base/firmware_loader/main.c (ffffffff8169ab2b)
Location: drivers/base/firmware_loader/firmware.h:80
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8169bcd1)
Location: drivers/base/firmware_loader/firmware.h:80
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff816bb333)
Location: drivers/base/firmware_loader/firmware.h:80
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bc45f)
Location: drivers/base/firmware_loader/firmware.h:80
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff816f5b2d)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816f6bab)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff81719f2d)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8171afac)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff817d5f53)
Location: drivers/base/firmware_loader/firmware.h:86
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817d6b05)
Location: drivers/base/firmware_loader/firmware.h:86
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff817ea9c4)
Location: drivers/base/firmware_loader/firmware.h:91
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb6ab)
Location: drivers/base/firmware_loader/firmware.h:91
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff817cf126)
Location: drivers/base/firmware_loader/firmware.h:91
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817cfd93)
Location: drivers/base/firmware_loader/firmware.h:91
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff8185980b)
Location: drivers/base/firmware_loader/firmware.h:91
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8185a5a3)
Location: drivers/base/firmware_loader/firmware.h:91
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff819a040b)
Location: drivers/base/firmware_loader/firmware.h:92
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff819a0ab3)
Location: drivers/base/firmware_loader/firmware.h:92
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff819a1764)
Location: drivers/base/firmware_loader/firmware.h:92
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_show
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
In drivers/base/firmware_loader/main.c (ffffffff81b11f96)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81b126d2)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b13504)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_show
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
In drivers/base/firmware_loader/main.c (ffffffff81b60286)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81b609c2)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b61814)
Location: drivers/base/firmware_loader/firmware.h:90
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_show
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
In drivers/base/firmware_loader/main.c (ffffffff81bb3cc6)
Location: drivers/base/firmware_loader/firmware.h:91
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff81bb441d)
Location: drivers/base/firmware_loader/firmware.h:91
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
  - drivers/base/firmware_loader/fallback.c:fw_load_sysfs_fallback
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb52a4)
Location: drivers/base/firmware_loader/firmware.h:91
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
  - drivers/base/firmware_loader/sysfs.c:firmware_data_read
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_show
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
In drivers/base/firmware_loader/main.c (ffff80001090d680)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffff80001090e884)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (c09f66e0)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (c09f7618)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (c0000000009adc24)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (c0000000009af134)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:fw_load_from_user_helper
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffe00059214a)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffe000592efe)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff816e025d)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816e12dc)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff816ba89d)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff816bb91c)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff8170d8a0)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e9ac)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
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
In drivers/base/firmware_loader/main.c (ffffffff8172858e)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
```
In drivers/base/firmware_loader/fallback.c (ffffffff817295cc)
Location: drivers/base/firmware_loader/firmware.h:82
Inline: True
Inline callers:
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
  - drivers/base/firmware_loader/fallback.c:firmware_data_read
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
  - drivers/base/firmware_loader/fallback.c:firmware_loading_show
  - drivers/base/firmware_loader/fallback.c:kill_pending_fw_fallback_reqs
```
</details>
</li>
</ul>

## Differences
