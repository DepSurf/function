# Function: <code>fw_free_paged_buf</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f4caf)
Location: drivers/base/firmware_loader/main.c:271
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff816f4a60-ffffffff816f4ab6: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff816f5420-ffffffff816f5438: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817190af)
Location: drivers/base/firmware_loader/main.c:271
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81718e60-ffffffff81718eb6: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff81719820-ffffffff81719838: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d4b52)
Location: drivers/base/firmware_loader/main.c:278
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff817d48d0-ffffffff817d4931: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff817d5960-ffffffff817d5978: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817e9486)
Location: drivers/base/firmware_loader/main.c:299
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff817e9290-ffffffff817e92f1: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff817ea370-ffffffff817ea388: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817cdc85)
Location: drivers/base/firmware_loader/main.c:300
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff817cda60-ffffffff817cdac1: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff817cea70-ffffffff817cea88: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81858490)
Location: drivers/base/firmware_loader/main.c:301
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81858250-ffffffff818582b1: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff81859180-ffffffff81859198: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199eea3)
Location: drivers/base/firmware_loader/main.c:238
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8199eb60-ffffffff8199ebdf: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff8199fc70-ffffffff8199fc94: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b108b5)
Location: drivers/base/firmware_loader/main.c:238
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81b10550-ffffffff81b105cf: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff81b11750-ffffffff81b11774: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5eb23)
Location: drivers/base/firmware_loader/main.c:238
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_start
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_main
```
**Symbols:**

```
ffffffff81b5e770-ffffffff81b5e7eb: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff81b5f9e0-ffffffff81b5fa04: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb2493)
Location: drivers/base/firmware_loader/main.c:239
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_start
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_main
```
**Symbols:**

```
ffffffff81bb20e0-ffffffff81bb215b: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff81bb33f0-ffffffff81bb3414: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090c4d4)
Location: drivers/base/firmware_loader/main.c:271
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffff80001090c270-ffff80001090c2d0: fw_free_paged_buf.part.0 (STB_LOCAL)
ffff80001090ce30-ffff80001090ce64: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f59ac)
Location: drivers/base/firmware_loader/main.c:271
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
c09f5778-c09f57dc: fw_free_paged_buf.part.0 (STB_LOCAL)
c09f5f70-c09f5f98: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ac38c)
Location: drivers/base/firmware_loader/main.c:271
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
c0000000009ac060-c0000000009ac0fc: fw_free_paged_buf.part.0 (STB_LOCAL)
c0000000009ad080-c0000000009ad0a0: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000591798)
Location: drivers/base/firmware_loader/main.c:271
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffe0005915cc-ffffffe00059162e: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffe000591b44-ffffffe000591b72: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816df3df)
Location: drivers/base/firmware_loader/main.c:271
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff816df190-ffffffff816df1e6: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff816dfb50-ffffffff816dfb68: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816b9a1f)
Location: drivers/base/firmware_loader/main.c:271
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff816b97d0-ffffffff816b9826: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff816ba190-ffffffff816ba1a8: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170cf9b)
Location: drivers/base/firmware_loader/main.c:271
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8170cb20-ffffffff8170cb76: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff8170d270-ffffffff8170d288: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fw_free_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8172786f)
Location: drivers/base/firmware_loader/main.c:271
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
  - drivers/base/firmware_loader/main.c:__free_fw_priv
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81727620-ffffffff81727676: fw_free_paged_buf.part.0 (STB_LOCAL)
ffffffff81727e90-ffffffff81727ea8: fw_free_paged_buf (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
