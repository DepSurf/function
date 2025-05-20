# Function: <code>efi_get_embedded_fw</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efi_get_embedded_fw(const char *name, const u8 **data, size_t *size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/embedded-firmware.c (ffffffff819c1ead)
Location: drivers/firmware/efi/embedded-firmware.c:125
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff819c1ead-ffffffff819c1eca: efi_get_embedded_fw.cold (STB_LOCAL)
ffffffff819c1e20-ffffffff819c1ead: efi_get_embedded_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efi_get_embedded_fw(const char *name, const u8 **data, size_t *size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/embedded-firmware.c (ffffffff81c2cc54)
Location: drivers/firmware/efi/embedded-firmware.c:122
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff81c2cc54-ffffffff81c2cc71: efi_get_embedded_fw.cold (STB_LOCAL)
ffffffff819c2880-ffffffff819c290d: efi_get_embedded_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efi_get_embedded_fw(const char *name, const u8 **data, size_t *size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/embedded-firmware.c (ffffffff81c1ee82)
Location: drivers/firmware/efi/embedded-firmware.c:122
Inline: True
Direct callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff81c1ee82-ffffffff81c1ee9f: efi_get_embedded_fw.cold (STB_LOCAL)
ffffffff819a6cc0-ffffffff819a6d4d: efi_get_embedded_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int efi_get_embedded_fw(const char *name, const u8 **data, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/embedded-firmware.c (0)
Location: drivers/firmware/efi/embedded-firmware.c:122
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff81d30467-ffffffff81d30498: efi_get_embedded_fw.cold (STB_LOCAL)
ffffffff81a54060-ffffffff81a540f9: efi_get_embedded_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int efi_get_embedded_fw(const char *name, const u8 **data, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/embedded-firmware.c (0)
Location: drivers/firmware/efi/embedded-firmware.c:122
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff81efc89b-ffffffff81efc8c7: efi_get_embedded_fw.cold (STB_LOCAL)
ffffffff81bc3560-ffffffff81bc35ee: efi_get_embedded_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int efi_get_embedded_fw(const char *name, const u8 **data, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/embedded-firmware.c (0)
Location: drivers/firmware/efi/embedded-firmware.c:122
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff820a9f72-ffffffff820a9f86: efi_get_embedded_fw.cold (STB_LOCAL)
ffffffff81d68180-ffffffff81d6821d: efi_get_embedded_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int efi_get_embedded_fw(const char *name, const u8 **data, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/embedded-firmware.c (0)
Location: drivers/firmware/efi/embedded-firmware.c:122
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff8212b450-ffffffff8212b464: efi_get_embedded_fw.cold (STB_LOCAL)
ffffffff81dd32d0-ffffffff81dd336d: efi_get_embedded_fw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int efi_get_embedded_fw(const char *name, const u8 **data, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/embedded-firmware.c (0)
Location: drivers/firmware/efi/embedded-firmware.c:122
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff8220d14d-ffffffff8220d161: efi_get_embedded_fw.cold (STB_LOCAL)
ffffffff81e8b2e0-ffffffff81e8b37d: efi_get_embedded_fw (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
