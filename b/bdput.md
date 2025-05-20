# Function: <code>bdput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81247cd0)
Location: fs/block_dev.c:685
Inline: True
Inline callers:
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_open
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:SyS_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff81247cd0-ffffffff81247ce4: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812711b2)
Location: fs/block_dev.c:763
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:SyS_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81270520-ffffffff81270534: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81284b1f)
Location: fs/block_dev.c:1015
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:SyS_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81283cf0-ffffffff81283d04: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81291eab)
Location: fs/block_dev.c:931
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:SyS_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81290a70-ffffffff81290a84: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b4c2b)
Location: fs/block_dev.c:921
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:SyS_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:dm_pr_clear
  - drivers/md/dm.c:dm_pr_preempt
  - drivers/md/dm.c:dm_pr_release
  - drivers/md/dm.c:dm_pr_reserve
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:dm_blk_ioctl
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff812b3750-ffffffff812b3764: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dcdad)
Location: fs/block_dev.c:922
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff812db610-ffffffff812db624: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f220d)
Location: fs/block_dev.c:961
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff812f0b60-ffffffff812f0b74: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81313bfd)
Location: fs/block_dev.c:958
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_open
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff813124d0-ffffffff813124e4: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326b0d)
Location: fs/block_dev.c:958
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff81325420-ffffffff81325434: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360734)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
Direct callers:
  - kernel/power/user.c:snapshot_set_swap_area
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - block/genhd.c:invalidate_partition
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:bdev_del_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_closing
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_device
```
**Symbols:**

```
ffffffff8135ef60-ffffffff8135ef74: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136dfc3)
Location: fs/block_dev.c:957
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get_no_open
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - block/genhd.c:set_disk_ro
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:diskstats_show
  - block/genhd.c:disk_release
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:del_gendisk
  - block/genhd.c:register_disk
  - block/genhd.c:disk_part_iter_next
  - block/genhd.c:disk_part_iter_next
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:part_release
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_closing
```
**Symbols:**

```
ffffffff8136c440-ffffffff8136c454: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81374983)
Location: fs/block_dev.c:963
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get_no_open
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - init/do_mounts.c:devt_from_partuuid
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_release
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:bdev_del_partition
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:part_release
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81372d70-ffffffff81372d84: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1958)
Location: fs/block_dev.c:958
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffff8000103dfa60-ffff8000103dfa8c: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b8bcc)
Location: fs/block_dev.c:958
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/mtd/mtdsuper.c:get_tree_mtd
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
c05b7d24-c05b7d44: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e57c8)
Location: fs/block_dev.c:958
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
c0000000004e4a60-c0000000004e4a98: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000297eba)
Location: fs/block_dev.c:958
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffe0002967ea-ffffffe000296814: bdput (STB_GLOBAL)
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
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f0ed)
Location: fs/block_dev.c:958
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff8131da00-ffffffff8131da14: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130fc8d)
Location: fs/block_dev.c:958
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff8130e5a0-ffffffff8130e5b4: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131cbbd)
Location: fs/block_dev.c:958
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff8131b4d0-ffffffff8131b4e4: bdput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bdput(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132ddc1)
Location: fs/block_dev.c:958
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:revalidate_disk
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_forget
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - fs/quota/quota.c:kernel_quotactl
  - fs/quota/quota.c:kernel_quotactl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:invalidate_partition
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/xen-blkfront.c:blkif_release
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_get_dev_t
```
**Symbols:**

```
ffffffff8132d170-ffffffff8132d184: bdput (STB_GLOBAL)
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
