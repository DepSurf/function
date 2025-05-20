# Function: <code>bdev_nr_bytes</code>

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
In fs/buffer.c (ffffffff814446b1)
Location: include/linux/blkdev.h:797
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/squashfs/super.c (ffffffff81550442)
Location: include/linux/blkdev.h:797
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/fops.c (ffffffff8166ff3e)
Location: include/linux/blkdev.h:797
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
```
```
In block/ioctl.c (ffffffff8169131b)
Location: include/linux/blkdev.h:797
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/partitions/efi.c (ffffffff8169e07b)
Location: include/linux/blkdev.h:797
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In drivers/md/md.c (ffffffff81b5db44)
Location: include/linux/blkdev.h:797
Inline: True
Inline callers:
  - drivers/md/md.c:md_import_device
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
In fs/buffer.c (ffffffff814d3934)
Location: include/linux/blkdev.h:785
Inline: True
Inline callers:
  - fs/buffer.c:init_page_buffers
```
```
In fs/squashfs/super.c (ffffffff815f107c)
Location: include/linux/blkdev.h:785
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/fops.c (ffffffff8172b49e)
Location: include/linux/blkdev.h:785
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
```
```
In block/ioctl.c (ffffffff8174ff50)
Location: include/linux/blkdev.h:785
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/partitions/efi.c (ffffffff8175cabb)
Location: include/linux/blkdev.h:785
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In drivers/md/md.c (ffffffff81cf7aca)
Location: include/linux/blkdev.h:785
Inline: True
Inline callers:
  - drivers/md/md.c:md_import_device
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
In fs/buffer.c (ffffffff81508a0d)
Location: include/linux/blkdev.h:769
Inline: True
Inline callers:
  - fs/buffer.c:folio_init_buffers
```
```
In fs/squashfs/super.c (ffffffff816290e1)
Location: include/linux/blkdev.h:769
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/fops.c (ffffffff817687fb)
Location: include/linux/blkdev.h:769
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
```
```
In block/ioctl.c (ffffffff8178c19c)
Location: include/linux/blkdev.h:769
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/partitions/efi.c (ffffffff8179b356)
Location: include/linux/blkdev.h:769
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In drivers/md/md.c (ffffffff81d5f3d3)
Location: include/linux/blkdev.h:769
Inline: True
Inline callers:
  - drivers/md/md.c:md_import_device
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
In fs/buffer.c (ffffffff8153d876)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - fs/buffer.c:folio_init_buffers
```
```
In fs/squashfs/super.c (ffffffff81662330)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/fops.c (ffffffff817aa69e)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - block/fops.c:blkdev_fallocate
  - block/fops.c:blkdev_read_iter
  - block/fops.c:blkdev_write_iter
```
```
In block/ioctl.c (ffffffff817ce93c)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
  - block/ioctl.c:blkdev_common_ioctl
```
```
In block/partitions/efi.c (ffffffff817dedb6)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - block/partitions/efi.c:efi_partition
  - block/partitions/efi.c:is_gpt_valid
  - block/partitions/efi.c:read_lba
```
```
In drivers/md/md.c (ffffffff81e16775)
Location: include/linux/blkdev.h:747
Inline: True
Inline callers:
  - drivers/md/md.c:md_import_device
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
