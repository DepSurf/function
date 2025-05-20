# Function: <code>md_bitmap_endwrite</code>

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
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8182fe80)
Location: drivers/md/md-bitmap.c:1459
Inline: False
```
**Symbols:**

```
ffffffff8182fe80-ffffffff81830082: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818725b0)
Location: drivers/md/md-bitmap.c:1460
Inline: False
```
**Symbols:**

```
ffffffff818725b0-ffffffff818727c0: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a43b0)
Location: drivers/md/md-bitmap.c:1460
Inline: False
```
**Symbols:**

```
ffffffff818a43b0-ffffffff818a45c0: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81973750)
Location: drivers/md/md-bitmap.c:1455
Inline: False
```
**Symbols:**

```
ffffffff81973750-ffffffff8197394a: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81978650)
Location: drivers/md/md-bitmap.c:1456
Inline: False
```
**Symbols:**

```
ffffffff81978650-ffffffff8197884a: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195d430)
Location: drivers/md/md-bitmap.c:1456
Inline: False
```
**Symbols:**

```
ffffffff8195d430-ffffffff8195d62a: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1456
Inline: False
```
**Symbols:**

```
ffffffff81d297de-ffffffff81d297fd: md_bitmap_endwrite.cold (STB_LOCAL)
ffffffff81a02c90-ffffffff81a02e94: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1457
Inline: False
```
**Symbols:**

```
ffffffff81ef559a-ffffffff81ef55b9: md_bitmap_endwrite.cold (STB_LOCAL)
ffffffff81b69200-ffffffff81b69446: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1457
Inline: False
```
**Symbols:**

```
ffffffff820a7fd3-ffffffff820a7ff2: md_bitmap_endwrite.cold (STB_LOCAL)
ffffffff81d04b80-ffffffff81d04dcd: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1524
Inline: False
```
**Symbols:**

```
ffffffff821293aa-ffffffff821293c9: md_bitmap_endwrite.cold (STB_LOCAL)
ffffffff81d6dc70-ffffffff81d6deb5: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1528
Inline: False
```
**Symbols:**

```
ffffffff8220ad99-ffffffff8220adb8: md_bitmap_endwrite.cold (STB_LOCAL)
ffffffff81e25270-ffffffff81e254b5: md_bitmap_endwrite (STB_GLOBAL)
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
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af7d18)
Location: drivers/md/md-bitmap.c:1460
Inline: False
```
**Symbols:**

```
ffff800010af7d18-ffff800010af7fc8: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bd7610)
Location: drivers/md/md-bitmap.c:1460
Inline: False
```
**Symbols:**

```
c0bd7610-c0bd7870: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be6c60)
Location: drivers/md/md-bitmap.c:1460
Inline: False
```
**Symbols:**

```
c000000000be6c60-c000000000be6f48: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006eaca6)
Location: drivers/md/md-bitmap.c:1460
Inline: False
```
**Symbols:**

```
ffffffe0006eaca6-ffffffe0006eae84: md_bitmap_endwrite (STB_GLOBAL)
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
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8184a230)
Location: drivers/md/md-bitmap.c:1460
Inline: False
```
**Symbols:**

```
ffffffff8184a230-ffffffff8184a440: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81811870)
Location: drivers/md/md-bitmap.c:1460
Inline: False
```
**Symbols:**

```
ffffffff81811870-ffffffff81811a80: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81899860)
Location: drivers/md/md-bitmap.c:1460
Inline: False
```
**Symbols:**

```
ffffffff81899860-ffffffff81899a70: md_bitmap_endwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void md_bitmap_endwrite(struct bitmap *bitmap, sector_t offset, long unsigned int sectors, int success, int behind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b53a0)
Location: drivers/md/md-bitmap.c:1460
Inline: False
```
**Symbols:**

```
ffffffff818b53a0-ffffffff818b55b0: md_bitmap_endwrite (STB_GLOBAL)
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
