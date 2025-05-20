# Function: <code>blk_mq_requeue_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c37b0)
Location: block/blk-mq.c:448
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_recover
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/md/dm.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff813c37b0-ffffffff813c37d9: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814074d0)
Location: block/blk-mq.c:504
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814074d0-ffffffff814074fc: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81421a70)
Location: block/blk-mq.c:525
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81421a70-ffffffff81421aa7: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430170)
Location: block/blk-mq.c:612
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81430170-ffffffff814301a7: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145c420)
Location: block/blk-mq.c:665
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8145c420-ffffffff8145c47b: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148f860)
Location: block/blk-mq.c:680
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8148f860-ffffffff8148f8bf: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a8cc0)
Location: block/blk-mq.c:716
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814a8cc0-ffffffff814a8d1f: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7820)
Location: block/blk-mq.c:716
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814d7820-ffffffff814d7880: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0ba0)
Location: block/blk-mq.c:729
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814f0ba0-ffffffff814f0c00: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81551da0)
Location: block/blk-mq.c:728
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81551da0-ffffffff81551e08: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156ded0)
Location: block/blk-mq.c:778
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8156ded0-ffffffff8156df38: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815759b0)
Location: block/blk-mq.c:752
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff815759b0-ffffffff81575a18: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d9ed0)
Location: block/blk-mq.c:759
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff815d9ed0-ffffffff815d9f27: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81687930)
Location: block/blk-mq.c:1309
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81687930-ffffffff81687996: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745cb0)
Location: block/blk-mq.c:1437
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81745cb0-ffffffff81745d16: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177f1d0)
Location: block/blk-mq.c:1445
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8177f1d0-ffffffff8177f29b: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c10f0)
Location: block/blk-mq.c:1448
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/virtio_blk.c:virtio_queue_rqs
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff817c10f0-ffffffff817c11bb: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105efff0)
Location: block/blk-mq.c:729
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
**Symbols:**

```
ffff8000105efff0-ffff8000105f0064: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079c160)
Location: block/blk-mq.c:729
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
**Symbols:**

```
c079c160-c079c1d0: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000786760)
Location: block/blk-mq.c:729
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
c000000000786760-c0000000007867fc: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042efc2)
Location: block/blk-mq.c:729
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
**Symbols:**

```
ffffffe00042efc2-ffffffe00042f01c: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9180)
Location: block/blk-mq.c:729
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/nvme/host/core.c:nvme_complete_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814e9180-ffffffff814e91e0: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d96f0)
Location: block/blk-mq.c:729
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/nvme/host/core.c:nvme_complete_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814d96f0-ffffffff814d9750: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5210)
Location: block/blk-mq.c:729
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814e5210-ffffffff814e5270: blk_mq_requeue_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_requeue_request(struct request *rq, bool kick_requeue_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fe170)
Location: block/blk-mq.c:729
Inline: True
Direct callers:
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814fe170-ffffffff814fe1d0: blk_mq_requeue_request (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool kick_requeue_list</code>
</li>
</ul>
</details>
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
