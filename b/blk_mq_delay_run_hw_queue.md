# Function: <code>blk_mq_delay_run_hw_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814302c0)
Location: block/blk-mq.c:1171
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814302c0-ffffffff814302d8: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b2d0)
Location: block/blk-mq.c:1302
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8145b2d0-ffffffff8145b2e8: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81490eb6)
Location: block/blk-mq.c:1345
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff8148e6b0-ffffffff8148e6c8: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9dba)
Location: block/blk-mq.c:1469
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff814a8040-ffffffff814a8058: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7d68)
Location: block/blk-mq.c:1467
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff814d5f00-ffffffff814d5f18: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f10e3)
Location: block/blk-mq.c:1483
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff814ef230-ffffffff814ef248: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815501f0)
Location: block/blk-mq.c:1520
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff815501a0-ffffffff815501b8: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c6c0)
Location: block/blk-mq.c:1611
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff8156c670-ffffffff8156c688: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815740e1)
Location: block/blk-mq.c:1576
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff81574080-ffffffff81574098: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d85f1)
Location: block/blk-mq.c:1587
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff815d8590-ffffffff815d85a8: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684d66)
Location: block/blk-mq.c:2110
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81684ca0-ffffffff81684cc2: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81742846)
Location: block/blk-mq.c:2273
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - block/blk-mq-sched.c:blk_mq_do_dispatch_sched
```
**Symbols:**

```
ffffffff81742770-ffffffff81742792: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177ddd0)
Location: block/blk-mq.c:2218
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff8177ddd0-ffffffff8177dee9: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c0440)
Location: block/blk-mq.c:2236
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff817c0440-ffffffff817c0559: blk_mq_delay_run_hw_queue (STB_GLOBAL)
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f07d4)
Location: block/blk-mq.c:1483
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffff8000105eee08-ffff8000105eee40: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079c934)
Location: block/blk-mq.c:1483
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
c079a764-c079a788: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007872e0)
Location: block/blk-mq.c:1483
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
c000000000784420-c00000000078443c: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042f736)
Location: block/blk-mq.c:1483
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffe00042d7de-ffffffe00042d812: blk_mq_delay_run_hw_queue (STB_GLOBAL)
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e96c3)
Location: block/blk-mq.c:1483
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff814e7810-ffffffff814e7828: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9c33)
Location: block/blk-mq.c:1483
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff814d7d80-ffffffff814d7d98: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5753)
Location: block/blk-mq.c:1483
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff814e38a0-ffffffff814e38b8: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, long unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fe6b9)
Location: block/blk-mq.c:1483
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
**Symbols:**

```
ffffffff814fc9d0-ffffffff814fc9e8: blk_mq_delay_run_hw_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
