# Function: <code>blk_mq_sched_insert_requests</code>

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
void blk_mq_sched_insert_requests(struct request_queue *q, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81435cb0)
Location: block/blk-mq-sched.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff81435cb0-ffffffff81435d94: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct request_queue *q, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81461a30)
Location: block/blk-mq-sched.c:465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff81461a30-ffffffff81461aaf: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct request_queue *q, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81495390)
Location: block/blk-mq-sched.c:481
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff81495390-ffffffff81495402: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814af310)
Location: block/blk-mq-sched.c:411
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff814af310-ffffffff814af387: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dd590)
Location: block/blk-mq-sched.c:413
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff814dd590-ffffffff814dd684: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f6a20)
Location: block/blk-mq-sched.c:443
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff814f6a20-ffffffff814f6b14: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815574c0)
Location: block/blk-mq-sched.c:508
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff815574c0-ffffffff815575b4: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81573ae0)
Location: block/blk-mq-sched.c:470
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff81573ae0-ffffffff81573bca: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8157bb70)
Location: block/blk-mq-sched.c:472
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff8157bb70-ffffffff8157bc5a: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815e0f50)
Location: block/blk-mq-sched.c:482
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff815e0f50-ffffffff815e1035: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8168fb10)
Location: block/blk-mq-sched.c:461
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff8168fb10-ffffffff8168fc79: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8174e680)
Location: block/blk-mq-sched.c:460
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff8174e680-ffffffff8174e809: blk_mq_sched_insert_requests (STB_GLOBAL)
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f70c0)
Location: block/blk-mq-sched.c:443
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffff8000105f70c0-ffff8000105f7228: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a2810)
Location: block/blk-mq-sched.c:443
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
c07a2810-c07a296c: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078f630)
Location: block/blk-mq-sched.c:443
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
c00000000078f630-c00000000078f7f8: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe0004347c4)
Location: block/blk-mq-sched.c:443
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffe0004347c4-ffffffe0004348d6: blk_mq_sched_insert_requests (STB_GLOBAL)
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ef000)
Location: block/blk-mq-sched.c:443
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff814ef000-ffffffff814ef0f4: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814df540)
Location: block/blk-mq-sched.c:443
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff814df540-ffffffff814df634: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eb090)
Location: block/blk-mq-sched.c:443
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff814eb090-ffffffff814eb184: blk_mq_sched_insert_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, struct list_head *list, bool run_queue_async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81504060)
Location: block/blk-mq-sched.c:443
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_flush_plug_list
```
**Symbols:**

```
ffffffff81504060-ffffffff81504196: blk_mq_sched_insert_requests (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_hw_ctx *hctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
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
