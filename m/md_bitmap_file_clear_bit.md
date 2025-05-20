# Function: <code>md_bitmap_file_clear_bit</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8182e440)
Location: drivers/md/md-bitmap.c:955
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff8182e440-ffffffff8182e51a: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818717b0)
Location: drivers/md/md-bitmap.c:956
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff818717b0-ffffffff81871893: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a35b0)
Location: drivers/md/md-bitmap.c:956
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff818a35b0-ffffffff818a3693: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81973c10)
Location: drivers/md/md-bitmap.c:952
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff81973c10-ffffffff81973cf1: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81978b10)
Location: drivers/md/md-bitmap.c:953
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff81978b10-ffffffff81978bf1: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195bf60)
Location: drivers/md/md-bitmap.c:953
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff8195bf60-ffffffff8195c047: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:953
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff81a01760-ffffffff81a0185b: md_bitmap_file_clear_bit (STB_LOCAL)
ffffffff81d294a4-ffffffff81d294c8: md_bitmap_file_clear_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:954
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff81b6a160-ffffffff81b6a28e: md_bitmap_file_clear_bit (STB_LOCAL)
ffffffff81ef58c8-ffffffff81ef58ec: md_bitmap_file_clear_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:954
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff81d05410-ffffffff81d0553e: md_bitmap_file_clear_bit (STB_LOCAL)
ffffffff820a8035-ffffffff820a8059: md_bitmap_file_clear_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:970
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff81d6e4f0-ffffffff81d6e61e: md_bitmap_file_clear_bit (STB_LOCAL)
ffffffff8212940c-ffffffff82129430: md_bitmap_file_clear_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:975
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff81e261c0-ffffffff81e262e2: md_bitmap_file_clear_bit (STB_LOCAL)
ffffffff8220ae82-ffffffff8220aea6: md_bitmap_file_clear_bit.cold (STB_LOCAL)
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
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af8380)
Location: drivers/md/md-bitmap.c:956
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffff800010af8380-ffff800010af84c4: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bd7234)
Location: drivers/md/md-bitmap.c:956
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
c0bd7234-c0bd7320: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be2a70)
Location: drivers/md/md-bitmap.c:956
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
c000000000be2a70-c000000000be2bc0: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006e8928)
Location: drivers/md/md-bitmap.c:956
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffe0006e8928-ffffffe0006e8a42: md_bitmap_file_clear_bit (STB_LOCAL)
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
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81849430)
Location: drivers/md/md-bitmap.c:956
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff81849430-ffffffff81849513: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81810a90)
Location: drivers/md/md-bitmap.c:956
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff81810a90-ffffffff81810b73: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81898a60)
Location: drivers/md/md-bitmap.c:956
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff81898a60-ffffffff81898b43: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void md_bitmap_file_clear_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b5ca0)
Location: drivers/md/md-bitmap.c:956
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
```
**Symbols:**

```
ffffffff818b5ca0-ffffffff818b5da3: md_bitmap_file_clear_bit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
