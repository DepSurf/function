# Function: <code>blk_mq_end_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c3fc0)
Location: block/blk-mq.c:318
Inline: True
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_insert_flush
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_make_request
  - drivers/block/virtio_blk.c:virtblk_request_done
  - drivers/md/dm.c:dm_softirq_done
  - drivers/md/dm.c:dm_softirq_done
```
**Symbols:**

```
ffffffff813c3fc0-ffffffff813c4021: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814076e0)
Location: block/blk-mq.c:374
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - drivers/block/virtio_blk.c:virtblk_request_done
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
```
**Symbols:**

```
ffffffff814076e0-ffffffff81407741: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, int error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814222a0)
Location: block/blk-mq.c:371
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
```
**Symbols:**

```
ffffffff814222a0-ffffffff81422317: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430980)
Location: block/blk-mq.c:472
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff81430980-ffffffff814309fb: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145bfa0)
Location: block/blk-mq.c:514
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff8145bfa0-ffffffff8145c021: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148fa10)
Location: block/blk-mq.c:542
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff8148fa10-ffffffff8148faed: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9250)
Location: block/blk-mq.c:560
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_teardown_job
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff814a9250-ffffffff814a937f: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6f40)
Location: block/blk-mq.c:555
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_teardown_job
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff814d6f40-ffffffff814d706b: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f02c0)
Location: block/blk-mq.c:566
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_teardown_job
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff814f02c0-ffffffff814f03ed: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81552a59)
Location: block/blk-mq.c:569
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_list_directly
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_complete
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff8154f9c0-ffffffff8154faef: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156eb0c)
Location: block/blk-mq.c:562
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_list_directly
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_complete
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff8156bed0-ffffffff8156c002: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815766ec)
Location: block/blk-mq.c:563
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_list_directly
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_complete
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff81574580-ffffffff815746b2: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815db33c)
Location: block/blk-mq.c:570
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_complete
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff815d8a30-ffffffff815d8b62: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816894ca)
Location: block/blk-mq.c:942
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_complete
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff81687220-ffffffff8168737a: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81747a99)
Location: block/blk-mq.c:1052
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/bsg-lib.c:bsg_complete
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff81744f80-ffffffff81744fc0: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81780e10)
Location: block/blk-mq.c:1048
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_plug_issue_direct
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_complete
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff81780e10-ffffffff81780f27: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c33d0)
Location: block/blk-mq.c:1058
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_plug_issue_direct
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_complete
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff817c33d0-ffffffff817c3525: blk_mq_end_request (STB_GLOBAL)
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
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ee6f0)
Location: block/blk-mq.c:566
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_job_put
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
**Symbols:**

```
ffff8000105ee6f0-ffff8000105ee834: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079bddc)
Location: block/blk-mq.c:566
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_job_put
  - drivers/block/loop.c:lo_complete_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
**Symbols:**

```
c079bddc-c079bf2c: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000786280)
Location: block/blk-mq.c:566
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_job_put
  - drivers/block/loop.c:lo_complete_rq
```
**Symbols:**

```
c000000000786280-c00000000078643c: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042e692)
Location: block/blk-mq.c:566
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_teardown_job
  - drivers/block/loop.c:lo_complete_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
```
**Symbols:**

```
ffffffe00042e692-ffffffe00042e78c: blk_mq_end_request (STB_GLOBAL)
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
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e88a0)
Location: block/blk-mq.c:566
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_teardown_job
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
  - drivers/nvme/host/core.c:nvme_complete_rq
  - drivers/nvme/host/multipath.c:nvme_failover_req
```
**Symbols:**

```
ffffffff814e88a0-ffffffff814e89cd: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8e10)
Location: block/blk-mq.c:566
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_teardown_job
  - drivers/block/loop.c:lo_complete_rq
  - drivers/scsi/scsi_transport_fc.c:fc_bsg_job_timeout
  - drivers/nvme/host/core.c:nvme_complete_rq
  - drivers/nvme/host/multipath.c:nvme_failover_req
```
**Symbols:**

```
ffffffff814d8e10-ffffffff814d8f3d: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e4930)
Location: block/blk-mq.c:566
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_teardown_job
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff814e4930-ffffffff814e4a5d: blk_mq_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_end_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fde30)
Location: block/blk-mq.c:566
Inline: True
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/bsg-lib.c:bsg_teardown_job
  - drivers/block/loop.c:lo_complete_rq
  - drivers/block/xen-blkfront.c:blkfront_resume
  - drivers/block/xen-blkfront.c:blkif_complete_rq
```
**Symbols:**

```
ffffffff814fde30-ffffffff814fdf5d: blk_mq_end_request (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
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
