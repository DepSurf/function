# Function: <code>bdev_open_by_dev</code>

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
In <code>5.13</code>: Absent ⚠️
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
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bdev_handle *bdev_open_by_dev(dev_t dev, blk_mode_t mode, void *holder, const struct blk_holder_ops *hops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bdev.c (0)
Location: block/bdev.c:812
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_check
  - kernel/power/swap.c:swsusp_write
  - mm/swapfile.c:__do_sys_swapon
  - fs/super.c:setup_bdev_super
  - fs/super.c:setup_bdev_super
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - block/bdev.c:bdev_open_by_path
  - block/fops.c:blkdev_open
  - block/ioctl.c:blkdev_bszset
  - block/genhd.c:disk_scan_partitions
  - drivers/md/md.c:md_import_device
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff821d2b3a-ffffffff821d2b8b: bdev_open_by_dev.cold (STB_LOCAL)
ffffffff817a88b0-ffffffff817a8d3f: bdev_open_by_dev (STB_GLOBAL)
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
<b>Regular</b>
<ul>
</ul>
