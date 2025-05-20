# Function: <code>unmap_mapping_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bdf00)
Location: mm/memory.c:2408
Inline: False
Direct callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_page
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache_range
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_fallocate
  - fs/dax.c:__dax_fault
  - fs/kernfs/file.c:kernfs_unmap_bin_file
```
**Symbols:**

```
ffffffff811bdf00-ffffffff811be02e: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d9730)
Location: mm/memory.c:2480
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_page
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_fault
  - fs/kernfs/file.c:kernfs_unmap_bin_file
```
**Symbols:**

```
ffffffff811d9730-ffffffff811d9868: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e8b40)
Location: mm/memory.c:2498
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_page
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/kernfs/file.c:kernfs_unmap_bin_file
```
**Symbols:**

```
ffffffff811e8b40-ffffffff811e8c78: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f3da0)
Location: mm/memory.c:2704
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_page
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:grab_mapping_entry
  - fs/kernfs/file.c:kernfs_drain_open_files
```
**Symbols:**

```
ffffffff811f3da0-ffffffff811f3ed0: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120ba60)
Location: mm/memory.c:2825
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_cleanup_page
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/kernfs/file.c:kernfs_drain_open_files
```
**Symbols:**

```
ffffffff8120ba60-ffffffff8120bb90: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122d170)
Location: mm/memory.c:2896
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/kernfs/file.c:kernfs_drain_open_files
```
**Symbols:**

```
ffffffff8122d170-ffffffff8122d197: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81240700)
Location: mm/memory.c:2633
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
```
**Symbols:**

```
ffffffff81240700-ffffffff81240727: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812529b0)
Location: mm/memory.c:2701
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff812529b0-ffffffff812529d7: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81260f10)
Location: mm/memory.c:2726
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff81260f10-ffffffff81260f37: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81291380)
Location: mm/memory.c:3074
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:__devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff81291380-ffffffff812913a7: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129bcf0)
Location: mm/memory.c:3237
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff8129bcf0-ffffffff8129bd17: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0f90)
Location: mm/memory.c:3328
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff812a0f90-ffffffff812a0fb7: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e1910)
Location: mm/memory.c:3426
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff812e1910-ffffffff812e1937: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813425c0)
Location: mm/memory.c:3585
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff813425c0-ffffffff81342701: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ba750)
Location: mm/memory.c:3557
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:unmap_and_kill
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff813ba750-ffffffff813ba88e: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ef110)
Location: mm/memory.c:3560
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:unmap_and_kill
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
```
**Symbols:**

```
ffffffff813ef110-ffffffff813ef24b: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141aa80)
Location: mm/memory.c:3639
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:unmap_and_kill
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:unregister_dev_dax
  - drivers/gpu/drm/drm_drv.c:drm_dev_unplug
  - drivers/gpu/drm/drm_gem_shmem_helper.c:drm_gem_shmem_purge
```
**Symbols:**

```
ffffffff8141aa80-ffffffff8141abbb: unmap_mapping_range (STB_GLOBAL)
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
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f82b0)
Location: mm/memory.c:2726
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffff8000102f82b0-ffff8000102f8304: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051aa78)
Location: mm/memory.c:2726
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
c051aa78-c051aadc: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c1620)
Location: mm/memory.c:2726
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
c0000000003c1620-c0000000003c1650: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020884c)
Location: mm/memory.c:2726
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffe00020884c-ffffffe000208898: unmap_mapping_range (STB_GLOBAL)
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
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81259560)
Location: mm/memory.c:2726
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff81259560-ffffffff81259587: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124b9e0)
Location: mm/memory.c:2726
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff8124b9e0-ffffffff8124ba07: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81257300)
Location: mm/memory.c:2726
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff81257300-ffffffff81257327: unmap_mapping_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unmap_mapping_range(struct address_space *mapping, const loff_t holebegin, const loff_t holelen, int even_cows);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81266cf0)
Location: mm/memory.c:2726
Inline: False
Direct callers:
  - mm/truncate.c:truncate_pagecache_range
  - mm/truncate.c:truncate_pagecache
  - mm/truncate.c:truncate_pagecache
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/memory-failure.c:memory_failure
  - fs/dax.c:dax_layout_busy_page
  - fs/kernfs/file.c:kernfs_drain_open_files
  - drivers/dax/bus.c:kill_dev_dax
```
**Symbols:**

```
ffffffff81266cf0-ffffffff81266d17: unmap_mapping_range (STB_GLOBAL)
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
