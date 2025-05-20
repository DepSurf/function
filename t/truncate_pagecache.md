# Function: <code>truncate_pagecache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119f560)
Location: mm/truncate.c:670
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff8119f560-ffffffff8119f5c1: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b5290)
Location: mm/truncate.c:691
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff811b5290-ffffffff811b52f1: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c58a0)
Location: mm/truncate.c:723
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff811c58a0-ffffffff811c5901: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811cdbb0)
Location: mm/truncate.c:742
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff811cdbb0-ffffffff811cdc11: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e2f60)
Location: mm/truncate.c:795
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff811e2f60-ffffffff811e2fc1: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812045c0)
Location: mm/truncate.c:786
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff812045c0-ffffffff81204621: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81216f80)
Location: mm/truncate.c:787
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff81216f80-ffffffff81216fe1: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812268e0)
Location: mm/truncate.c:790
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff812268e0-ffffffff81226943: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81234750)
Location: mm/truncate.c:802
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff81234750-ffffffff812347b3: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81261d10)
Location: mm/truncate.c:802
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff81261d10-ffffffff81261d73: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126c010)
Location: mm/truncate.c:830
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff8126c010-ffffffff8126c073: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81270f00)
Location: mm/truncate.c:721
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff81270f00-ffffffff81270f63: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812aded0)
Location: mm/truncate.c:720
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff812aded0-ffffffff812adf33: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81308ac0)
Location: mm/truncate.c:738
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff81308ac0-ffffffff81308b2d: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813728d0)
Location: mm/truncate.c:728
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff813728d0-ffffffff8137293d: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813a4a30)
Location: mm/truncate.c:728
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff813a4a30-ffffffff813a4a9d: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813ce590)
Location: mm/truncate.c:717
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_direct_IO
  - fs/fat/inode.c:fat_write_end
  - fs/fat/inode.c:fat_write_begin
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/file.c:fuse_open_common
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff813ce590-ffffffff813ce5fd: truncate_pagecache (STB_GLOBAL)
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
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c4d70)
Location: mm/truncate.c:802
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffff8000102c4d70-ffff8000102c4de8: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04ef5bc)
Location: mm/truncate.c:802
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_write_failed
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
c04ef5bc-c04ef658: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037f4c0)
Location: mm/truncate.c:802
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_write_failed
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
c00000000037f4c0-c00000000037f550: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e5476)
Location: mm/truncate.c:802
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/inode.c:fat_write_failed
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffe0001e5476-ffffffe0001e54de: truncate_pagecache (STB_GLOBAL)
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
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122cda0)
Location: mm/truncate.c:802
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff8122cda0-ffffffff8122ce03: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121fe70)
Location: mm/truncate.c:802
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff8121fe70-ffffffff8121fed3: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122ab40)
Location: mm/truncate.c:802
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff8122ab40-ffffffff8122aba3: truncate_pagecache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void truncate_pagecache(struct inode *inode, loff_t newsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81239f40)
Location: mm/truncate.c:802
Inline: False
Direct callers:
  - mm/truncate.c:truncate_setsize
  - mm/truncate.c:truncate_setsize
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/inode.c:fuse_change_attributes
```
**Symbols:**

```
ffffffff81239f40-ffffffff81239fa3: truncate_pagecache (STB_GLOBAL)
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
