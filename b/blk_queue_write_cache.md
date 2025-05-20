# Function: <code>blk_queue_write_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81402b10)
Location: block/blk-settings.c:842
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/virtio_blk.c:virtblk_update_cache_mode
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81402b10-ffffffff81402b7f: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141c6c0)
Location: block/blk-settings.c:879
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8141c6c0-ffffffff8141c746: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8142a620)
Location: block/blk-settings.c:891
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8142a620-ffffffff8142a6a7: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81455970)
Location: block/blk-settings.c:892
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81455970-ffffffff814559f7: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488c00)
Location: block/blk-settings.c:890
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81488c00-ffffffff81488c88: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a2b20)
Location: block/blk-settings.c:832
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814a2b20-ffffffff814a2b87: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d0bd0)
Location: block/blk-settings.c:820
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814d0bd0-ffffffff814d0c35: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e9f50)
Location: block/blk-settings.c:821
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814e9f50-ffffffff814e9fb5: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81548e00)
Location: block/blk-settings.c:782
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81548e00-ffffffff81548e65: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81564d70)
Location: block/blk-settings.c:795
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81564d70-ffffffff81564dd5: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156d3c0)
Location: block/blk-settings.c:792
Inline: False
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8156d3c0-ffffffff8156d425: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d1860)
Location: block/blk-settings.c:792
Inline: False
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff815d1860-ffffffff815d18c5: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167ce00)
Location: block/blk-settings.c:824
Inline: False
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8167ce00-ffffffff8167ce71: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81739880)
Location: block/blk-settings.c:825
Inline: False
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81739880-ffffffff817398f1: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775f50)
Location: block/blk-settings.c:831
Inline: False
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:cache_type_store
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81775f50-ffffffff81775fde: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b82c0)
Location: block/blk-settings.c:833
Inline: True
Direct callers:
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:cache_type_store
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:cache_type_store
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff817b82c0-ffffffff817b8345: blk_queue_write_cache (STB_GLOBAL)
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
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e8288)
Location: block/blk-settings.c:821
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
ffff8000105e8288-ffff8000105e8320: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c0794788)
Location: block/blk-settings.c:821
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
c0794788-c07947fc: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077ce70)
Location: block/blk-settings.c:821
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
c00000000077ce70-c00000000077cf4c: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe000428f40)
Location: block/blk-settings.c:821
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
ffffffe000428f40-ffffffe000428fb6: blk_queue_write_cache (STB_GLOBAL)
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
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e2530)
Location: block/blk-settings.c:821
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/nvme/host/core.c:nvme_set_queue_limits
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814e2530-ffffffff814e2595: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d2ec0)
Location: block/blk-settings.c:821
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/nvme/host/core.c:nvme_set_queue_limits
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814d2ec0-ffffffff814d2f25: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814de5c0)
Location: block/blk-settings.c:821
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814de5c0-ffffffff814de625: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue *q, bool wc, bool fua);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814f7420)
Location: block/blk-settings.c:821
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/xen-blkfront.c:xlvbd_flush
  - drivers/scsi/sd.c:sd_set_flush_flag
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff814f7420-ffffffff814f7485: blk_queue_write_cache (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
