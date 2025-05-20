# Function: <code>read_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169b8c0)
Location: drivers/md/bitmap.c:356
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff8169b8c0-ffffffff8169bb1e: read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fc9f0)
Location: drivers/md/bitmap.c:354
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff816fc9f0-ffffffff816fcc50: read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172e5c0)
Location: drivers/md/bitmap.c:357
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff8172e5c0-ffffffff8172e81c: read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81747530)
Location: drivers/md/bitmap.c:358
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81747530-ffffffff81747760: read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817b97c0)
Location: drivers/md/md-bitmap.c:358
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff817b97c0-ffffffff817b99f0: read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:358
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81801970-ffffffff81801b77: read_page (STB_LOCAL)
ffffffff81805f46-ffffffff81805f79: read_page.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:358
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff8182db80-ffffffff8182dd89: read_page (STB_LOCAL)
ffffffff818320d6-ffffffff81832109: read_page.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:359
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff818701d0-ffffffff818703f6: read_page (STB_LOCAL)
ffffffff818748a8-ffffffff818748df: read_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:359
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff818a1fd0-ffffffff818a21f6: read_page (STB_LOCAL)
ffffffff818a66b8-ffffffff818a66ef: read_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:351
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81972d60-ffffffff81972f84: read_page.isra.0 (STB_LOCAL)
ffffffff81976506-ffffffff81976545: read_page.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:351
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81977c80-ffffffff81977ea0: read_page.isra.0 (STB_LOCAL)
ffffffff81c27be1-ffffffff81c27c20: read_page.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:351
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff8195b790-ffffffff8195b9a9: read_page.isra.0 (STB_LOCAL)
ffffffff81c19da9-ffffffff81c19de8: read_page.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:351
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81a00f80-ffffffff81a011ae: read_page.isra.0 (STB_LOCAL)
ffffffff81d29401-ffffffff81d29480: read_page.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:351
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81b686c0-ffffffff81b6896f: read_page.isra.0 (STB_LOCAL)
ffffffff81ef54ad-ffffffff81ef5526: read_page.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:351
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81d04160-ffffffff81d04445: read_page.isra.0 (STB_LOCAL)
ffffffff820a7f1f-ffffffff820a7f5f: read_page.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:367
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81d6cef0-ffffffff81d6d1dc: read_page.isra.0 (STB_LOCAL)
ffffffff821292f7-ffffffff82129336: read_page.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af6f40)
Location: drivers/md/md-bitmap.c:359
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffff800010af6f40-ffff800010af71f8: read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bd7870)
Location: drivers/md/md-bitmap.c:359
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
c0bd7870-c0bd7b20: read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be2fc0)
Location: drivers/md/md-bitmap.c:359
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
c000000000be2fc0-c000000000be3390: read_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006e8c6a)
Location: drivers/md/md-bitmap.c:359
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffe0006e8c6a-ffffffe0006e8e74: read_page (STB_LOCAL)
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
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:359
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81847e50-ffffffff81848076: read_page (STB_LOCAL)
ffffffff8184c538-ffffffff8184c56f: read_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:359
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff8180f4b0-ffffffff8180f6d6: read_page (STB_LOCAL)
ffffffff81813b58-ffffffff81813b8f: read_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:359
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81897480-ffffffff818976a6: read_page (STB_LOCAL)
ffffffff8189bb68-ffffffff8189bb9f: read_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int read_page(struct file *file, long unsigned int index, struct bitmap *bitmap, long unsigned int count, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:359
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff818b3560-ffffffff818b3781: read_page (STB_LOCAL)
ffffffff818b7d18-ffffffff818b7d4f: read_page.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
