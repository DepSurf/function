# Function: <code>blk_alloc_flush_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff813bdd00)
Location: block/blk-flush.c:503
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff813bdd00-ffffffff813bddd8: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81401c60)
Location: block/blk-flush.c:505
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81401c60-ffffffff81401d38: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8141b8d0)
Location: block/blk-flush.c:538
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8141b8d0-ffffffff8141b9a8: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814298f0)
Location: block/blk-flush.c:546
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814298f0-ffffffff814299a5: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81454ad0)
Location: block/blk-flush.c:563
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81454ad0-ffffffff81454b85: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81487f10)
Location: block/blk-flush.c:568
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81487f10-ffffffff81487fc5: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814a1ef0)
Location: block/blk-flush.c:465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814a1ef0-ffffffff814a1fc4: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814cffb0)
Location: block/blk-flush.c:464
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814cffb0-ffffffff814d0085: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814e9350)
Location: block/blk-flush.c:475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814e9350-ffffffff814e9425: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81548320)
Location: block/blk-flush.c:454
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
**Symbols:**

```
ffffffff81548320-ffffffff81548404: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81564060)
Location: block/blk-flush.c:455
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
**Symbols:**

```
ffffffff81564060-ffffffff81564144: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8156c7d0)
Location: block/blk-flush.c:449
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
**Symbols:**

```
ffffffff8156c7d0-ffffffff8156c8b4: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff815d0cb0)
Location: block/blk-flush.c:464
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
**Symbols:**

```
ffffffff815d0cb0-ffffffff815d0dda: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8167c570)
Location: block/blk-flush.c:468
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
**Symbols:**

```
ffffffff8167c570-ffffffff8167c68a: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81738e10)
Location: block/blk-flush.c:471
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
**Symbols:**

```
ffffffff81738e10-ffffffff81738f2b: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817754f0)
Location: block/blk-flush.c:480
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
**Symbols:**

```
ffffffff817754f0-ffffffff8177560b: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817b7790)
Location: block/blk-flush.c:478
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_hctx
```
**Symbols:**

```
ffffffff817b7790-ffffffff817b78ba: blk_alloc_flush_queue (STB_GLOBAL)
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
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffff8000105e73f8)
Location: block/blk-flush.c:475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffff8000105e73f8-ffff8000105e74cc: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (c0793fac)
Location: block/blk-flush.c:475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
c0793fac-c079405c: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (c00000000077bd90)
Location: block/blk-flush.c:475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
c00000000077bd90-c00000000077be84: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffe00042825a)
Location: block/blk-flush.c:475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffe00042825a-ffffffe0004282f8: blk_alloc_flush_queue (STB_GLOBAL)
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
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814e1930)
Location: block/blk-flush.c:475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814e1930-ffffffff814e1a05: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814d22c0)
Location: block/blk-flush.c:475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814d22c0-ffffffff814d2395: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814dd9c0)
Location: block/blk-flush.c:475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814dd9c0-ffffffff814dda95: blk_alloc_flush_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct blk_flush_queue *blk_alloc_flush_queue(struct request_queue *q, int node, int cmd_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff814f6820)
Location: block/blk-flush.c:475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814f6820-ffffffff814f68f5: blk_alloc_flush_queue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t flags</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, node, cmd_size, flags</code> ➡️ <code>node, cmd_size, flags</code>
</li>
</ul>
</details>
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
