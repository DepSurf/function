# Function: <code>blk_mq_kick_requeue_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c3190)
Location: block/blk-mq.c:519
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_queue_rq
  - drivers/block/xen-blkfront.c:blkif_recover
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/md/dm.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff813c3190-ffffffff813c31a7: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81406db0)
Location: block/blk-mq.c:575
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_queue_rq
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/md/dm-rq.c:dm_requeue_original_request
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81406db0-ffffffff81406dc7: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814211d0)
Location: block/blk-mq.c:590
Inline: True
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814211d0-ffffffff814211e9: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142fa90)
Location: block/blk-mq.c:677
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8142fa90-ffffffff8142faa9: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b030)
Location: block/blk-mq.c:732
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8145b030-ffffffff8145b049: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e000)
Location: block/blk-mq.c:747
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8148e000-ffffffff8148e01e: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a78a0)
Location: block/blk-mq.c:791
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814a78a0-ffffffff814a78be: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d58e0)
Location: block/blk-mq.c:790
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814d58e0-ffffffff814d58fe: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eec10)
Location: block/blk-mq.c:803
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814eec10-ffffffff814eec2e: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81551d7c)
Location: block/blk-mq.c:802
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_add_to_requeue_list
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8154e6d0-ffffffff8154e6ee: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156deac)
Location: block/blk-mq.c:852
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_add_to_requeue_list
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8156ab30-ffffffff8156ab4e: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8157598c)
Location: block/blk-mq.c:826
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_add_to_requeue_list
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81572a90-ffffffff81572aae: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d9eac)
Location: block/blk-mq.c:832
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_add_to_requeue_list
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff815d70c0-ffffffff815d70de: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816878fa)
Location: block/blk-mq.c:1382
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_add_to_requeue_list
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81682e50-ffffffff81682e7a: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745c6a)
Location: block/blk-mq.c:1510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_add_to_requeue_list
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81740510-ffffffff8174053a: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177f270)
Location: block/blk-mq.c:1503
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_requeue_request
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff8177c800-ffffffff8177c82a: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c1190)
Location: block/blk-mq.c:1506
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_requeue_request
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/scsi/scsi_error.c:scsi_eh_flush_done_q
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff817beb60-ffffffff817beb8a: blk_mq_kick_requeue_list (STB_GLOBAL)
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
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ed428)
Location: block/blk-mq.c:803
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffff8000105ed428-ffff8000105ed45c: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0799e2c)
Location: block/blk-mq.c:803
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
c0799e2c-c0799e58: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000786728)
Location: block/blk-mq.c:803
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_add_to_requeue_list
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
c000000000783910-c000000000783954: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042d1a6)
Location: block/blk-mq.c:803
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffe00042d1a6-ffffffe00042d1d6: blk_mq_kick_requeue_list (STB_GLOBAL)
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
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e71f0)
Location: block/blk-mq.c:803
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814e71f0-ffffffff814e720e: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7760)
Location: block/blk-mq.c:803
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814d7760-ffffffff814d777e: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3280)
Location: block/blk-mq.c:803
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814e3280-ffffffff814e329e: blk_mq_kick_requeue_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc120)
Location: block/blk-mq.c:803
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff814fc120-ffffffff814fc13e: blk_mq_kick_requeue_list (STB_GLOBAL)
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
