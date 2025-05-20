# Function: <code>fw_decompress_xz_pages</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f567e)
Location: drivers/base/firmware_loader/main.c:380
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
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
In drivers/base/firmware_loader/main.c (ffffffff81719a7e)
Location: drivers/base/firmware_loader/main.c:380
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz_pages(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:385
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
**Symbols:**

```
ffffffff817d5a70-ffffffff817d5be0: fw_decompress_xz_pages (STB_LOCAL)
ffffffff817d63c5-ffffffff817d63f0: fw_decompress_xz_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fw_decompress_xz_pages(struct device *dev, struct fw_priv *fw_priv, size_t in_size, const void *in_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/main.c (0)
Location: drivers/base/firmware_loader/main.c:406
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
**Symbols:**

```
ffffffff817ea480-ffffffff817ea5f0: fw_decompress_xz_pages (STB_LOCAL)
ffffffff81c0f187-ffffffff81c0f1b2: fw_decompress_xz_pages.cold (STB_LOCAL)
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
In drivers/base/firmware_loader/main.c (ffffffff817cec4b)
Location: drivers/base/firmware_loader/main.c:407
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
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
In drivers/base/firmware_loader/main.c (ffffffff8185935b)
Location: drivers/base/firmware_loader/main.c:408
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199ff24)
Location: drivers/base/firmware_loader/main.c:411
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b11a5b)
Location: drivers/base/firmware_loader/main.c:411
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5fd4b)
Location: drivers/base/firmware_loader/main.c:411
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb375b)
Location: drivers/base/firmware_loader/main.c:412
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
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
In drivers/base/firmware_loader/main.c (ffff80001090d148)
Location: drivers/base/firmware_loader/main.c:380
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
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
In drivers/base/firmware_loader/main.c (c09f61c8)
Location: drivers/base/firmware_loader/main.c:380
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
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
In drivers/base/firmware_loader/main.c (c0000000009ad410)
Location: drivers/base/firmware_loader/main.c:380
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
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
In drivers/base/firmware_loader/main.c (ffffffe000591d76)
Location: drivers/base/firmware_loader/main.c:380
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
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
In drivers/base/firmware_loader/main.c (ffffffff816dfdae)
Location: drivers/base/firmware_loader/main.c:380
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
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
In drivers/base/firmware_loader/main.c (ffffffff816ba3ee)
Location: drivers/base/firmware_loader/main.c:380
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817280ee)
Location: drivers/base/firmware_loader/main.c:380
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_decompress_xz
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
