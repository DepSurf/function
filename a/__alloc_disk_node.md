# Function: <code>__alloc_disk_node</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81464db0)
Location: block/genhd.c:1388
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81464db0-ffffffff81464ef6: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1409
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81498e64-ffffffff81498e80: __alloc_disk_node.cold.35 (STB_LOCAL)
ffffffff814986f0-ffffffff81498838: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1434
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff814b2fa6-ffffffff814b2fc2: __alloc_disk_node.cold.34 (STB_LOCAL)
ffffffff814b2840-ffffffff814b2988: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1455
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814e1544-ffffffff814e1560: __alloc_disk_node.cold (STB_LOCAL)
ffffffff814e0cd0-ffffffff814e0e2d: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1464
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814fa90b-ffffffff814fa927: __alloc_disk_node.cold (STB_LOCAL)
ffffffff814fa100-ffffffff814fa25d: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1676
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8155b8da-ffffffff8155b8f6: __alloc_disk_node.cold (STB_LOCAL)
ffffffff8155afc0-ffffffff8155b0f1: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1571
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81bf28fd-ffffffff81bf2919: __alloc_disk_node.cold (STB_LOCAL)
ffffffff81577250-ffffffff8157732b: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1277
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81be4897-ffffffff81be48b3: __alloc_disk_node.cold (STB_LOCAL)
ffffffff8157e880-ffffffff8157e99c: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct gendisk *__alloc_disk_node(struct request_queue *q, int node_id, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e3d90)
Location: block/genhd.c:1277
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/genhd.c:__blk_alloc_disk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff815e3d90-ffffffff815e3f41: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct gendisk *__alloc_disk_node(struct request_queue *q, int node_id, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81693060)
Location: block/genhd.c:1336
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/genhd.c:__blk_alloc_disk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
```
**Symbols:**

```
ffffffff81693060-ffffffff81693234: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct gendisk *__alloc_disk_node(struct request_queue *q, int node_id, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817527e0)
Location: block/genhd.c:1359
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_disk_for_queue
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/genhd.c:__blk_alloc_disk
```
**Symbols:**

```
ffffffff817527e0-ffffffff817529d0: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct gendisk *__alloc_disk_node(struct request_queue *q, int node_id, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178e9a0)
Location: block/genhd.c:1322
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_disk_for_queue
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/genhd.c:__blk_alloc_disk
```
**Symbols:**

```
ffffffff8178e9a0-ffffffff8178eb90: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gendisk *__alloc_disk_node(struct request_queue *q, int node_id, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817d1260)
Location: block/genhd.c:1335
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_disk_for_queue
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/genhd.c:__blk_alloc_disk
```
**Symbols:**

```
ffffffff817d1260-ffffffff817d147c: __alloc_disk_node (STB_GLOBAL)
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
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fbc60)
Location: block/genhd.c:1464
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
ffff8000105fbc60-ffff8000105fbdd0: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a6d1c)
Location: block/genhd.c:1464
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
c07a6d1c-c07a6e88: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000794fe0)
Location: block/genhd.c:1464
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
c000000000794fe0-c0000000007951b0: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000437ce0)
Location: block/genhd.c:1464
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
ffffffe000437ce0-ffffffe000437e3a: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1464
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814f2eeb-ffffffff814f2f07: __alloc_disk_node.cold (STB_LOCAL)
ffffffff814f26e0-ffffffff814f283d: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1464
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814e33ff-ffffffff814e341b: __alloc_disk_node.cold (STB_LOCAL)
ffffffff814e2c10-ffffffff814e2d6d: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1464
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff814eef7b-ffffffff814eef97: __alloc_disk_node.cold (STB_LOCAL)
ffffffff814ee770-ffffffff814ee8cd: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct gendisk *__alloc_disk_node(int minors, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/genhd.c (0)
Location: block/genhd.c:1464
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/sd.c:sd_probe
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sg.c:sg_add_device
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8150800d-ffffffff81508029: __alloc_disk_node.cold (STB_LOCAL)
ffffffff81507810-ffffffff8150796d: __alloc_disk_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param added. </b>
<code>struct lock_class_key *lkclass</code>
</li>
<li>
<b>Param removed. </b>
<code>int minors</code>
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
