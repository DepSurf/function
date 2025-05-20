# Function: <code>truncate_pagecache_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119f610)
Location: mm/truncate.c:778
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_fallocate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff8119f610-ffffffff8119f66d: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b5340)
Location: mm/truncate.c:799
Inline: False
Direct callers:
  - fs/iomap.c:iomap_write_begin
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_fallocate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff811b5340-ffffffff811b539d: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c5950)
Location: mm/truncate.c:831
Inline: False
Direct callers:
  - fs/iomap.c:iomap_write_begin
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_fallocate
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff811c5950-ffffffff811c59ad: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811cdc60)
Location: mm/truncate.c:850
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff811cdc60-ffffffff811cdcbd: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e3010)
Location: mm/truncate.c:903
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff811e3010-ffffffff811e306d: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81204680)
Location: mm/truncate.c:894
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81204680-ffffffff812046df: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81217040)
Location: mm/truncate.c:895
Inline: False
Direct callers:
  - fs/iomap.c:iomap_write_end
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81217040-ffffffff8121709f: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812269a0)
Location: mm/truncate.c:898
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff812269a0-ffffffff81226a01: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81234810)
Location: mm/truncate.c:910
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81234810-ffffffff81234871: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81261dd0)
Location: mm/truncate.c:910
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81261dd0-ffffffff81261e31: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126c0d0)
Location: mm/truncate.c:938
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff8126c0d0-ffffffff8126c131: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81270fc0)
Location: mm/truncate.c:829
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81270fc0-ffffffff81271021: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812adf90)
Location: mm/truncate.c:828
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff812adf90-ffffffff812adff1: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81308b90)
Location: mm/truncate.c:846
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff81308b90-ffffffff81308bfd: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813729c0)
Location: mm/truncate.c:836
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff813729c0-ffffffff81372a2d: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813a4b20)
Location: mm/truncate.c:836
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff813a4b20-ffffffff813a4b8d: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813ce680)
Location: mm/truncate.c:825
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_write_begin
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff813ce680-ffffffff813ce6ed: truncate_pagecache_range (STB_GLOBAL)
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
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c4e50)
Location: mm/truncate.c:910
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffff8000102c4e50-ffff8000102c4ee8: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04ef6dc)
Location: mm/truncate.c:910
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_failed
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
c04ef6dc-c04ef798: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037f5d0)
Location: mm/truncate.c:910
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
c00000000037f5d0-c00000000037f670: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e5528)
Location: mm/truncate.c:910
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffe0001e5528-ffffffe0001e5598: truncate_pagecache_range (STB_GLOBAL)
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
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122ce60)
Location: mm/truncate.c:910
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff8122ce60-ffffffff8122cec1: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121ff30)
Location: mm/truncate.c:910
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff8121ff30-ffffffff8121ff91: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122ac00)
Location: mm/truncate.c:910
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff8122ac00-ffffffff8122ac61: truncate_pagecache_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void truncate_pagecache_range(struct inode *inode, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8123a000)
Location: mm/truncate.c:910
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/fuse/file.c:fuse_file_fallocate
```
**Symbols:**

```
ffffffff8123a000-ffffffff8123a061: truncate_pagecache_range (STB_GLOBAL)
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
