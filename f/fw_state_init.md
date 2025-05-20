# Function: <code>fw_state_init</code>

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
In drivers/base/firmware_class.c (ffffffff815e3375)
Location: drivers/base/firmware_class.c:119
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
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
In drivers/base/firmware_class.c (ffffffff815f7d2f)
Location: drivers/base/firmware_class.c:118
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
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
In drivers/base/firmware_class.c (ffffffff8165fd00)
Location: drivers/base/firmware_class.c:120
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8169a9df)
Location: drivers/base/firmware_loader/main.c:152
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816bb1d5)
Location: drivers/base/firmware_loader/main.c:152
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f5a57)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81719e57)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d4f57)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ea02e)
Location: drivers/base/firmware_loader/main.c:154
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ce73e)
Location: drivers/base/firmware_loader/main.c:155
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81858fee)
Location: drivers/base/firmware_loader/main.c:156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fw_state_init(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199f7d5)
Location: drivers/base/firmware_loader/main.c:97
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8199f6b0-ffffffff8199f6f2: fw_state_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fw_state_init(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b11275)
Location: drivers/base/firmware_loader/main.c:97
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81b11140-ffffffff81b11182: fw_state_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fw_state_init(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5f5aa)
Location: drivers/base/firmware_loader/main.c:97
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_start
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_main
```
**Symbols:**

```
ffffffff81b5f3d0-ffffffff81b5f412: fw_state_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fw_state_init(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb2fb9)
Location: drivers/base/firmware_loader/main.c:98
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
Direct callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_start
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_main
```
**Symbols:**

```
ffffffff81bb2db0-ffffffff81bb2df2: fw_state_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090d5d4)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f65d8)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009adb3c)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000592054)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816e0187)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba7c7)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170d701)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817284bb)
Location: drivers/base/firmware_loader/main.c:153
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
