# Function: <code>bdget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812479f0)
Location: fs/block_dev.c:627
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff812479f0-ffffffff81247b19: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812701c0)
Location: fs/block_dev.c:705
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff812701c0-ffffffff812702e9: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812833c0)
Location: fs/block_dev.c:957
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff812833c0-ffffffff812834d9: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81290a90)
Location: fs/block_dev.c:873
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:bd_acquire
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff81290a90-ffffffff81290ba9: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b3770)
Location: fs/block_dev.c:863
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:bd_acquire
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff812b3770-ffffffff812b3889: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dcb30)
Location: fs/block_dev.c:864
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff812dcb30-ffffffff812dcc54: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f27f0)
Location: fs/block_dev.c:903
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff812f27f0-ffffffff812f2915: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81314390)
Location: fs/block_dev.c:900
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff81314390-ffffffff813144c7: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326d00)
Location: fs/block_dev.c:900
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff81326d00-ffffffff81326e37: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360ea0)
Location: fs/block_dev.c:881
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:bd_acquire
  - block/genhd.c:bdget_disk
  - block/partitions/core.c:bdev_resize_partition
```
**Symbols:**

```
ffffffff81360ea0-ffffffff81360fd7: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136e8b1)
Location: fs/block_dev.c:919
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_no_open
  - fs/block_dev.c:blkdev_get_no_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813751a5)
Location: fs/block_dev.c:925
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get_no_open
  - fs/block_dev.c:blkdev_get_no_open
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1c18)
Location: fs/block_dev.c:900
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:bd_acquire
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffff8000103e1c18-ffff8000103e1d7c: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b7d44)
Location: fs/block_dev.c:900
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:bd_acquire
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
c05b7d44-c05b7e6c: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e4aa0)
Location: fs/block_dev.c:900
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - fs/block_dev.c:blkdev_get_by_dev
  - fs/block_dev.c:bd_acquire
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
c0000000004e4aa0-c0000000004e4c4c: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002980f2)
Location: fs/block_dev.c:900
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffe0002980f2-ffffffe00029823a: bdget (STB_GLOBAL)
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
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f2e0)
Location: fs/block_dev.c:900
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff8131f2e0-ffffffff8131f417: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130fe80)
Location: fs/block_dev.c:900
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff8130fe80-ffffffff8130ffb7: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131cdb0)
Location: fs/block_dev.c:900
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff8131cdb0-ffffffff8131cee7: bdget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct block_device *bdget(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132d190)
Location: fs/block_dev.c:900
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_store
  - kernel/trace/blktrace.c:sysfs_blk_trace_attr_show
  - mm/swapfile.c:swap_type_of
  - fs/block_dev.c:blkdev_get_by_dev
  - block/ioctl.c:blkpg_ioctl
  - block/ioctl.c:blkpg_ioctl
  - block/genhd.c:bdget_disk
```
**Symbols:**

```
ffffffff8132d190-ffffffff8132d2c5: bdget (STB_GLOBAL)
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
