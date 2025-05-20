# Function: <code>mapping_empty</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812703b9)
Location: include/linux/pagemap.h:21
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/block_dev.c (ffffffff8137455c)
Location: include/linux/pagemap.h:21
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
```
```
In fs/dax.c (ffffffff813a64da)
Location: include/linux/pagemap.h:21
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812ae039)
Location: include/linux/pagemap.h:21
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/inode.c (ffffffff8139650a)
Location: include/linux/pagemap.h:21
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/dax.c (ffffffff813f5f4a)
Location: include/linux/pagemap.h:21
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/drop_caches.c (ffffffff81410956)
Location: include/linux/pagemap.h:21
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In block/bdev.c (ffffffff815c42aa)
Location: include/linux/pagemap.h:21
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8130757d)
Location: include/linux/pagemap.h:135
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/inode.c (ffffffff81417a6b)
Location: include/linux/pagemap.h:135
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/dax.c (ffffffff81469b13)
Location: include/linux/pagemap.h:135
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/drop_caches.c (ffffffff814862a3)
Location: include/linux/pagemap.h:135
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In block/bdev.c (ffffffff8166ebdb)
Location: include/linux/pagemap.h:135
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813716a8)
Location: include/linux/pagemap.h:135
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/inode.c (ffffffff814a320b)
Location: include/linux/pagemap.h:135
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/dax.c (ffffffff814fa263)
Location: include/linux/pagemap.h:135
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/drop_caches.c (ffffffff81519b63)
Location: include/linux/pagemap.h:135
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In block/bdev.c (ffffffff81729ec8)
Location: include/linux/pagemap.h:135
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813a37b8)
Location: include/linux/pagemap.h:139
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/inode.c (ffffffff814d835b)
Location: include/linux/pagemap.h:139
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/dax.c (ffffffff815316e2)
Location: include/linux/pagemap.h:139
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/drop_caches.c (ffffffff81551453)
Location: include/linux/pagemap.h:139
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In block/bdev.c (ffffffff81766238)
Location: include/linux/pagemap.h:139
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813cd358)
Location: include/linux/pagemap.h:139
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_final
  - mm/truncate.c:truncate_inode_pages_range
```
```
In fs/inode.c (ffffffff8150ab3b)
Location: include/linux/pagemap.h:139
Inline: True
Inline callers:
  - fs/inode.c:inode_lru_isolate
```
```
In fs/dax.c (ffffffff815665c2)
Location: include/linux/pagemap.h:139
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/drop_caches.c (ffffffff81587353)
Location: include/linux/pagemap.h:139
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_pagecache_sb
```
```
In block/bdev.c (ffffffff817a7cf8)
Location: include/linux/pagemap.h:139
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
