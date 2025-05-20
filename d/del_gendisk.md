# Function: <code>del_gendisk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813cb7e0)
Location: block/genhd.c:637
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/block/brd.c:brd_exit
  - drivers/block/loop.c:loop_remove
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_release_gendisk
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff813cb7e0-ffffffff813cba08: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140faa0)
Location: block/genhd.c:639
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_exit
  - drivers/block/loop.c:loop_remove
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8140faa0-ffffffff8140fcba: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8142ae30)
Location: block/genhd.c:639
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8142ae30-ffffffff8142b04c: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81439040)
Location: block/genhd.c:640
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81439040-ffffffff8143928d: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81465020)
Location: block/genhd.c:698
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81465020-ffffffff81465297: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81498960)
Location: block/genhd.c:727
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81498960-ffffffff81498c13: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b2ab0)
Location: block/genhd.c:749
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814b2ab0-ffffffff814b2d60: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:764
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814e1560-ffffffff814e1573: del_gendisk.cold (STB_LOCAL)
ffffffff814e0f70-ffffffff814e1235: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814fa3a0)
Location: block/genhd.c:773
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814fa3a0-ffffffff814fa687: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8155b350)
Location: block/genhd.c:880
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8155b350-ffffffff8155b658: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81577580)
Location: block/genhd.c:811
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81577580-ffffffff81577846: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157f370)
Location: block/genhd.c:600
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8157f370-ffffffff8157f58b: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e4440)
Location: block/genhd.c:581
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff815e4440-ffffffff815e46a8: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81692d70)
Location: block/genhd.c:596
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81692d70-ffffffff81693051: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81751b60)
Location: block/genhd.c:590
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_kobj_release
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81751b60-ffffffff81751ee1: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178df00)
Location: block/genhd.c:630
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_kobj_release
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8178df00-ffffffff8178e297: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817d0760)
Location: block/genhd.c:641
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_exit
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_kobj_release
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff817d0760-ffffffff817d0b18: del_gendisk (STB_GLOBAL)
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
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fbf78)
Location: block/genhd.c:773
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/mmc/core/block.c:mmc_blk_remove_req
```
**Symbols:**

```
ffff8000105fbf78-ffff8000105fc228: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a6fc8)
Location: block/genhd.c:773
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/mtd/mtd_blkdevs.c:del_mtd_blktrans_dev
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/mmc/core/block.c:mmc_blk_remove_req
```
**Symbols:**

```
c07a6fc8-c07a7284: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c0000000007953a0)
Location: block/genhd.c:773
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
c0000000007953a0-c000000000795744: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000437f4a)
Location: block/genhd.c:773
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/block.c:mmc_add_disk
  - drivers/mmc/core/block.c:mmc_blk_remove_req
```
**Symbols:**

```
ffffffe000437f4a-ffffffe0004381fa: del_gendisk (STB_GLOBAL)
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
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f2980)
Location: block/genhd.c:773
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814f2980-ffffffff814f2c67: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e2eb0)
Location: block/genhd.c:773
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_remove
  - drivers/nvdimm/pmem.c:pmem_release_disk
  - drivers/nvdimm/btt.c:nvdimm_namespace_detach_btt
  - drivers/nvdimm/blk.c:nd_blk_release_disk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814e2eb0-ffffffff814e3197: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814eea10)
Location: block/genhd.c:773
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814eea10-ffffffff814eecf7: del_gendisk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void del_gendisk(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81507ab0)
Location: block/genhd.c:773
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sr.c:sr_remove
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81507ab0-ffffffff81507da1: del_gendisk (STB_GLOBAL)
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
