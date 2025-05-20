# Function: <code>set_disk_ro</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff813c9cf0)
Location: block/genhd.c:1351
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:md_ioctl
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
```
**Symbols:**

```
ffffffff813c9cf0-ffffffff813c9dcd: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8140df60)
Location: block/genhd.c:1380
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
```
**Symbols:**

```
ffffffff8140df60-ffffffff8140e03d: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814292f0)
Location: block/genhd.c:1380
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
```
**Symbols:**

```
ffffffff814292f0-ffffffff814293cd: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81437620)
Location: block/genhd.c:1403
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
```
**Symbols:**

```
ffffffff81437620-ffffffff81437702: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81463400)
Location: block/genhd.c:1487
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
```
**Symbols:**

```
ffffffff81463400-ffffffff814634e2: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81496d20)
Location: block/genhd.c:1522
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
```
**Symbols:**

```
ffffffff81496d20-ffffffff81496e02: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b0c40)
Location: block/genhd.c:1547
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
```
**Symbols:**

```
ffffffff814b0c40-ffffffff814b0d22: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814df070)
Location: block/genhd.c:1568
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff814df070-ffffffff814df14f: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f84a0)
Location: block/genhd.c:1577
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff814f84a0-ffffffff814f857f: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81558d20)
Location: block/genhd.c:1790
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81558d20-ffffffff81558e02: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81576300)
Location: block/genhd.c:1640
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81576300-ffffffff815763e6: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, bool read_only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8157e190)
Location: block/genhd.c:1353
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8157e190-ffffffff8157e247: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, bool read_only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e3890)
Location: block/genhd.c:1400
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff815e3890-ffffffff815e3947: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, bool read_only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81692af0)
Location: block/genhd.c:1466
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81692af0-ffffffff81692bb3: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, bool read_only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81750f70)
Location: block/genhd.c:1476
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81750f70-ffffffff81751039: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, bool read_only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178d540)
Location: block/genhd.c:1439
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8178d540-ffffffff8178d60c: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, bool read_only);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817cfda0)
Location: block/genhd.c:1452
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_check_and_set_ro
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/scsi/sd.c:sd_read_write_protect_flag
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:do_resume
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff817cfda0-ffffffff817cfe6c: set_disk_ro (STB_GLOBAL)
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
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105f97e8)
Location: block/genhd.c:1577
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/mmc/core/block.c:force_ro_store
```
**Symbols:**

```
ffff8000105f97e8-ffff8000105f98c8: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a5808)
Location: block/genhd.c:1577
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/mmc/core/block.c:force_ro_store
```
**Symbols:**

```
c07a5808-c07a5900: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000792100)
Location: block/genhd.c:1577
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c000000000792100-c00000000079222c: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000435f0e)
Location: block/genhd.c:1577
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dm_early_create
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/mmc/core/block.c:force_ro_store
```
**Symbols:**

```
ffffffe000435f0e-ffffffe000435fc4: set_disk_ro (STB_GLOBAL)
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
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f0a80)
Location: block/genhd.c:1577
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff814f0a80-ffffffff814f0b5f: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e0fc0)
Location: block/genhd.c:1577
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/nvme/host/core.c:nvme_update_disk_info
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff814e0fc0-ffffffff814e109f: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ecb10)
Location: block/genhd.c:1577
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff814ecb10-ffffffff814ecbef: set_disk_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk *disk, int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81505b70)
Location: block/genhd.c:1577
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/nvdimm/bus.c:nvdimm_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:do_md_stop
  - drivers/md/md.c:md_set_readonly
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/md.c:array_state_store
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81505b70-ffffffff81505c59: set_disk_ro (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool read_only</code>
</li>
<li>
<b>Param removed. </b>
<code>int flag</code>
</li>
</ul>
</details>
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
