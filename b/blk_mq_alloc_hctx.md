# Function: <code>blk_mq_alloc_hctx</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d94a1)
Location: block/blk-mq.c:2323
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f2861)
Location: block/blk-mq.c:2349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct blk_mq_hw_ctx *blk_mq_alloc_hctx(struct request_queue *q, struct blk_mq_tag_set *set, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81551630)
Location: block/blk-mq.c:2541
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff81551630-ffffffff8155187e: blk_mq_alloc_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct blk_mq_hw_ctx *blk_mq_alloc_hctx(struct request_queue *q, struct blk_mq_tag_set *set, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156d770)
Location: block/blk-mq.c:2642
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff8156d770-ffffffff8156d9ca: blk_mq_alloc_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct blk_mq_hw_ctx *blk_mq_alloc_hctx(struct request_queue *q, struct blk_mq_tag_set *set, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81574760)
Location: block/blk-mq.c:2703
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81574760-ffffffff815749cc: blk_mq_alloc_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct blk_mq_hw_ctx *blk_mq_alloc_hctx(struct request_queue *q, struct blk_mq_tag_set *set, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d8c80)
Location: block/blk-mq.c:2759
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff815d8c80-ffffffff815d8eec: blk_mq_alloc_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct blk_mq_hw_ctx *blk_mq_alloc_hctx(struct request_queue *q, struct blk_mq_tag_set *set, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81686710)
Location: block/blk-mq.c:3509
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff81686710-ffffffff81686927: blk_mq_alloc_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct blk_mq_hw_ctx *blk_mq_alloc_hctx(struct request_queue *q, struct blk_mq_tag_set *set, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81744fd0)
Location: block/blk-mq.c:3673
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff81744fd0-ffffffff817451e7: blk_mq_alloc_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct blk_mq_hw_ctx *blk_mq_alloc_hctx(struct request_queue *q, struct blk_mq_tag_set *set, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81780f40)
Location: block/blk-mq.c:3685
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff81780f40-ffffffff81781157: blk_mq_alloc_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct blk_mq_hw_ctx *blk_mq_alloc_hctx(struct request_queue *q, struct blk_mq_tag_set *set, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c3770)
Location: block/blk-mq.c:3701
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff817c3770-ffffffff817c39b9: blk_mq_alloc_hctx (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f20a4)
Location: block/blk-mq.c:2349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079e1f0)
Location: block/blk-mq.c:2349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007891d0)
Location: block/blk-mq.c:2349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe0004307f4)
Location: block/blk-mq.c:2349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eae41)
Location: block/blk-mq.c:2349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814db391)
Location: block/blk-mq.c:2349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6ed1)
Location: block/blk-mq.c:2349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ffe76)
Location: block/blk-mq.c:2349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
