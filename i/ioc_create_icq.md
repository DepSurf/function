# Function: <code>ioc_create_icq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff813bf210)
Location: block/blk-ioc.c:357
Inline: False
Direct callers:
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff813bf210-ffffffff813bf38d: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81403160)
Location: block/blk-ioc.c:357
Inline: False
Direct callers:
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff81403160-ffffffff814032e3: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8141ce90)
Location: block/blk-ioc.c:357
Inline: False
Direct callers:
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff8141ce90-ffffffff8141d013: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8142aef0)
Location: block/blk-ioc.c:388
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff8142aef0-ffffffff8142b08b: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814560e0)
Location: block/blk-ioc.c:389
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814560e0-ffffffff8145627e: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:389
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814896b6-ffffffff814896c7: ioc_create_icq.cold.14 (STB_LOCAL)
ffffffff81489520-ffffffff814896b6: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814a34f1-ffffffff814a3502: ioc_create_icq.cold.13 (STB_LOCAL)
ffffffff814a3370-ffffffff814a34f1: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814d15ca-ffffffff814d15db: ioc_create_icq.cold (STB_LOCAL)
ffffffff814d1440-ffffffff814d15ca: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814ea974-ffffffff814ea985: ioc_create_icq.cold (STB_LOCAL)
ffffffff814ea7f0-ffffffff814ea974: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:372
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff81549914-ffffffff81549925: ioc_create_icq.cold (STB_LOCAL)
ffffffff81549790-ffffffff81549914: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:372
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff81bf2777-ffffffff81bf2788: ioc_create_icq.cold (STB_LOCAL)
ffffffff815655c0-ffffffff81565744: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:372
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff81be473e-ffffffff81be474f: ioc_create_icq.cold (STB_LOCAL)
ffffffff8156dc30-ffffffff8156ddb4: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:372
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff81cd81f9-ffffffff81cd820a: ioc_create_icq.cold (STB_LOCAL)
ffffffff815d2220-ffffffff815d23a4: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:367
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
```
**Symbols:**

```
ffffffff8167d930-ffffffff8167dac7: ioc_create_icq (STB_LOCAL)
ffffffff81e8b5bf-ffffffff81e8b5d0: ioc_create_icq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8173a540)
Location: block/blk-ioc.c:367
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
```
**Symbols:**

```
ffffffff8173a540-ffffffff8173a6e0: ioc_create_icq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81776c40)
Location: block/blk-ioc.c:363
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
```
**Symbols:**

```
ffffffff81776c40-ffffffff81776ddb: ioc_create_icq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff817b8e70)
Location: block/blk-ioc.c:363
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
```
**Symbols:**

```
ffffffff817b8e70-ffffffff817b9008: ioc_create_icq (STB_LOCAL)
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
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffff8000105e8f38)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffff8000105e8f38-ffff8000105e9134: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c0795628)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
c0795628-c079578c: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c00000000077dba0)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
c00000000077dba0-c00000000077ddfc: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffe000429846)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffe000429846-ffffffe0004299de: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814e2f54-ffffffff814e2f65: ioc_create_icq.cold (STB_LOCAL)
ffffffff814e2dd0-ffffffff814e2f54: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814d38de-ffffffff814d38ef: ioc_create_icq.cold (STB_LOCAL)
ffffffff814d3760-ffffffff814d38de: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814defe4-ffffffff814deff5: ioc_create_icq.cold (STB_LOCAL)
ffffffff814dee60-ffffffff814defe4: ioc_create_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct io_cq *ioc_create_icq(struct io_context *ioc, struct request_queue *q, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-ioc.c (0)
Location: block/blk-ioc.c:365
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814f7e4b-ffffffff814f7e64: ioc_create_icq.cold (STB_LOCAL)
ffffffff814f7cb0-ffffffff814f7e4b: ioc_create_icq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_context *ioc</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
<li>
<b>Param reordered. </b>
<code>ioc, q, gfp_mask</code> ➡️ <code>q</code>
</li>
</ul>
</details>
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
