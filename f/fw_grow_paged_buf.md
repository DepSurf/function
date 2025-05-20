# Function: <code>fw_grow_paged_buf</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f5440)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffff816f5440-ffffffff816f5530: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81719840)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffff81719840-ffffffff81719930: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d5980)
Location: drivers/base/firmware_loader/main.c:295
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffff817d5980-ffffffff817d5a70: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817ea390)
Location: drivers/base/firmware_loader/main.c:316
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz_pages
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffff817ea390-ffffffff817ea480: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817cea90)
Location: drivers/base/firmware_loader/main.c:317
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffff817cea90-ffffffff817ceb80: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff818591a0)
Location: drivers/base/firmware_loader/main.c:318
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffff818591a0-ffffffff81859290: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199fca0)
Location: drivers/base/firmware_loader/main.c:257
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
```
**Symbols:**

```
ffffffff8199fca0-ffffffff8199fdc0: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b11790)
Location: drivers/base/firmware_loader/main.c:257
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
```
**Symbols:**

```
ffffffff81b11790-ffffffff81b118b0: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5fa20)
Location: drivers/base/firmware_loader/main.c:257
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
```
**Symbols:**

```
ffffffff81b5fa20-ffffffff81b5fb93: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb3430)
Location: drivers/base/firmware_loader/main.c:258
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/sysfs.c:firmware_data_write
```
**Symbols:**

```
ffffffff81bb3430-ffffffff81bb35a3: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090ce68)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffff80001090ce68-ffff80001090cf6c: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f5f98)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
c09f5f98-c09f6084: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ad0a0)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
c0000000009ad0a0-c0000000009ad234: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe000591b72)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffe000591b72-ffffffe000591c82: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816dfb70)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffff816dfb70-ffffffff816dfc60: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba1b0)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffff816ba1b0-ffffffff816ba2a0: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170d290)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffff8170d290-ffffffff8170d380: fw_grow_paged_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fw_grow_paged_buf(struct fw_priv *fw_priv, int pages_needed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81727eb0)
Location: drivers/base/firmware_loader/main.c:286
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
  - drivers/base/firmware_loader/fallback.c:firmware_data_write
```
**Symbols:**

```
ffffffff81727eb0-ffffffff81727fa0: fw_grow_paged_buf (STB_GLOBAL)
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
