# Function: <code>bdev_nonrot</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81382637)
Location: include/linux/blkdev.h:1300
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/ext4/mballoc.c (ffffffff814f9400)
Location: include/linux/blkdev.h:1300
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In block/ioctl.c (ffffffff81690968)
Location: include/linux/blkdev.h:1300
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff819b7c07)
Location: include/linux/blkdev.h:1300
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
```
```
In drivers/md/md.c (ffffffff81b6526f)
Location: include/linux/blkdev.h:1300
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm-table.c (ffffffff81b74765)
Location: include/linux/blkdev.h:1300
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rotational
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
In mm/swapfile.c (ffffffff813fc5a3)
Location: include/linux/blkdev.h:1248
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/ext4/mballoc.c (ffffffff81593bce)
Location: include/linux/blkdev.h:1248
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In block/ioctl.c (ffffffff8174f545)
Location: include/linux/blkdev.h:1248
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff81b2cf47)
Location: include/linux/blkdev.h:1248
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
```
```
In drivers/md/md.c (ffffffff81d00230)
Location: include/linux/blkdev.h:1248
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm-table.c (ffffffff81d11695)
Location: include/linux/blkdev.h:1248
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rotational
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
In mm/swapfile.c (ffffffff8142f8b0)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/ext4/mballoc.c (ffffffff815cabed)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In block/ioctl.c (ffffffff8178b745)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff81b7d172)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
```
```
In drivers/md/md.c (ffffffff81d63561)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm-table.c (ffffffff81d7aaf5)
Location: include/linux/blkdev.h:1229
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rotational
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
In mm/swapfile.c (ffffffff81469478)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
```
In fs/ext4/mballoc.c (ffffffff81603a12)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
```
In block/ioctl.c (ffffffff817cdea5)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
```
In drivers/block/loop.c (ffffffff81bd10fd)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_configure
```
```
In drivers/md/md.c (ffffffff81e1a332)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
```
In drivers/md/dm-table.c (ffffffff81e31c05)
Location: include/linux/blkdev.h:1214
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_is_rotational
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
