# Function: <code>blk_mq_exit_hctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c391e)
Location: block/blk-mq.c:1628
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff81407640)
Location: block/blk-mq.c:1682
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81407640-ffffffff814076d9: blk_mq_exit_hctx.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff81421cf0)
Location: block/blk-mq.c:1710
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81421cf0-ffffffff81421db3: blk_mq_exit_hctx.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142fdf0)
Location: block/blk-mq.c:1877
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8142fdf0-ffffffff8142fec7: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145b730)
Location: block/blk-mq.c:2011
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8145b730-ffffffff8145b821: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148e1c0)
Location: block/blk-mq.c:2080
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8148e1c0-ffffffff8148e2ac: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff814a8400)
Location: block/blk-mq.c:2248
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_free_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814a8400-ffffffff814a84cf: blk_mq_exit_hctx.isra.69 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d73b0)
Location: block/blk-mq.c:2247
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814d73b0-ffffffff814d749c: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0730)
Location: block/blk-mq.c:2273
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814f0730-ffffffff814f081c: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550980)
Location: block/blk-mq.c:2462
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81550980-ffffffff81550a8a: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156d0c0)
Location: block/blk-mq.c:2563
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8156d0c0-ffffffff8156d1ca: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81574e00)
Location: block/blk-mq.c:2624
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81574e00-ffffffff81574f0a: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d96e0)
Location: block/blk-mq.c:2676
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff815d96e0-ffffffff815d986f: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684770)
Location: block/blk-mq.c:3431
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81684770-ffffffff8168493c: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81742400)
Location: block/blk-mq.c:3595
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff81742400-ffffffff817425cc: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177db10)
Location: block/blk-mq.c:3607
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff8177db10-ffffffff8177dcdd: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c0180)
Location: block/blk-mq.c:3623
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff817c0180-ffffffff817c034a: blk_mq_exit_hctx (STB_LOCAL)
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
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ee1e0)
Location: block/blk-mq.c:2273
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffff8000105ee1e0-ffff8000105ee2f8: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a334)
Location: block/blk-mq.c:2273
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
c079a334-c079a420: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000783ed0)
Location: block/blk-mq.c:2273
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
c000000000783ed0-c000000000784064: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042eb64)
Location: block/blk-mq.c:2273
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffe00042eb64-ffffffe00042ec4a: blk_mq_exit_hctx (STB_LOCAL)
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
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8d10)
Location: block/blk-mq.c:2273
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814e8d10-ffffffff814e8dfc: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9280)
Location: block/blk-mq.c:2273
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814d9280-ffffffff814d936c: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e4da0)
Location: block/blk-mq.c:2273
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814e4da0-ffffffff814e4e8c: blk_mq_exit_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_exit_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc4b0)
Location: block/blk-mq.c:2273
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
**Symbols:**

```
ffffffff814fc4b0-ffffffff814fc59a: blk_mq_exit_hctx (STB_LOCAL)
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
