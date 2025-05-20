# Function: <code>blk_mq_insert_requests</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct request_queue *q, struct blk_mq_ctx *ctx, struct list_head *list, int depth, bool from_schedule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c5b50)
Location: block/blk-mq.c:1018
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff813c5b50-ffffffff813c5d04: blk_mq_insert_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct request_queue *q, struct blk_mq_ctx *ctx, struct list_head *list, int depth, bool from_schedule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814099e0)
Location: block/blk-mq.c:1091
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff814099e0-ffffffff81409b5e: blk_mq_insert_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct request_queue *q, struct blk_mq_ctx *ctx, struct list_head *list, int depth, bool from_schedule);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814243f0)
Location: block/blk-mq.c:1153
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff814243f0-ffffffff8142456e: blk_mq_insert_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81431d00)
Location: block/blk-mq.c:1376
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff81431d00-ffffffff81431df9: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145d830)
Location: block/blk-mq.c:1512
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff8145d830-ffffffff8145d92c: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81491050)
Location: block/blk-mq.c:1545
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff81491050-ffffffff81491165: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814aa310)
Location: block/blk-mq.c:1669
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814aa310-ffffffff814aa426: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8b10)
Location: block/blk-mq.c:1667
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814d8b10-ffffffff814d8c25: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f1ed0)
Location: block/blk-mq.c:1687
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814f1ed0-ffffffff814f1fe5: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815525e0)
Location: block/blk-mq.c:1757
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff815525e0-ffffffff815526f5: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156e770)
Location: block/blk-mq.c:1849
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff8156e770-ffffffff8156e855: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81576350)
Location: block/blk-mq.c:1868
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff81576350-ffffffff81576435: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815daf40)
Location: block/blk-mq.c:1879
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff815daf40-ffffffff815db03c: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81688e30)
Location: block/blk-mq.c:2393
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff81688e30-ffffffff81688f4d: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81747350)
Location: block/blk-mq.c:2536
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff81747350-ffffffff8174746d: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81782d70)
Location: block/blk-mq.c:2459
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_plug_list
```
**Symbols:**

```
ffffffff81782d70-ffffffff81782f2e: blk_mq_insert_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c50c0)
Location: block/blk-mq.c:2479
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_plug_list
```
**Symbols:**

```
ffffffff817c50c0-ffffffff817c52a9: blk_mq_insert_requests (STB_LOCAL)
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f1660)
Location: block/blk-mq.c:1687
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffff8000105f1660-ffff8000105f17f8: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079d708)
Location: block/blk-mq.c:1687
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
c079d708-c079d87c: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000788450)
Location: block/blk-mq.c:1687
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
c000000000788450-c00000000078860c: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe0004301ce)
Location: block/blk-mq.c:1687
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffe0004301ce-ffffffe000430320: blk_mq_insert_requests (STB_GLOBAL)
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ea4b0)
Location: block/blk-mq.c:1687
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814ea4b0-ffffffff814ea5c5: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814daa00)
Location: block/blk-mq.c:1687
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814daa00-ffffffff814dab15: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6540)
Location: block/blk-mq.c:1687
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814e6540-ffffffff814e6655: blk_mq_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ff510)
Location: block/blk-mq.c:1687
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814ff510-ffffffff814ff63b: blk_mq_insert_requests (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct blk_mq_hw_ctx *hctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>int depth</code>
</li>
<li>
<b>Param removed. </b>
<code>bool from_schedule</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool run_queue_async</code>
</li>
</ul>
</details>
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
