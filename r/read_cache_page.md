# Function: <code>read_cache_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e360)
Location: mm/filemap.c:2291
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:SyS_swapon
  - fs/ext4/symlink.c:ext4_encrypted_follow_link
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff8118e360-ffffffff8118e37b: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a1660)
Location: mm/filemap.c:2468
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:SyS_swapon
  - fs/namei.c:page_get_link
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff811a1660-ffffffff811a167b: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b14d0)
Location: mm/filemap.c:2584
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:SyS_swapon
  - fs/namei.c:page_get_link
  - fs/iomap.c:iomap_dirty_actor
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff811b14d0-ffffffff811b14e4: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b8890)
Location: mm/filemap.c:2718
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - fs/namei.c:page_get_link
  - fs/iomap.c:iomap_dirty_actor
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff811b8890-ffffffff811b88a4: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd0d0)
Location: mm/filemap.c:2888
Inline: False
Direct callers:
  - mm/swapfile.c:SYSC_swapon
  - fs/namei.c:page_get_link
  - fs/iomap.c:iomap_dirty_actor
  - fs/ext4/symlink.c:ext4_encrypted_get_link
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff811cd0d0-ffffffff811cd0e7: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ee200)
Location: mm/filemap.c:2888
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/iomap.c:iomap_dirty_actor
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff811ee200-ffffffff811ee217: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ff9a0)
Location: mm/filemap.c:2865
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/iomap.c:iomap_dirty_actor
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff811ff9a0-ffffffff811ff9b4: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81216a70)
Location: mm/filemap.c:2915
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff81216a70-ffffffff81216a84: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81224380)
Location: mm/filemap.c:2869
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:build_merkle_tree
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff81224380-ffffffff81224394: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81252fe0)
Location: mm/filemap.c:2878
Inline: False
Direct callers:
  - kernel/events/uprobes.c:copy_insn
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partitions/core.c:read_part_sector
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
**Symbols:**

```
ffffffff81252fe0-ffffffff81252ff4: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125dbb0)
Location: mm/filemap.c:3195
Inline: False
Direct callers:
  - kernel/events/uprobes.c:copy_insn
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partitions/core.c:read_part_sector
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
**Symbols:**

```
ffffffff8125dbb0-ffffffff8125dbc4: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81260950)
Location: mm/filemap.c:3442
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partitions/core.c:read_part_sector
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
**Symbols:**

```
ffffffff81260950-ffffffff81260964: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8129d340)
Location: mm/filemap.c:3557
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:read_file_data_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partitions/core.c:read_part_sector
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
**Symbols:**

```
ffffffff8129d340-ffffffff8129d354: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, filler_t *filler, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f43e0)
Location: mm/filemap.c:3608
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partitions/core.c:read_part_sector
```
**Symbols:**

```
ffffffff812f43e0-ffffffff812f4472: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, filler_t *filler, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135e500)
Location: mm/filemap.c:3602
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
**Symbols:**

```
ffffffff8135e500-ffffffff8135e561: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, filler_t *filler, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813912a0)
Location: mm/filemap.c:3770
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
**Symbols:**

```
ffffffff813912a0-ffffffff81391302: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, filler_t *filler, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813bb040)
Location: mm/filemap.c:3777
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
```
**Symbols:**

```
ffffffff813bb040-ffffffff813bb08c: read_cache_page (STB_GLOBAL)
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
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b19a8)
Location: mm/filemap.c:2869
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:build_merkle_tree
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffff8000102b19a8-ffff8000102b19f8: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04de634)
Location: mm/filemap.c:2869
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/read_write.c:vfs_dedupe_get_page
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:build_merkle_tree
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
c04de634-c04de660: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c0000000003677f0)
Location: mm/filemap.c:2869
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:__do_sys_swapon
  - fs/read_write.c:vfs_dedupe_get_page
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:build_merkle_tree
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
c0000000003677f0-c000000000367808: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d72fa)
Location: mm/filemap.c:2869
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - fs/read_write.c:vfs_dedupe_get_page
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:build_merkle_tree
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ext4/verity.c:pagecache_read
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffe0001d72fa-ffffffe0001d733e: read_cache_page (STB_GLOBAL)
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
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c9d0)
Location: mm/filemap.c:2869
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:build_merkle_tree
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff8121c9d0-ffffffff8121c9e4: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120fbb0)
Location: mm/filemap.c:2869
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:build_merkle_tree
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff8120fbb0-ffffffff8120fbc4: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121a770)
Location: mm/filemap.c:2869
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:build_merkle_tree
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff8121a770-ffffffff8121a784: read_cache_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *read_cache_page(struct address_space *mapping, long unsigned int index, int (*filler)(void *, struct page *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81229840)
Location: mm/filemap.c:2869
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uprobe
  - mm/swapfile.c:__do_sys_swapon
  - fs/namei.c:page_get_link
  - fs/verity/enable.c:build_merkle_tree
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/ext4/verity.c:ext4_read_merkle_tree_page
  - fs/ecryptfs/mmap.c:ecryptfs_get_locked_page
  - block/partition-generic.c:read_dev_sector
```
**Symbols:**

```
ffffffff81229840-ffffffff81229854: read_cache_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*filler)(void *, struct page *)</code> ➡️ <code>filler_t *filler</code>
</li>
</ul>
</details>
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
