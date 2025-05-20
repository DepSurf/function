# Function: <code>blk_cleanup_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b8bd0)
Location: block/blk-core.c:542
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/block/brd.c:brd_free
  - drivers/block/brd.c:brd_alloc
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_release_gendisk
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff813b8bd0-ffffffff813b8d16: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fc9c0)
Location: block/blk-core.c:544
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/block/brd.c:brd_free
  - drivers/block/brd.c:brd_alloc
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_remove
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff813fc9c0-ffffffff813fcb06: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81416360)
Location: block/blk-core.c:545
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-mq.c:blk_mq_init_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81416360-ffffffff814164a6: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81423a40)
Location: block/blk-core.c:623
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/hosts.c:scsi_host_dev_release
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81423a40-ffffffff81423b81: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144f1e0)
Location: block/blk-core.c:666
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff8144f1e0-ffffffff8144f313: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81482c80)
Location: block/blk-core.c:754
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue_node
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81482c80-ffffffff81482de4: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149e760)
Location: block/blk-core.c:329
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8149e760-ffffffff8149e82c: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb560)
Location: block/blk-core.c:334
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814cb560-ffffffff814cb62a: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4750)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814e4750-ffffffff814e481a: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815430d0)
Location: block/blk-core.c:356
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff815430d0-ffffffff81543198: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f920)
Location: block/blk-core.c:371
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff8155f920-ffffffff8155f9ed: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81568060)
Location: block/blk-core.c:372
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_exit_cb
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81568060-ffffffff8156812d: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cce30)
Location: block/blk-core.c:362
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:blk_mq_init_queue
  - block/genhd.c:blk_cleanup_disk
  - block/genhd.c:__blk_alloc_disk
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff815cce30-ffffffff815ccf11: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678510)
Location: block/blk-core.c:296
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:blk_mq_init_queue
  - block/genhd.c:blk_cleanup_disk
  - block/genhd.c:__blk_alloc_disk
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
```
**Symbols:**

```
ffffffff81678510-ffffffff816785cf: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0e78)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
```
**Symbols:**

```
ffff8000105e0e78-ffff8000105e0fb0: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e3a0)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/mtd/mtd_blkdevs.c:blktrans_dev_release
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
```
**Symbols:**

```
c078e3a0-c078e488: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774230)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
c000000000774230-c000000000774398: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe00042364c)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/mmc/core/queue.c:mmc_cleanup_queue
```
**Symbols:**

```
ffffffe00042364c-ffffffe00042373e: blk_cleanup_queue (STB_GLOBAL)
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
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dcd30)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/nvme/host/pci.c:nvme_dev_remove_admin
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814dcd30-ffffffff814dcdfa: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd6e0)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/nvdimm/pmem.c:pmem_release_queue
  - drivers/nvdimm/btt.c:nvdimm_namespace_detach_btt
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/multipath.c:nvme_mpath_remove_disk
  - drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk
  - drivers/nvme/host/pci.c:nvme_dev_remove_admin
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814cd6e0-ffffffff814cd7aa: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8dc0)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814d8dc0-ffffffff814d8e8a: blk_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_cleanup_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f19d0)
Location: block/blk-core.c:337
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_remove
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_sysfs.c:__scsi_remove_device
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff814f19d0-ffffffff814f1a9a: blk_cleanup_queue (STB_GLOBAL)
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
