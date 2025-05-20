# Function: <code>fw_map_paged_buf</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f5530)
Location: drivers/base/firmware_loader/main.c:319
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff816f5530-ffffffff816f55a2: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81719930)
Location: drivers/base/firmware_loader/main.c:319
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81719930-ffffffff817199a2: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d5b8a)
Location: drivers/base/firmware_loader/main.c:328
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff817d5cc0-ffffffff817d5d19: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ea59a)
Location: drivers/base/firmware_loader/main.c:349
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff817ea6d0-ffffffff817ea729: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ced13)
Location: drivers/base/firmware_loader/main.c:350
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff817ced70-ffffffff817cedc9: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81859423)
Location: drivers/base/firmware_loader/main.c:351
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81859480-ffffffff818594d9: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199fdc0)
Location: drivers/base/firmware_loader/main.c:290
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8199fdc0-ffffffff8199fe36: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b118c0)
Location: drivers/base/firmware_loader/main.c:290
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81b118c0-ffffffff81b11936: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5fbb0)
Location: drivers/base/firmware_loader/main.c:290
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81b5fbb0-ffffffff81b5fc26: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb35c0)
Location: drivers/base/firmware_loader/main.c:291
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/sysfs.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81bb35c0-ffffffff81bb3636: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090cf70)
Location: drivers/base/firmware_loader/main.c:319
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffff80001090cf70-ffff80001090d080: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f6084)
Location: drivers/base/firmware_loader/main.c:319
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
c09f6084-c09f60fc: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ad240)
Location: drivers/base/firmware_loader/main.c:319
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
c0000000009ad240-c0000000009ad2f0: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000591c82)
Location: drivers/base/firmware_loader/main.c:319
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffe000591c82-ffffffe000591cdc: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816dfc60)
Location: drivers/base/firmware_loader/main.c:319
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff816dfc60-ffffffff816dfcd2: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba2a0)
Location: drivers/base/firmware_loader/main.c:319
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff816ba2a0-ffffffff816ba312: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170d380)
Location: drivers/base/firmware_loader/main.c:319
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff8170d380-ffffffff8170d3f2: fw_map_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fw_map_paged_buf(struct fw_priv *fw_priv);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81727fa0)
Location: drivers/base/firmware_loader/main.c:319
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_loading_store
```
**Symbols:**

```
ffffffff81727fa0-ffffffff81728012: fw_map_paged_buf (STB_GLOBAL)
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
