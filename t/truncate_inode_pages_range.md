# Function: <code>truncate_inode_pages_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119ed10)
Location: mm/truncate.c:218
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache_range
```
**Symbols:**

```
ffffffff8119ed10-ffffffff8119f4e0: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b4870)
Location: mm/truncate.c:229
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
```
**Symbols:**

```
ffffffff811b4870-ffffffff811b5208: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c4ef0)
Location: mm/truncate.c:256
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff811c4ef0-ffffffff811c581f: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811cd300)
Location: mm/truncate.c:254
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff811cd300-ffffffff811cdb2e: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e25a0)
Location: mm/truncate.c:297
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff811e25a0-ffffffff811e2ed4: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81203c20)
Location: mm/truncate.c:293
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff81203c20-ffffffff81204539: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812165e0)
Location: mm/truncate.c:290
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff812165e0-ffffffff81216ef9: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff81226dca-ffffffff81226e0c: truncate_inode_pages_range.cold (STB_LOCAL)
ffffffff81225fc0-ffffffff8122685a: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81233e20)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff81233e20-ffffffff812346c6: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812613f0)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - fs/fuse/file.c:__fuse_copy_file_range
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff812613f0-ffffffff81261c8e: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126b7f0)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:truncate_bdev_range
  - fs/block_dev.c:truncate_bdev_range
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff8126b7f0-ffffffff8126bf88: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812708b0)
Location: mm/truncate.c:282
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:truncate_bdev_range
  - fs/block_dev.c:truncate_bdev_range
  - fs/fuse/file.c:__fuse_copy_file_range
```
**Symbols:**

```
ffffffff812708b0-ffffffff81270e87: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812ad7c0)
Location: mm/truncate.c:282
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fuse/file.c:__fuse_copy_file_range
  - block/bdev.c:truncate_bdev_range
  - block/bdev.c:truncate_bdev_range
```
**Symbols:**

```
ffffffff812ad7c0-ffffffff812ade50: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:330
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fuse/file.c:__fuse_copy_file_range
  - block/bdev.c:truncate_bdev_range
  - block/bdev.c:truncate_bdev_range
```
**Symbols:**

```
ffffffff81e6beb3-ffffffff81e6bef5: truncate_inode_pages_range.cold (STB_LOCAL)
ffffffff81308380-ffffffff81308a22: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:330
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fuse/file.c:__fuse_copy_file_range
  - block/bdev.c:truncate_bdev_range
  - block/bdev.c:truncate_bdev_range
```
**Symbols:**

```
ffffffff820627ef-ffffffff82062831: truncate_inode_pages_range.cold (STB_LOCAL)
ffffffff813722c0-ffffffff8137280b: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:330
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fuse/file.c:__fuse_copy_file_range
  - block/bdev.c:truncate_bdev_range
  - block/bdev.c:truncate_bdev_range
```
**Symbols:**

```
ffffffff820e1f9a-ffffffff820e1fdc: truncate_inode_pages_range.cold (STB_LOCAL)
ffffffff813a4450-ffffffff813a497d: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:320
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/jbd2/journal.c:__jbd2_journal_erase
  - fs/fuse/file.c:__fuse_copy_file_range
  - block/bdev.c:truncate_bdev_range
  - block/bdev.c:truncate_bdev_range
```
**Symbols:**

```
ffffffff821be9b0-ffffffff821be9f0: truncate_inode_pages_range.cold (STB_LOCAL)
ffffffff813cdfb0-ffffffff813ce4d8: truncate_inode_pages_range (STB_GLOBAL)
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
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c4510)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffff8000102c4510-ffff8000102c4c38: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04eede4)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
c04eede4-c04ef504: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037e9f0)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
c00000000037e9f0-c00000000037f3c0: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e4e36)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffe0001e4e36-ffffffe0001e53ac: truncate_inode_pages_range (STB_GLOBAL)
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
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122c470)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff8122c470-ffffffff8122cd16: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121f550)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff8121f550-ffffffff8121fdf6: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122a210)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff8122a210-ffffffff8122aab6: truncate_inode_pages_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void truncate_inode_pages_range(struct address_space *mapping, loff_t lstart, loff_t lend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81239600)
Location: mm/truncate.c:291
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_inode_pages_final
  - fs/block_dev.c:blkdev_fallocate
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blk_ioctl_discard
```
**Symbols:**

```
ffffffff81239600-ffffffff81239ec1: truncate_inode_pages_range (STB_GLOBAL)
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
