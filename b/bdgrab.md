# Function: <code>bdgrab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81247cb0)
Location: fs/block_dev.c:666
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
Direct callers:
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:SyS_swapon
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff81247cb0-ffffffff81247ccc: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81271cf1)
Location: fs/block_dev.c:744
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
**Symbols:**

```
ffffffff81270500-ffffffff8127051c: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8128534c)
Location: fs/block_dev.c:996
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
**Symbols:**

```
ffffffff81283cd0-ffffffff81283cec: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81292888)
Location: fs/block_dev.c:912
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
**Symbols:**

```
ffffffff812913d0-ffffffff812913ec: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b569a)
Location: fs/block_dev.c:902
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
Direct callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/md/dm.c:dm_grab_bdev_for_ioctl
```
**Symbols:**

```
ffffffff812b4120-ffffffff812b413c: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dd50c)
Location: fs/block_dev.c:903
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff812db740-ffffffff812db75c: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2aec)
Location: fs/block_dev.c:942
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff812f0d40-ffffffff812f0d5c: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81314534)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81312c40-ffffffff81312c5e: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326ea4)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81325b80-ffffffff81325b9e: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81361334)
Location: fs/block_dev.c:920
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_bszset
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff8135ef40-ffffffff8135ef60: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136dde1)
Location: fs/block_dev.c:936
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_part_iter_next
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_closing
```
**Symbols:**

```
ffffffff8136c720-ffffffff8136c74c: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813747eb)
Location: fs/block_dev.c:942
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/partitions/core.c:blk_drop_partitions
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81373050-ffffffff8137307c: bdgrab (STB_GLOBAL)
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
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1628)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffff8000103dfcf8-ffff8000103dfd28: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b9ad8)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c05b8740-c05b8768: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e759c)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
  - fs/block_dev.c:bd_acquire
  - fs/block_dev.c:bd_acquire
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c0000000004e5200-c0000000004e5248: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000298290)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffe000296bb0-ffffffe000296bdc: bdgrab (STB_GLOBAL)
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
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f484)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8131e160-ffffffff8131e17e: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81310024)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8130ed00-ffffffff8130ed1e: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131cf54)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8131bc30-ffffffff8131bc4e: bdgrab (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bdgrab(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132ec3f)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bd_start_claiming
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:swap_type_of
  - mm/swapfile.c:swap_type_of
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8132da10-ffffffff8132da2e: bdgrab (STB_GLOBAL)
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
