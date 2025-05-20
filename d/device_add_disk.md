# Function: <code>device_add_disk</code>

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
void device_add_disk(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140f280)
Location: block/genhd.c:585
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_init
  - drivers/block/brd.c:brd_probe
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8140f280-ffffffff8140f701: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8142a620)
Location: block/genhd.c:585
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8142a620-ffffffff8142aa9b: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814388c0)
Location: block/genhd.c:586
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff814388c0-ffffffff81438cb4: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81464850)
Location: block/genhd.c:641
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81464850-ffffffff81464c90: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81498590)
Location: block/genhd.c:715
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff81498590-ffffffff814985a5: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b26e0)
Location: block/genhd.c:735
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/sd.c:sd_probe_async
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814b26e0-ffffffff814b26f5: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e0b50)
Location: block/genhd.c:750
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814e0b50-ffffffff814e0b65: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f9f80)
Location: block/genhd.c:759
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814f9f80-ffffffff814f9f95: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155aca0)
Location: block/genhd.c:847
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8155aca0-ffffffff8155acb5: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81576fe0)
Location: block/genhd.c:766
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff81576fe0-ffffffff81576ff5: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157ef90)
Location: block/genhd.c:567
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff8157ef90-ffffffff8157efa5: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:393
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81cd88cd-ffffffff81cd88f1: device_add_disk.cold (STB_LOCAL)
ffffffff815e39d0-ffffffff815e3d81: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:410
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81e8c3df-ffffffff81e8c401: device_add_disk.cold (STB_LOCAL)
ffffffff81693470-ffffffff81693829: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81752130)
Location: block/genhd.c:390
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81752130-ffffffff817524f4: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178e2b0)
Location: block/genhd.c:396
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff8178e2b0-ffffffff8178e690: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817d0b30)
Location: block/genhd.c:396
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff817d0b30-ffffffff817d0f45: device_add_disk (STB_GLOBAL)
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
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fba50)
Location: block/genhd.c:759
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/mmc/core/block.c:mmc_add_disk
```
**Symbols:**

```
ffff8000105fba50-ffff8000105fba98: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a6b80)
Location: block/genhd.c:759
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/md/md.c:md_alloc
  - drivers/mmc/core/block.c:mmc_add_disk
```
**Symbols:**

```
c07a6b80-c07a6ba0: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000794dc0)
Location: block/genhd.c:759
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
c000000000794dc0-c000000000794dd8: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000437b1c)
Location: block/genhd.c:759
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
  - drivers/mmc/core/block.c:mmc_add_disk
```
**Symbols:**

```
ffffffe000437b1c-ffffffe000437b58: device_add_disk (STB_GLOBAL)
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
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f2560)
Location: block/genhd.c:759
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814f2560-ffffffff814f2575: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e2a90)
Location: block/genhd.c:759
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814e2a90-ffffffff814e2aa5: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ee5f0)
Location: block/genhd.c:759
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff814ee5f0-ffffffff814ee605: device_add_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void device_add_disk(struct device *parent, struct gendisk *disk, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81507690)
Location: block/genhd.c:759
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/md/md.c:md_alloc
```
**Symbols:**

```
ffffffff81507690-ffffffff815076a5: device_add_disk (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct attribute_group **groups</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
