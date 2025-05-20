# Function: <code>blk_mq_alloc_tag_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c3da0)
Location: block/blk-mq.c:2260
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff813c3da0-ffffffff813c3fb2: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81408110)
Location: block/blk-mq.c:2314
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81408110-ffffffff8140833a: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814230e0)
Location: block/blk-mq.c:2346
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814230e0-ffffffff81423361: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81433130)
Location: block/blk-mq.c:2495
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81433130-ffffffff81433360: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145ece0)
Location: block/blk-mq.c:2659
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff8145ece0-ffffffff8145ef36: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2721
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81492ac7-ffffffff81492af8: blk_mq_alloc_tag_set.cold.66 (STB_LOCAL)
ffffffff81492630-ffffffff81492853: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2990
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814aca06-ffffffff814aca37: blk_mq_alloc_tag_set.cold.81 (STB_LOCAL)
ffffffff814ac3f0-ffffffff814ac6c0: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3023
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814dad17-ffffffff814dad48: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff814da600-ffffffff814da8d3: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3043
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814f40a4-ffffffff814f40d5: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff814f39c0-ffffffff814f3c93: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3265
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81554722-ffffffff8155473f: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff81554050-ffffffff8155428c: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3378
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_init_blk_queue
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81bf27f0-ffffffff81bf280d: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff81570710-ffffffff81570991: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3440
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_sq_queue
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_init_blk_queue
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81be47a0-ffffffff81be47d3: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff815785d0-ffffffff815788f7: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3472
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_sq_tag_set
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81cd85b8-ffffffff81cd85eb: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff815dd6b0-ffffffff815dda92: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:4235
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_sq_tag_set
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81e8bd3a-ffffffff81e8bd59: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff8168b420-ffffffff8168b71c: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81749440)
Location: block/blk-mq.c:4431
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_sq_tag_set
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81749440-ffffffff817497e5: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81785b80)
Location: block/blk-mq.c:4430
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_sq_tag_set
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81785b80-ffffffff81785f24: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c8200)
Location: block/blk-mq.c:4457
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_sq_tag_set
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff817c8200-ffffffff817c85d3: blk_mq_alloc_tag_set (STB_GLOBAL)
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
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f3218)
Location: block/blk-mq.c:3043
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105f3218-ffff8000105f3530: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079f324)
Location: block/blk-mq.c:3043
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c079f324-c079f680: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c00000000078a9b0)
Location: block/blk-mq.c:3043
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
c00000000078a9b0-c00000000078adc0: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000431982)
Location: block/blk-mq.c:3043
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe000431982-ffffffe000431b9e: blk_mq_alloc_tag_set (STB_GLOBAL)
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
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3043
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814ec684-ffffffff814ec6b5: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff814ebfa0-ffffffff814ec273: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3043
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814dcbd4-ffffffff814dcc05: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff814dc4f0-ffffffff814dc7c3: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3043
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff814e8714-ffffffff814e8745: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff814e8030-ffffffff814e8303: blk_mq_alloc_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int blk_mq_alloc_tag_set(struct blk_mq_tag_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3043
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff815016b4-ffffffff815016e5: blk_mq_alloc_tag_set.cold (STB_LOCAL)
ffffffff81500fd0-ffffffff815012a3: blk_mq_alloc_tag_set (STB_GLOBAL)
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
