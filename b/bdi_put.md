# Function: <code>bdi_put</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e1400)
Location: mm/backing-dev.c:956
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff811e1400-ffffffff811e149b: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f78e9)
Location: mm/backing-dev.c:971
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff811f7860-ffffffff811f7880: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81218789)
Location: mm/backing-dev.c:969
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_exit_queue
```
**Symbols:**

```
ffffffff812188a0-ffffffff812188c5: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122ba89)
Location: mm/backing-dev.c:972
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-core.c:blk_exit_queue
```
**Symbols:**

```
ffffffff8122b9f0-ffffffff8122ba15: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123b6fd)
Location: mm/backing-dev.c:959
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8123b660-ffffffff8123b684: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81249c19)
Location: mm/backing-dev.c:1040
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81249b80-ffffffff81249ba4: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81277e8d)
Location: mm/backing-dev.c:1030
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:__blk_alloc_queue
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81277de0-ffffffff81277e1b: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812824ad)
Location: mm/backing-dev.c:899
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff81282410-ffffffff8128244b: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812875bd)
Location: mm/backing-dev.c:898
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff81287520-ffffffff8128755b: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c6706)
Location: mm/backing-dev.c:981
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/bdev.c:bdev_free_inode
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff812c6950-ffffffff812c69c1: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8132398a)
Location: mm/backing-dev.c:971
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/squashfs/super.c:squashfs_fill_super
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/bdev.c:bdev_free_inode
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff81323bb0-ffffffff81323c0f: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813981f7)
Location: mm/backing-dev.c:1094
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/bdev.c:bdev_free_inode
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff81398430-ffffffff8139848f: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813cb177)
Location: mm/backing-dev.c:1107
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/bdev.c:bdev_free_inode
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff813cb3b0-ffffffff813cb40f: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f5982)
Location: mm/backing-dev.c:1103
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
  - mm/backing-dev.c:cgwb_release_workfn
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/bdev.c:bdev_free_inode
  - block/genhd.c:__alloc_disk_node
```
**Symbols:**

```
ffffffff813f5650-ffffffff813f56af: bdi_put (STB_GLOBAL)
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
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102deee8)
Location: mm/backing-dev.c:1040
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffff8000102deee8-ffff8000102df004: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c0503d94)
Location: mm/backing-dev.c:1040
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/mtd/mtdcore.c:cleanup_mtd
  - drivers/mtd/mtdcore.c:init_mtd
  - drivers/mtd/mtdcore.c:init_mtd
```
**Symbols:**

```
c0503d94-c0503e80: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039e820)
Location: mm/backing-dev.c:1040
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
c00000000039e820-c00000000039e978: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f7196)
Location: mm/backing-dev.c:1040
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffe0001f6dbc-ffffffe0001f6e00: bdi_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81242269)
Location: mm/backing-dev.c:1040
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff812421d0-ffffffff812421f4: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81235239)
Location: mm/backing-dev.c:1040
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff812351a0-ffffffff812351c4: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81240009)
Location: mm/backing-dev.c:1040
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8123ff70-ffffffff8123ff94: bdi_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bdi_put(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124f769)
Location: mm/backing-dev.c:1040
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
Direct callers:
  - fs/super.c:super_setup_bdi_name
  - fs/super.c:generic_shutdown_super
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/block_dev.c:bdev_evict_inode
  - fs/fuse/inode.c:fuse_fill_super_common
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8124f6d0-ffffffff8124f6f4: bdi_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
