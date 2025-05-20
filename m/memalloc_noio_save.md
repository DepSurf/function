# Function: <code>memalloc_noio_save</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815561dc)
Location: include/linux/sched.h:2134
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/usb/core/hub.c (ffffffff816070e7)
Location: include/linux/sched.h:2134
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff816aa0cd)
Location: include/linux/sched.h:2134
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a821c)
Location: include/linux/sched.h:2276
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/usb/core/hub.c (ffffffff81666e43)
Location: include/linux/sched.h:2276
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8170a4d1)
Location: include/linux/sched.h:2276
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d6d0c)
Location: include/linux/sched.h:2368
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/usb/core/hub.c (ffffffff81694b73)
Location: include/linux/sched.h:2368
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8173c3a1)
Location: include/linux/sched.h:2368
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815eb706)
Location: include/linux/sched/mm.h:170
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff8162e1fb)
Location: include/linux/sched/mm.h:170
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/usb/core/hub.c (ffffffff816a9fc6)
Location: include/linux/sched/mm.h:170
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81755c0d)
Location: include/linux/sched/mm.h:170
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81652af6)
Location: include/linux/sched/mm.h:179
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff816969bb)
Location: include/linux/sched/mm.h:179
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/usb/core/hub.c (ffffffff81715416)
Location: include/linux/sched/mm.h:179
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff817c7ebc)
Location: include/linux/sched/mm.h:179
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168f886)
Location: include/linux/sched/mm.h:188
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff816d2b71)
Location: include/linux/sched/mm.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/usb/core/hub.c (ffffffff81754221)
Location: include/linux/sched/mm.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8180fa69)
Location: include/linux/sched/mm.h:188
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816afc16)
Location: include/linux/sched/mm.h:188
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff816f42c1)
Location: include/linux/sched/mm.h:188
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/usb/core/hub.c (ffffffff8177867d)
Location: include/linux/sched/mm.h:188
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8183ba40)
Location: include/linux/sched/mm.h:188
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814fa43a)
Location: include/linux/sched/mm.h:221
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff816e9756)
Location: include/linux/sched/mm.h:221
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff8172d8ae)
Location: include/linux/sched/mm.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81760eba)
Location: include/linux/sched/mm.h:221
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff817b64df)
Location: include/linux/sched/mm.h:221
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81861ac6)
Location: include/linux/sched/mm.h:221
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8187f621)
Location: include/linux/sched/mm.h:221
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8151839a)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff8170d7b6)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff81751b4e)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81784e7a)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff817e6c08)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff818936f6)
Location: include/linux/sched/mm.h:223
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818b14ad)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81578fcf)
Location: include/linux/sched/mm.h:225
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff817c8db6)
Location: include/linux/sched/mm.h:225
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff817ecb39)
Location: include/linux/sched/mm.h:225
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff818103a4)
Location: include/linux/sched/mm.h:225
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/usb/core/hub.c (ffffffff818b6bbc)
Location: include/linux/sched/mm.h:225
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff819631a0)
Location: include/linux/sched/mm.h:225
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197b0c3)
Location: include/linux/sched/mm.h:225
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff819811a4)
Location: include/linux/sched/mm.h:225
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81595a87)
Location: include/linux/sched/mm.h:211
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff817c7af3)
Location: include/linux/sched/mm.h:211
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff817dd0a6)
Location: include/linux/sched/mm.h:211
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff81801469)
Location: include/linux/sched/mm.h:211
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff8181f2e4)
Location: include/linux/sched/mm.h:211
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff818599f4)
Location: include/linux/sched/mm.h:211
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff818c54cc)
Location: include/linux/sched/mm.h:211
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81969a50)
Location: include/linux/sched/mm.h:211
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197f8e3)
Location: include/linux/sched/mm.h:211
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff819857c4)
Location: include/linux/sched/mm.h:211
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159c823)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff817ab003)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff817c1456)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff817e5ec9)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff81802604)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c734)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff818a87ac)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff8194dd08)
Location: include/linux/sched/mm.h:215
Inline: True
```
```
In drivers/md/dm.c (ffffffff81963a63)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff81969105)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81604ed3)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff81834353)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff8184ac0a)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff81872269)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff8188cae4)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c9094)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff8193d68c)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff819f3108)
Location: include/linux/sched/mm.h:215
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81a0587b)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81a062e2)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
```
In drivers/md/dm.c (ffffffff81a0ba03)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff81a11325)
Location: include/linux/sched/mm.h:215
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
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
In mm/vmalloc.c (ffffffff81366dbb)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In block/blk-zoned.c (ffffffff816b86cc)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff81975e21)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff8199096a)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff819ba439)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff819d5fd2)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a16620)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff81a95390)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81b5ba04)
Location: include/linux/sched/mm.h:288
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81b6d56c)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81b6df80)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
```
In drivers/md/dm.c (ffffffff81b73ea8)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff81b79a37)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
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
In mm/vmalloc.c (ffffffff813e29cb)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In block/blk-zoned.c (ffffffff8177806d)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff81ae1ed1)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff81b00caa)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2f959)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff81b50bd2)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b97430)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff81c17a49)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81cf59c4)
Location: include/linux/sched/mm.h:288
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d098e5)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81d0a490)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
```
In drivers/md/dm.c (ffffffff81d10dfe)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17e4c)
Location: include/linux/sched/mm.h:288
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:copy_params
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
In mm/vmalloc.c (ffffffff814175a0)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In block/blk-zoned.c (ffffffff817b7fa6)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff81b2fe01)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff81b4ee5a)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff81b82da9)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff81ba4072)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed9f5)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff81c7ea45)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81d5d7ec)
Location: include/linux/sched/mm.h:320
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d72bb1)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81d735d0)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
```
In drivers/md/dm.c (ffffffff81d7a28e)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
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
In mm/vmalloc.c (ffffffff814440b0)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In block/blk-zoned.c (ffffffff817fc644)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff81b87601)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff81ba73da)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd6c99)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff81bf8262)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c4312c)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff81d33415)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81e0e4db)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_suspend
```
```
In drivers/md/dm-zone.c (ffffffff81e29ca1)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81e2a6e0)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
```
In drivers/md/dm.c (ffffffff81e3142e)
Location: include/linux/sched/mm.h:320
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff80001061fd4c)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffff8000108fccc4)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffff800010952274)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffff80001098b244)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/usb/core/hub.c (ffff800010a15afc)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffff800010aea040)
Location: include/linux/sched/mm.h:223
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffff800010b09480)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c7870)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (c09e7e68)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/scsi/sd_zbc.c (c0a5d4f0)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/usb/core/hub.c (c0aede40)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (c0bcc028)
Location: include/linux/sched/mm.h:223
Inline: True
```
```
In drivers/md/dm-ioctl.c (c0be7c6c)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bf350)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (c0000000009982a8)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (c0000000009ff07c)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (c000000000a4bdf4)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/usb/core/hub.c (c000000000ace08c)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (c000000000bd1218)
Location: include/linux/sched/mm.h:223
Inline: True
```
```
In drivers/md/dm-ioctl.c (c000000000bfafa0)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe0004524ba)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffe00058bc16)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffe0005c1dba)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005ef628)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/usb/core/hub.c (ffffffe00063ad34)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffe0006dd958)
Location: include/linux/sched/mm.h:223
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f79de)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8151097a)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff816d2f06)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff8170623e)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff8173956a)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff8179efe8)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81839576)
Location: include/linux/sched/mm.h:223
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8185732d)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81500c9a)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff816ae1f6)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff816d9cbe)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171b20a)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff81790c68)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81800be6)
Location: include/linux/sched/mm.h:223
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8181e93d)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150ca0a)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff81701476)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff8174500e)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779cfa)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff817dba88)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81888ba6)
Location: include/linux/sched/mm.h:223
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818a695d)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815260ea)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff8171b316)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff8176044e)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81793b2a)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff817f5d18)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff818a62d6)
Location: include/linux/sched/mm.h:223
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818c2b9d)
Location: include/linux/sched/mm.h:223
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
</ul>

## Differences
