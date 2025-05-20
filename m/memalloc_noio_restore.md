# Function: <code>memalloc_noio_restore</code>

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
In drivers/base/power/runtime.c (ffffffff815561ff)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/usb/core/hub.c (ffffffff816071f3)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff816aa113)
Location: include/linux/sched.h:2141
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
In drivers/base/power/runtime.c (ffffffff815a823f)
Location: include/linux/sched.h:2283
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/usb/core/hub.c (ffffffff81666f71)
Location: include/linux/sched.h:2283
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8170a513)
Location: include/linux/sched.h:2283
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
In drivers/base/power/runtime.c (ffffffff815d6d2f)
Location: include/linux/sched.h:2375
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/usb/core/hub.c (ffffffff81694ca1)
Location: include/linux/sched.h:2375
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8173c3e3)
Location: include/linux/sched.h:2375
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
In drivers/base/power/runtime.c (ffffffff815eb729)
Location: include/linux/sched/mm.h:177
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff8162e251)
Location: include/linux/sched/mm.h:177
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/usb/core/hub.c (ffffffff816aa140)
Location: include/linux/sched/mm.h:177
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81755c51)
Location: include/linux/sched/mm.h:177
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
In drivers/base/power/runtime.c (ffffffff81652b19)
Location: include/linux/sched/mm.h:186
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff81696a16)
Location: include/linux/sched/mm.h:186
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/usb/core/hub.c (ffffffff81715596)
Location: include/linux/sched/mm.h:186
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff817c7f00)
Location: include/linux/sched/mm.h:186
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
In drivers/base/power/runtime.c (ffffffff8168f8a9)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff816d2b76)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/usb/core/hub.c (ffffffff8175432e)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8180fa91)
Location: include/linux/sched/mm.h:203
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
In drivers/base/power/runtime.c (ffffffff816afc39)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff816f42c6)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/usb/core/hub.c (ffffffff8177878a)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8183ba68)
Location: include/linux/sched/mm.h:203
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
In block/blk-zoned.c (ffffffff814fa4be)
Location: include/linux/sched/mm.h:236
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff816e9777)
Location: include/linux/sched/mm.h:236
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff8172d8b3)
Location: include/linux/sched/mm.h:236
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff817610d4)
Location: include/linux/sched/mm.h:236
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff817b65e8)
Location: include/linux/sched/mm.h:236
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81861b07)
Location: include/linux/sched/mm.h:236
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8187f644)
Location: include/linux/sched/mm.h:236
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
In block/blk-zoned.c (ffffffff8151841e)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff8170d7d7)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff81751b53)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81785094)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff817e6d11)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81893737)
Location: include/linux/sched/mm.h:238
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818b14d0)
Location: include/linux/sched/mm.h:238
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
In block/blk-zoned.c (ffffffff8157900a)
Location: include/linux/sched/mm.h:240
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff817c8dd7)
Location: include/linux/sched/mm.h:240
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff817ecf53)
Location: include/linux/sched/mm.h:240
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff818103a9)
Location: include/linux/sched/mm.h:240
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/usb/core/hub.c (ffffffff818b6cc2)
Location: include/linux/sched/mm.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff819632a5)
Location: include/linux/sched/mm.h:240
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197b0ea)
Location: include/linux/sched/mm.h:240
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff819811bf)
Location: include/linux/sched/mm.h:240
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
In block/blk-zoned.c (ffffffff81595ac4)
Location: include/linux/sched/mm.h:226
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff817c7d60)
Location: include/linux/sched/mm.h:226
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff817dd0c7)
Location: include/linux/sched/mm.h:226
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff81801883)
Location: include/linux/sched/mm.h:226
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff8181f2e9)
Location: include/linux/sched/mm.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859a65)
Location: include/linux/sched/mm.h:226
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff818c55d2)
Location: include/linux/sched/mm.h:226
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81969b55)
Location: include/linux/sched/mm.h:226
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197f90b)
Location: include/linux/sched/mm.h:226
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff819857df)
Location: include/linux/sched/mm.h:226
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
In block/blk-zoned.c (ffffffff8159c85d)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff817ab270)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff817c1477)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff817e641d)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff81802609)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c7a5)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff818a88b2)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff8194d815)
Location: include/linux/sched/mm.h:230
Inline: True
```
```
In drivers/md/dm.c (ffffffff81963a88)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff81969119)
Location: include/linux/sched/mm.h:230
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
In block/blk-zoned.c (ffffffff81604f0d)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff818345d7)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff8184ac2b)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff818727c3)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff8188cae9)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c9105)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff8193d7a7)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff819f2c25)
Location: include/linux/sched/mm.h:230
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81a058b8)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81a0631a)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
```
In drivers/md/dm.c (ffffffff81a0ba28)
Location: include/linux/sched/mm.h:230
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff81a11339)
Location: include/linux/sched/mm.h:230
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
In mm/vmalloc.c (ffffffff81366cda)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In block/blk-zoned.c (ffffffff816b8706)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff8197608e)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff8199098b)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff819ba984)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff819d6003)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a1667f)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff81a954ab)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81b5b005)
Location: include/linux/sched/mm.h:303
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81b6d5b9)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81b6dfb8)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
```
In drivers/md/dm.c (ffffffff81b73ec0)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff81b79a73)
Location: include/linux/sched/mm.h:303
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
In mm/vmalloc.c (ffffffff813e2aed)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In block/blk-zoned.c (ffffffff817780a7)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff81ae213e)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff81b00ccb)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2fea4)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff81b50c03)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b9748f)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff81c17b68)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81cf4885)
Location: include/linux/sched/mm.h:303
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d09932)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81d0a4c8)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
```
In drivers/md/dm.c (ffffffff81d10e34)
Location: include/linux/sched/mm.h:303
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_kobject_uevent
```
```
In drivers/md/dm-ioctl.c (ffffffff81d17e88)
Location: include/linux/sched/mm.h:303
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
In mm/vmalloc.c (ffffffff81417742)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In block/blk-zoned.c (ffffffff817b7fe5)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff81b3002e)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff81b4ee7b)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff81b832dc)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff81ba40a3)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bedaa1)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff81c7eb64)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81d5c655)
Location: include/linux/sched/mm.h:335
Inline: True
```
```
In drivers/md/dm-zone.c (ffffffff81d72bfe)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81d73608)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
```
In drivers/md/dm.c (ffffffff81d7a2c7)
Location: include/linux/sched/mm.h:335
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
In mm/vmalloc.c (ffffffff81444252)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In block/blk-zoned.c (ffffffff817fc683)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/core.c (ffffffff81b8782e)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
```
In drivers/base/power/runtime.c (ffffffff81ba73fb)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd7203)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
```
```
In drivers/nvdimm/bus.c (ffffffff81bf8293)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c431cf)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/usb/core/hub.c (ffffffff81d33534)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81e10516)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/md/md.c:__mddev_resume
```
```
In drivers/md/dm-zone.c (ffffffff81e29cea)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_zone_map_bio_begin
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
```
```
In drivers/md/dm-ima.c (ffffffff81e2a718)
Location: include/linux/sched/mm.h:335
Inline: True
Inline callers:
  - drivers/md/dm-ima.c:dm_ima_measure_data
```
```
In drivers/md/dm.c (ffffffff81e31467)
Location: include/linux/sched/mm.h:335
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
In block/blk-zoned.c (ffff80001061fdb4)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffff8000108fccec)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffff800010952290)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffff80001098b458)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/usb/core/hub.c (ffff800010a15bdc)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffff800010aea074)
Location: include/linux/sched/mm.h:238
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffff800010b094b4)
Location: include/linux/sched/mm.h:238
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
In block/blk-zoned.c (c07c78f0)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (c09e7e90)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/scsi/sd_zbc.c (c0a5d768)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/usb/core/hub.c (c0aedf70)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (c0bcc074)
Location: include/linux/sched/mm.h:238
Inline: True
```
```
In drivers/md/dm-ioctl.c (c0be7ca4)
Location: include/linux/sched/mm.h:238
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
In block/blk-zoned.c (c0000000007bf3b8)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (c0000000009982c4)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (c0000000009ff0bc)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (c000000000a4bfdc)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/usb/core/hub.c (c000000000ace1ec)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (c000000000bd1250)
Location: include/linux/sched/mm.h:238
Inline: True
```
```
In drivers/md/dm-ioctl.c (c000000000bfafc8)
Location: include/linux/sched/mm.h:238
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
In block/blk-zoned.c (ffffffe00045250a)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffe00058bc38)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffe0005c1dfc)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffe0005ef890)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
```
```
In drivers/usb/core/hub.c (ffffffe00063ae2e)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffe0006dd990)
Location: include/linux/sched/mm.h:238
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f7a0a)
Location: include/linux/sched/mm.h:238
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
In block/blk-zoned.c (ffffffff815109fe)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff816d2f27)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff81706243)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81739784)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff8179f0f1)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff818395b7)
Location: include/linux/sched/mm.h:238
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81857350)
Location: include/linux/sched/mm.h:238
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
In block/blk-zoned.c (ffffffff81500d1e)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff816ae217)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff816d9cc3)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff8171b424)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff81790d71)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81800c27)
Location: include/linux/sched/mm.h:238
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8181e960)
Location: include/linux/sched/mm.h:238
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
In block/blk-zoned.c (ffffffff8150ca8e)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff81701497)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff81745013)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81779f14)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff817dbb91)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff81888be7)
Location: include/linux/sched/mm.h:238
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818a6980)
Location: include/linux/sched/mm.h:238
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
In block/blk-zoned.c (ffffffff8152616e)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/base/power/runtime.c (ffffffff8171b337)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_callback
```
```
In drivers/nvdimm/bus.c (ffffffff81760453)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
  - drivers/nvdimm/bus.c:nvdimm_clear_poison
```
```
In drivers/scsi/sd_zbc.c (ffffffff81793d44)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
```
In drivers/usb/core/hub.c (ffffffff817f5e21)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_device
```
```
In drivers/md/md.c (ffffffff818a6317)
Location: include/linux/sched/mm.h:238
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818c2bc0)
Location: include/linux/sched/mm.h:238
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
</ul>

## Differences
