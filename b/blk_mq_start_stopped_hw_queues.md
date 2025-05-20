# Function: <code>blk_mq_start_stopped_hw_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c5ae0)
Location: block/blk-mq.c:929
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/block/virtio_blk.c:virtblk_restore
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock
  - drivers/md/dm.c:start_queue
```
**Symbols:**

```
ffffffff813c5ae0-ffffffff813c5b47: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81409970)
Location: block/blk-mq.c:1007
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_restore
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81409970-ffffffff814099d7: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81424380)
Location: block/blk-mq.c:1076
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
  - drivers/scsi/scsi_lib.c:scsi_internal_device_unblock
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/md/dm-rq.c:dm_start_queue
```
**Symbols:**

```
ffffffff81424380-ffffffff814243e4: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430590)
Location: block/blk-mq.c:1282
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
```
**Symbols:**

```
ffffffff81430590-ffffffff814305f5: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145bac0)
Location: block/blk-mq.c:1417
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
```
**Symbols:**

```
ffffffff8145bac0-ffffffff8145bb25: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e9d0)
Location: block/blk-mq.c:1476
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
```
**Symbols:**

```
ffffffff8148e9d0-ffffffff8148ea23: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a83b0)
Location: block/blk-mq.c:1600
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
```
**Symbols:**

```
ffffffff814a83b0-ffffffff814a83fa: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6ef0)
Location: block/blk-mq.c:1598
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
```
**Symbols:**

```
ffffffff814d6ef0-ffffffff814d6f3c: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0270)
Location: block/blk-mq.c:1614
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
```
**Symbols:**

```
ffffffff814f0270-ffffffff814f02bc: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550440)
Location: block/blk-mq.c:1680
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_restart_queue
```
**Symbols:**

```
ffffffff81550440-ffffffff8155048f: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c860)
Location: block/blk-mq.c:1771
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_restart_queue
```
**Symbols:**

```
ffffffff8156c860-ffffffff8156c8af: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815744f0)
Location: block/blk-mq.c:1790
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_restart_queue
```
**Symbols:**

```
ffffffff815744f0-ffffffff8157453f: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d89a0)
Location: block/blk-mq.c:1801
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_restart_queue
```
**Symbols:**

```
ffffffff815d89a0-ffffffff815d89ef: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816852c0)
Location: block/blk-mq.c:2315
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_restart_queue
```
**Symbols:**

```
ffffffff816852c0-ffffffff81685372: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81742ad0)
Location: block/blk-mq.c:2458
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_restart_queue
```
**Symbols:**

```
ffffffff81742ad0-ffffffff81742b72: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177e2f0)
Location: block/blk-mq.c:2420
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_restart_queue
```
**Symbols:**

```
ffffffff8177e2f0-ffffffff8177e392: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c0970)
Location: block/blk-mq.c:2439
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_done
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:blkif_restart_queue
```
**Symbols:**

```
ffffffff817c0970-ffffffff817c0a26: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
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
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ef5c0)
Location: block/blk-mq.c:1614
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
```
**Symbols:**

```
ffff8000105ef5c0-ffff8000105ef648: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079bd70)
Location: block/blk-mq.c:1614
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
**Symbols:**

```
c079bd70-c079bddc: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007861c0)
Location: block/blk-mq.c:1614
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
**Symbols:**

```
c0000000007861c0-c000000000786278: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042e624)
Location: block/blk-mq.c:1614
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
**Symbols:**

```
ffffffe00042e624-ffffffe00042e692: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
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
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8850)
Location: block/blk-mq.c:1614
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
```
**Symbols:**

```
ffffffff814e8850-ffffffff814e889c: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8dc0)
Location: block/blk-mq.c:1614
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
```
**Symbols:**

```
ffffffff814d8dc0-ffffffff814d8e0c: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e48e0)
Location: block/blk-mq.c:1614
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
```
**Symbols:**

```
ffffffff814e48e0-ffffffff814e492c: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_start_stopped_hw_queues(struct request_queue *q, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fcdc0)
Location: block/blk-mq.c:1614
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_state_write
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkif_interrupt
  - drivers/block/xen-blkfront.c:kick_pending_request_queues
```
**Symbols:**

```
ffffffff814fcdc0-ffffffff814fce0c: blk_mq_start_stopped_hw_queues (STB_GLOBAL)
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
