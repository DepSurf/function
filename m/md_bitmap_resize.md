# Function: <code>md_bitmap_resize</code>

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
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81830280)
Location: drivers/md/md-bitmap.c:2046
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81830280-ffffffff81830b19: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81874a4f-ffffffff81874a65: md_bitmap_resize.cold (STB_LOCAL)
ffffffff81872990-ffffffff8187322f: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff818a685f-ffffffff818a6875: md_bitmap_resize.cold (STB_LOCAL)
ffffffff818a4790-ffffffff818a502f: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2048
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff819765b5-ffffffff819765cb: md_bitmap_resize.cold (STB_LOCAL)
ffffffff81974280-ffffffff819749ad: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2051
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81c27c90-ffffffff81c27ca6: md_bitmap_resize.cold (STB_LOCAL)
ffffffff81979180-ffffffff819798ab: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81c19f72-ffffffff81c19f88: md_bitmap_resize.cold (STB_LOCAL)
ffffffff8195d630-ffffffff8195ded0: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81d297fd-ffffffff81d29a30: md_bitmap_resize.cold (STB_LOCAL)
ffffffff81a02ea0-ffffffff81a037e2: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2054
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81ef5953-ffffffff81ef5d0e: md_bitmap_resize.cold (STB_LOCAL)
ffffffff81b6aaa0-ffffffff81b6b633: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2054
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff820a8139-ffffffff820a84a9: md_bitmap_resize.cold (STB_LOCAL)
ffffffff81d06910-ffffffff81d07507: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2120
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff82129510-ffffffff821296be: md_bitmap_resize.cold (STB_LOCAL)
ffffffff81d6fbe0-ffffffff81d706a0: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2124
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8220aee6-ffffffff8220b05d: md_bitmap_resize.cold (STB_LOCAL)
ffffffff81e26ce0-ffffffff81e2772b: md_bitmap_resize (STB_GLOBAL)
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
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af8e88)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffff800010af8e88-ffff800010af95f4: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bd9d20)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
c0bd9d20-c0bda6c0: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be6f50)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
c000000000be6f50-c000000000be7908: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006eb0da)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffe0006eb0da-ffffffe0006eb78a: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8184c6df-ffffffff8184c6f5: md_bitmap_resize.cold (STB_LOCAL)
ffffffff8184a610-ffffffff8184aeaf: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff81813cff-ffffffff81813d15: md_bitmap_resize.cold (STB_LOCAL)
ffffffff81811c40-ffffffff818124d9: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8189bd0f-ffffffff8189bd25: md_bitmap_resize.cold (STB_LOCAL)
ffffffff81899c40-ffffffff8189a4df: md_bitmap_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int md_bitmap_resize(struct bitmap *bitmap, sector_t blocks, int chunksize, int init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:2053
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff818b7eb7-ffffffff818b7ecd: md_bitmap_resize.cold (STB_LOCAL)
ffffffff818b5db0-ffffffff818b6628: md_bitmap_resize (STB_GLOBAL)
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
