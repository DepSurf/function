# Function: <code>md_bitmap_file_set_bit</code>

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
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8182f0a0)
Location: drivers/md/md-bitmap.c:926
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff8182f0a0-ffffffff8182f18d: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818716c0)
Location: drivers/md/md-bitmap.c:927
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff818716c0-ffffffff818717af: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a34c0)
Location: drivers/md/md-bitmap.c:927
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff818a34c0-ffffffff818a35af: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81973950)
Location: drivers/md/md-bitmap.c:923
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff81973950-ffffffff81973a3d: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81978850)
Location: drivers/md/md-bitmap.c:924
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff81978850-ffffffff8197893d: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195be70)
Location: drivers/md/md-bitmap.c:924
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff8195be70-ffffffff8195bf5d: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:924
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff81a01660-ffffffff81a0175c: md_bitmap_file_set_bit (STB_LOCAL)
ffffffff81d29480-ffffffff81d294a4: md_bitmap_file_set_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:925
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff81b69450-ffffffff81b69575: md_bitmap_file_set_bit (STB_LOCAL)
ffffffff81ef55b9-ffffffff81ef55dd: md_bitmap_file_set_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:925
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff81d04fe0-ffffffff81d05105: md_bitmap_file_set_bit (STB_LOCAL)
ffffffff820a7ff2-ffffffff820a8016: md_bitmap_file_set_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:941
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff81d6e0d0-ffffffff81d6e1f5: md_bitmap_file_set_bit (STB_LOCAL)
ffffffff821293c9-ffffffff821293ed: md_bitmap_file_set_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:945
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff81e256e0-ffffffff81e25803: md_bitmap_file_set_bit (STB_LOCAL)
ffffffff8220adb8-ffffffff8220addc: md_bitmap_file_set_bit.cold (STB_LOCAL)
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
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af7fc8)
Location: drivers/md/md-bitmap.c:927
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffff800010af7fc8-ffff800010af811c: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bd7144)
Location: drivers/md/md-bitmap.c:927
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
c0bd7144-c0bd7234: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be2d90)
Location: drivers/md/md-bitmap.c:927
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
c000000000be2d90-c000000000be2f24: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006e8ae4)
Location: drivers/md/md-bitmap.c:927
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffe0006e8ae4-ffffffe0006e8c04: md_bitmap_file_set_bit (STB_LOCAL)
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
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81849340)
Location: drivers/md/md-bitmap.c:927
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff81849340-ffffffff8184942f: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818109a0)
Location: drivers/md/md-bitmap.c:927
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff818109a0-ffffffff81810a8f: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81898970)
Location: drivers/md/md-bitmap.c:927
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff81898970-ffffffff81898a5f: md_bitmap_file_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void md_bitmap_file_set_bit(struct bitmap *bitmap, sector_t block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b59d0)
Location: drivers/md/md-bitmap.c:927
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_dirty_bits
  - drivers/md/md-bitmap.c:md_bitmap_startwrite
```
**Symbols:**

```
ffffffff818b59d0-ffffffff818b5ada: md_bitmap_file_set_bit (STB_LOCAL)
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
