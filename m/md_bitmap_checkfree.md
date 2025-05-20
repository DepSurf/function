# Function: <code>md_bitmap_checkfree</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8182eae2)
Location: drivers/md/md-bitmap.c:118
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff818710f4)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff818a2ee4)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff81971c14)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff81976b24)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff8195ad64)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff81a0054c)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff81b67c8c)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff81d0364c)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff81d6c43c)
Location: drivers/md/md-bitmap.c:112
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff81e2372c)
Location: drivers/md/md-bitmap.c:112
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffff800010af6950)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void md_bitmap_checkfree(struct bitmap_counts *bitmap, long unsigned int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bd6bb0)
Location: drivers/md/md-bitmap.c:119
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
c0bd6bb0-c0bd6c18: md_bitmap_checkfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void md_bitmap_checkfree(struct bitmap_counts *bitmap, long unsigned int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be2d00)
Location: drivers/md/md-bitmap.c:119
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
c000000000be2d00-c000000000be2d8c: md_bitmap_checkfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void md_bitmap_checkfree(struct bitmap_counts *bitmap, long unsigned int page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006e8a74)
Location: drivers/md/md-bitmap.c:119
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffe0006e8a74-ffffffe0006e8ae4: md_bitmap_checkfree (STB_LOCAL)
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
In drivers/md/md-bitmap.c (ffffffff81848d64)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff818103c4)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff81898394)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
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
In drivers/md/md-bitmap.c (ffffffff818b45b4)
Location: drivers/md/md-bitmap.c:119
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_count_page
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
