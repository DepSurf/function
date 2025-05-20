# Function: <code>bvec_virt</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff814c2060)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff814c72aa)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff814c7643)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff814c7936)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff814c7c63)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff814c7f38)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio-integrity.c (ffffffff816022e0)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In drivers/scsi/sd.c (ffffffff818c51e8)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/block.c (ffffffff8154cab8)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81552673)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81552a3d)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81552d71)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff815530be)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff81553401)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio-integrity.c (ffffffff816b4eba)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In drivers/scsi/sd.c (ffffffff81a11cab)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In fs/squashfs/block.c (ffffffff815ec958)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff815f3bde)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff815f4030)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff815f439d)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff815f4766)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff815f4b39)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio-integrity.c (ffffffff817749ba)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In drivers/scsi/sd.c (ffffffff81b91f6b)
Location: include/linux/bvec.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_init_command
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
In fs/squashfs/block.c (ffffffff816248d1)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8162bcce)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff8162c120)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff8162c492)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff8162c836)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8162cbcf)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio-integrity.c (ffffffff817b46d3)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
```
```
In drivers/block/virtio_blk.c (ffffffff81b802d6)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_complete_batch
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81be4f38)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
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
In fs/squashfs/block.c (ffffffff8165d961)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:squashfs_read_data
  - fs/squashfs/block.c:copy_bio_to_actor
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff8166509e)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_uncompress
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81665520)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_uncompress
```
```
In fs/squashfs/xz_wrapper.c (ffffffff816658c2)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_uncompress
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff81665cc6)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_uncompress
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8166608f)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In block/bio-integrity.c (ffffffff817f8513)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_process
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_free
  - block/bio-integrity.c:bio_integrity_free
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4116)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_complete_batch
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/virtio_blk.c:virtio_queue_rq
```
```
In drivers/scsi/sd.c (ffffffff81c3a098)
Location: include/linux/bvec.h:277
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_set_special_bvec
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
