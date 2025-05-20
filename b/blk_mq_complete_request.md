# Function: <code>blk_mq_complete_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_complete_request(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c4200)
Location: block/blk-mq.c:377
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
```
**Symbols:**

```
ffffffff813c4200-ffffffff813c421f: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_complete_request(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81407920)
Location: block/blk-mq.c:433
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:dm_complete_request
```
**Symbols:**

```
ffffffff81407920-ffffffff8140793f: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_complete_request(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81422550)
Location: block/blk-mq.c:447
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:dm_complete_request
```
**Symbols:**

```
ffffffff81422550-ffffffff8142256f: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142f920)
Location: block/blk-mq.c:528
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:dm_complete_request
```
**Symbols:**

```
ffffffff8142f920-ffffffff8142f93a: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145aea0)
Location: block/blk-mq.c:570
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:dm_complete_request
```
**Symbols:**

```
ffffffff8145aea0-ffffffff8145aeba: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148dde0)
Location: block/blk-mq.c:616
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:dm_complete_request
```
**Symbols:**

```
ffffffff8148dde0-ffffffff8148dee7: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7670)
Location: block/blk-mq.c:651
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff814a7670-ffffffff814a7771: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d56e0)
Location: block/blk-mq.c:646
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff814d56e0-ffffffff814d57e0: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee9c0)
Location: block/blk-mq.c:657
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff814ee9c0-ffffffff814eeac0: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550780)
Location: block/blk-mq.c:671
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff81550780-ffffffff81550795: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c2f0)
Location: block/blk-mq.c:703
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff8156c2f0-ffffffff8156c321: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573ed0)
Location: block/blk-mq.c:677
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff81573ed0-ffffffff81573f01: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d83e0)
Location: block/blk-mq.c:684
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:lo_rw_aio_complete
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff815d83e0-ffffffff815d8411: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81685be0)
Location: block/blk-mq.c:1115
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_process_work
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff81685be0-ffffffff81685c17: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81743a10)
Location: block/blk-mq.c:1234
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_process_work
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff81743a10-ffffffff81743a47: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177f700)
Location: block/blk-mq.c:1233
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_process_work
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff8177f700-ffffffff8177f737: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c21e0)
Location: block/blk-mq.c:1234
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_process_work
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_done_internal
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff817c21e0-ffffffff817c2217: blk_mq_complete_request (STB_GLOBAL)
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
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ede28)
Location: block/blk-mq.c:657
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_req_done
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
```
**Symbols:**

```
ffff8000105ede28-ffff8000105edf70: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0799b6c)
Location: block/blk-mq.c:657
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_req_done
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
```
**Symbols:**

```
c0799b6c-c0799ca8: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000783590)
Location: block/blk-mq.c:657
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
c000000000783590-c00000000078374c: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042cf8c)
Location: block/blk-mq.c:657
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_req_done
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
```
**Symbols:**

```
ffffffe00042cf8c-ffffffe00042d082: blk_mq_complete_request (STB_GLOBAL)
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
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6fa0)
Location: block/blk-mq.c:657
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/nvme/host/core.c:nvme_cancel_request
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_poll
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/nvme/host/pci.c:nvme_irq
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff814e6fa0-ffffffff814e70a0: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7510)
Location: block/blk-mq.c:657
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/nvme/host/core.c:nvme_cancel_request
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_poll
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/nvme/host/pci.c:nvme_irq
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff814d7510-ffffffff814d7610: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3030)
Location: block/blk-mq.c:657
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff814e3030-ffffffff814e3130: blk_mq_complete_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fbeb0)
Location: block/blk-mq.c:657
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_job_done
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:lo_rw_aio_do_completion
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/scsi/scsi_lib.c:scsi_mq_done
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff814fbeb0-ffffffff814fbfb9: blk_mq_complete_request (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int error</code>
</li>
</ul>
</details>
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
