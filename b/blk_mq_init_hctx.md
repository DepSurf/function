# Function: <code>blk_mq_init_hctx</code>

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
In block/blk-mq.c (ffffffff813c53ac)
Location: block/blk-mq.c:1672
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81407a0f)
Location: block/blk-mq.c:1726
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142263b)
Location: block/blk-mq.c:1757
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814322a3)
Location: block/blk-mq.c:1914
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145dd33)
Location: block/blk-mq.c:2049
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814916d7)
Location: block/blk-mq.c:2118
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ab162)
Location: block/blk-mq.c:2283
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d92dc)
Location: block/blk-mq.c:2295
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
In block/blk-mq.c (ffffffff814f269c)
Location: block/blk-mq.c:2321
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff8154e910)
Location: block/blk-mq.c:2510
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff8154e910-ffffffff8154ea37: blk_mq_init_hctx.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff8156adf0)
Location: block/blk-mq.c:2611
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff8156adf0-ffffffff8156af1a: blk_mq_init_hctx.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81577258)
Location: block/blk-mq.c:2672
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dbfb8)
Location: block/blk-mq.c:2728
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_init_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816835c0)
Location: block/blk-mq.c:3471
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff816835c0-ffffffff8168375a: blk_mq_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_init_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81740c50)
Location: block/blk-mq.c:3635
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff81740c50-ffffffff81740def: blk_mq_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_init_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177cf10)
Location: block/blk-mq.c:3647
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff8177cf10-ffffffff8177d0af: blk_mq_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_init_hctx(struct request_queue *q, struct blk_mq_tag_set *set, struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817bf2a0)
Location: block/blk-mq.c:3663
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_and_init_hctx
```
**Symbols:**

```
ffffffff817bf2a0-ffffffff817bf43f: blk_mq_init_hctx (STB_LOCAL)
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
In block/blk-mq.c (ffff8000105f1f3c)
Location: block/blk-mq.c:2321
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
In block/blk-mq.c (c079e024)
Location: block/blk-mq.c:2321
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
In block/blk-mq.c (c000000000788fc8)
Location: block/blk-mq.c:2321
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
In block/blk-mq.c (ffffffe0004308bc)
Location: block/blk-mq.c:2321
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
In block/blk-mq.c (ffffffff814eac7c)
Location: block/blk-mq.c:2321
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
In block/blk-mq.c (ffffffff814db1cc)
Location: block/blk-mq.c:2321
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
In block/blk-mq.c (ffffffff814e6d0c)
Location: block/blk-mq.c:2321
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
In block/blk-mq.c (ffffffff814ffcb0)
Location: block/blk-mq.c:2321
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
