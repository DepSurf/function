# Function: <code>blk_mq_stop_hw_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c31b0)
Location: block/blk-mq.c:893
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff813c31b0-ffffffff813c31da: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81406dd0)
Location: block/blk-mq.c:971
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff81406dd0-ffffffff81406dfa: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81421250)
Location: block/blk-mq.c:1030
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_quiesce_queue
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81421250-ffffffff8142127a: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142fc3f)
Location: block/blk-mq.c:1227
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8142fba0-ffffffff8142fbbe: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b582)
Location: block/blk-mq.c:1362
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8145b4e0-ffffffff8145b4fe: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e19b)
Location: block/blk-mq.c:1421
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8148e150-ffffffff8148e16e: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7a35)
Location: block/blk-mq.c:1545
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff814a79f0-ffffffff814a7a0e: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5aa5)
Location: block/blk-mq.c:1543
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff814d5a60-ffffffff814d5a7e: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eedd5)
Location: block/blk-mq.c:1559
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff814eed90-ffffffff814eedae: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154f3c5)
Location: block/blk-mq.c:1625
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8154f3f0-ffffffff8154f411: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156b375)
Location: block/blk-mq.c:1716
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8156b730-ffffffff8156b751: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81572fa5)
Location: block/blk-mq.c:1735
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81572fd0-ffffffff81572ff1: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d76f5)
Location: block/blk-mq.c:1746
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff815d7720-ffffffff815d7741: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816843db)
Location: block/blk-mq.c:2260
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81682f40-ffffffff81682f69: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81741e9b)
Location: block/blk-mq.c:2403
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81740740-ffffffff81740769: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177d73b)
Location: block/blk-mq.c:2365
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8177c9c0-ffffffff8177c9e9: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817bfacb)
Location: block/blk-mq.c:2384
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/virtio_blk.c:virtio_queue_rq
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff817bedc0-ffffffff817bede9: blk_mq_stop_hw_queue (STB_GLOBAL)
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105edce8)
Location: block/blk-mq.c:1559
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffff8000105edd30-ffff8000105edd84: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a2ac)
Location: block/blk-mq.c:1559
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
```
**Symbols:**

```
c079a24c-c079a27c: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000783cdc)
Location: block/blk-mq.c:1559
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
```
**Symbols:**

```
c000000000783c20-c000000000783c7c: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042d3da)
Location: block/blk-mq.c:1559
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
```
**Symbols:**

```
ffffffe00042d380-ffffffe00042d3b6: blk_mq_stop_hw_queue (STB_GLOBAL)
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
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e73b5)
Location: block/blk-mq.c:1559
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff814e7370-ffffffff814e738e: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7925)
Location: block/blk-mq.c:1559
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
```
**Symbols:**

```
ffffffff814d78e0-ffffffff814d78fe: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3445)
Location: block/blk-mq.c:1559
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff814e3400-ffffffff814e341e: blk_mq_stop_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_stop_hw_queue(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc335)
Location: block/blk-mq.c:1559
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_stop_hw_queues
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff814fc2f0-ffffffff814fc30e: blk_mq_stop_hw_queue (STB_GLOBAL)
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
