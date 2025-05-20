# Function: <code>blk_mq_start_hw_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c5a90)
Location: block/blk-mq.c:919
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_requeue_work
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff813c5a90-ffffffff813c5ad2: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8140a91e)
Location: block/blk-mq.c:997
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_requeue_work
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff81409920-ffffffff81409962: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814242f0)
Location: block/blk-mq.c:1056
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff814242f0-ffffffff81424332: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430380)
Location: block/blk-mq.c:1262
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff81430380-ffffffff814303c3: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b440)
Location: block/blk-mq.c:1397
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff8145b440-ffffffff8145b483: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e8a0)
Location: block/blk-mq.c:1456
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff8148e8a0-ffffffff8148e8e2: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a8220)
Location: block/blk-mq.c:1580
Inline: False
```
**Symbols:**

```
ffffffff814a8220-ffffffff814a8259: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6e70)
Location: block/blk-mq.c:1578
Inline: False
```
**Symbols:**

```
ffffffff814d6e70-ffffffff814d6ea9: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f01f0)
Location: block/blk-mq.c:1594
Inline: False
```
**Symbols:**

```
ffffffff814f01f0-ffffffff814f0229: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550490)
Location: block/blk-mq.c:1660
Inline: False
```
**Symbols:**

```
ffffffff81550490-ffffffff815504d0: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c8b0)
Location: block/blk-mq.c:1751
Inline: False
```
**Symbols:**

```
ffffffff8156c8b0-ffffffff8156c8f0: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81574540)
Location: block/blk-mq.c:1770
Inline: False
```
**Symbols:**

```
ffffffff81574540-ffffffff81574580: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d89f0)
Location: block/blk-mq.c:1781
Inline: False
```
**Symbols:**

```
ffffffff815d89f0-ffffffff815d8a30: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81685380)
Location: block/blk-mq.c:2295
Inline: False
```
**Symbols:**

```
ffffffff81685380-ffffffff8168541d: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81742c20)
Location: block/blk-mq.c:2438
Inline: False
```
**Symbols:**

```
ffffffff81742c20-ffffffff81742cbd: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177e440)
Location: block/blk-mq.c:2400
Inline: False
```
**Symbols:**

```
ffffffff8177e440-ffffffff8177e4dd: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c0ad0)
Location: block/blk-mq.c:2419
Inline: False
```
**Symbols:**

```
ffffffff817c0ad0-ffffffff817c0b79: blk_mq_start_hw_queues (STB_GLOBAL)
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
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ef1d8)
Location: block/blk-mq.c:1594
Inline: False
```
**Symbols:**

```
ffff8000105ef1d8-ffff8000105ef258: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079bab0)
Location: block/blk-mq.c:1594
Inline: False
```
**Symbols:**

```
c079bab0-c079bb0c: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000785da0)
Location: block/blk-mq.c:1594
Inline: False
```
**Symbols:**

```
c000000000785da0-c000000000785e38: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042e588)
Location: block/blk-mq.c:1594
Inline: False
```
**Symbols:**

```
ffffffe00042e588-ffffffe00042e5e2: blk_mq_start_hw_queues (STB_GLOBAL)
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
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e87d0)
Location: block/blk-mq.c:1594
Inline: False
```
**Symbols:**

```
ffffffff814e87d0-ffffffff814e8809: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8d40)
Location: block/blk-mq.c:1594
Inline: False
```
**Symbols:**

```
ffffffff814d8d40-ffffffff814d8d79: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e4860)
Location: block/blk-mq.c:1594
Inline: False
```
**Symbols:**

```
ffffffff814e4860-ffffffff814e4899: blk_mq_start_hw_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_start_hw_queues(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fccc0)
Location: block/blk-mq.c:1594
Inline: False
```
**Symbols:**

```
ffffffff814fccc0-ffffffff814fccf9: blk_mq_start_hw_queues (STB_GLOBAL)
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
