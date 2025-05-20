# Function: <code>__blk_mq_delay_run_hw_queue</code>

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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430240)
Location: block/blk-mq.c:1146
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_request_bypass_insert
  - block/blk-mq.c:blk_mq_start_hw_queue
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_wake
```
**Symbols:**

```
ffffffff81430240-ffffffff814302c0: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b240)
Location: block/blk-mq.c:1277
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff8145b240-ffffffff8145b2c2: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e550)
Location: block/blk-mq.c:1324
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff8148e550-ffffffff8148e6ad: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7ee0)
Location: block/blk-mq.c:1448
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814a7ee0-ffffffff814a803a: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5da0)
Location: block/blk-mq.c:1446
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814d5da0-ffffffff814d5f00: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ef0d0)
Location: block/blk-mq.c:1462
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814ef0d0-ffffffff814ef230: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550040)
Location: block/blk-mq.c:1492
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff81550040-ffffffff81550197: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c510)
Location: block/blk-mq.c:1583
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff8156c510-ffffffff8156c667: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573f10)
Location: block/blk-mq.c:1548
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff81573f10-ffffffff81574077: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d8420)
Location: block/blk-mq.c:1559
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff815d8420-ffffffff815d8587: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684b10)
Location: block/blk-mq.c:2082
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff81684b10-ffffffff81684c93: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817425e0)
Location: block/blk-mq.c:2249
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff817425e0-ffffffff8174275f: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105eec28)
Location: block/blk-mq.c:1462
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffff8000105eec28-ffff8000105eee04: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a5d0)
Location: block/blk-mq.c:1462
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
c079a5d0-c079a764: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007841d0)
Location: block/blk-mq.c:1462
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
c0000000007841d0-c000000000784418: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042d66a)
Location: block/blk-mq.c:1462
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffe00042d66a-ffffffe00042d7de: __blk_mq_delay_run_hw_queue (STB_LOCAL)
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e76b0)
Location: block/blk-mq.c:1462
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814e76b0-ffffffff814e7810: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7c20)
Location: block/blk-mq.c:1462
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814d7c20-ffffffff814d7d80: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3740)
Location: block/blk-mq.c:1462
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814e3740-ffffffff814e38a0: __blk_mq_delay_run_hw_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx *hctx, bool async, long unsigned int msecs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc840)
Location: block/blk-mq.c:1462
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff814fc840-ffffffff814fc9cf: __blk_mq_delay_run_hw_queue (STB_LOCAL)
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
