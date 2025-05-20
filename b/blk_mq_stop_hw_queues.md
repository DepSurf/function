# Function: <code>blk_mq_stop_hw_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c31e0)
Location: block/blk-mq.c:901
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_freeze
  - drivers/block/xen-blkfront.c:xlvbd_release_gendisk
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff813c31e0-ffffffff813c3222: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81406e00)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_freeze
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
  - drivers/md/dm-rq.c:dm_stop_queue
```
**Symbols:**

```
ffffffff81406e00-ffffffff81406e42: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814212d5)
Location: block/blk-mq.c:1038
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free
  - drivers/scsi/scsi_lib.c:scsi_internal_device_block
```
**Symbols:**

```
ffffffff81421280-ffffffff814212c2: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142fbc0)
Location: block/blk-mq.c:1244
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff8142fbc0-ffffffff8142fc11: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b500)
Location: block/blk-mq.c:1379
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff8145b500-ffffffff8145b551: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e170)
Location: block/blk-mq.c:1438
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff8148e170-ffffffff8148e1c0: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7a10)
Location: block/blk-mq.c:1562
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff814a7a10-ffffffff814a7a57: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5a80)
Location: block/blk-mq.c:1560
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff814d5a80-ffffffff814d5ac7: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eedb0)
Location: block/blk-mq.c:1576
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff814eedb0-ffffffff814eedf7: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154f3a0)
Location: block/blk-mq.c:1642
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff8154f3a0-ffffffff8154f3e7: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156b350)
Location: block/blk-mq.c:1733
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff8156b350-ffffffff8156b397: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81572f80)
Location: block/blk-mq.c:1752
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff81572f80-ffffffff81572fc7: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d76d0)
Location: block/blk-mq.c:1763
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff815d76d0-ffffffff815d7717: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684390)
Location: block/blk-mq.c:2277
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff81684390-ffffffff81684434: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81741e50)
Location: block/blk-mq.c:2420
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff81741e50-ffffffff81741ef4: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177d6f0)
Location: block/blk-mq.c:2382
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff8177d6f0-ffffffff8177d794: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817bfa80)
Location: block/blk-mq.c:2401
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_remove
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:setup_blkring
```
**Symbols:**

```
ffffffff817bfa80-ffffffff817bfb24: blk_mq_stop_hw_queues (STB_GLOBAL)
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
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105edcb0)
Location: block/blk-mq.c:1576
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffff8000105edcb0-ffff8000105edd30: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a27c)
Location: block/blk-mq.c:1576
Inline: False
```
**Symbols:**

```
c079a27c-c079a2d4: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000783c80)
Location: block/blk-mq.c:1576
Inline: False
```
**Symbols:**

```
c000000000783c80-c000000000783d30: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042d3b6)
Location: block/blk-mq.c:1576
Inline: False
```
**Symbols:**

```
ffffffe00042d3b6-ffffffe00042d418: blk_mq_stop_hw_queues (STB_GLOBAL)
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
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7390)
Location: block/blk-mq.c:1576
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_freeze
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff814e7390-ffffffff814e73d7: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7900)
Location: block/blk-mq.c:1576
Inline: False
```
**Symbols:**

```
ffffffff814d7900-ffffffff814d7947: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3420)
Location: block/blk-mq.c:1576
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff814e3420-ffffffff814e3467: blk_mq_stop_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc310)
Location: block/blk-mq.c:1576
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_free
```
**Symbols:**

```
ffffffff814fc310-ffffffff814fc357: blk_mq_stop_hw_queues (STB_GLOBAL)
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
