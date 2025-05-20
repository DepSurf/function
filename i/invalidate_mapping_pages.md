# Function: <code>invalidate_mapping_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119f6e0)
Location: mm/truncate.c:454
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/bitmap.c:bitmap_file_unmap
```
**Symbols:**

```
ffffffff8119f6e0-ffffffff8119f8e0: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b5420)
Location: mm/truncate.c:465
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:SyS_fadvise64
  - mm/fadvise.c:SyS_fadvise64
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/bitmap.c:bitmap_file_unmap
```
**Symbols:**

```
ffffffff811b5420-ffffffff811b56d3: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c5a30)
Location: mm/truncate.c:494
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:SyS_fadvise64
  - mm/fadvise.c:SyS_fadvise64
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/bitmap.c:bitmap_file_unmap
```
**Symbols:**

```
ffffffff811c5a30-ffffffff811c5cf3: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811cdd40)
Location: mm/truncate.c:493
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:SyS_fadvise64
  - mm/fadvise.c:SyS_fadvise64
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/bitmap.c:bitmap_file_unmap
```
**Symbols:**

```
ffffffff811cdd40-ffffffff811cdfd9: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e3100)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:SyS_fadvise64
  - mm/fadvise.c:SyS_fadvise64
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:bitmap_file_unmap
```
**Symbols:**

```
ffffffff811e3100-ffffffff811e342c: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81204770)
Location: mm/truncate.c:542
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/fadvise.c:ksys_fadvise64_64
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:bitmap_file_unmap
```
**Symbols:**

```
ffffffff81204770-ffffffff81204a87: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81217130)
Location: mm/truncate.c:543
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:vfs_fadvise
  - mm/fadvise.c:vfs_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff81217130-ffffffff8121745c: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:vfs_fadvise
  - mm/fadvise.c:vfs_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff81226e0c-ffffffff81226e1f: invalidate_mapping_pages.cold (STB_LOCAL)
ffffffff81226aa0-ffffffff81226d8d: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81234910)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff81234910-ffffffff81234cb6: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81261f30)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff81261f30-ffffffff812622e3: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126c600)
Location: mm/truncate.c:632
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff8126c600-ffffffff8126c612: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81271360)
Location: mm/truncate.c:529
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff81271360-ffffffff81271372: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812ae8e0)
Location: mm/truncate.c:530
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - block/bdev.c:invalidate_bdev
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff812ae8e0-ffffffff812ae8f2: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81308ec0)
Location: mm/truncate.c:564
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - block/bdev.c:__invalidate_device
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff81308ec0-ffffffff81308ede: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81372cc0)
Location: mm/truncate.c:556
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/fuse/file.c:fuse_cache_write_iter
  - block/bdev.c:__invalidate_device
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff81372cc0-ffffffff81372cde: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813a4e20)
Location: mm/truncate.c:556
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/libfs.c:direct_write_fallback
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/ext4/file.c:ext4_dio_write_iter
  - block/bdev.c:__invalidate_device
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff813a4e20-ffffffff813a4e3e: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813ce9a0)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/libfs.c:direct_write_fallback
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/ext4/file.c:ext4_dio_write_iter
  - block/bdev.c:bdev_mark_dead
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_purge
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff813ce9a0-ffffffff813ce9be: invalidate_mapping_pages (STB_GLOBAL)
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
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c4fa0)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffff8000102c4fa0-ffff8000102c533c: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04ef844)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
c04ef844-c04efa2c: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037f780)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
c00000000037f780-c00000000037fc98: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e5634)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffe0001e5634-ffffffe0001e582a: invalidate_mapping_pages (STB_GLOBAL)
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
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122cf60)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff8122cf60-ffffffff8122d306: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81220030)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff81220030-ffffffff812203d0: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122ad00)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff8122ad00-ffffffff8122b0a6: invalidate_mapping_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int invalidate_mapping_pages(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8123a100)
Location: mm/truncate.c:546
Inline: False
Direct callers:
  - mm/filemap.c:__generic_file_write_iter
  - mm/fadvise.c:generic_fadvise
  - mm/fadvise.c:generic_fadvise
  - fs/inode.c:inode_lru_isolate
  - fs/block_dev.c:invalidate_bdev
  - fs/drop_caches.c:drop_pagecache_sb
  - fs/fuse/file.c:fuse_file_write_iter
  - drivers/md/md-bitmap.c:md_bitmap_file_unmap
```
**Symbols:**

```
ffffffff8123a100-ffffffff8123a498: invalidate_mapping_pages (STB_GLOBAL)
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
