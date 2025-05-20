# Function: <code>blk_mq_alloc_request_hctx</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, int rw, unsigned int flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81407190)
Location: block/blk-mq.c:274
Inline: True
```
**Symbols:**

```
ffffffff81407190-ffffffff814072dd: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, int rw, unsigned int flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81421710)
Location: block/blk-mq.c:271
Inline: True
```
**Symbols:**

```
ffffffff81421710-ffffffff8142185a: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, unsigned int flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142f530)
Location: block/blk-mq.c:377
Inline: False
```
**Symbols:**

```
ffffffff8142f530-ffffffff8142f66c: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145aa80)
Location: block/blk-mq.c:413
Inline: False
```
**Symbols:**

```
ffffffff8145aa80-ffffffff8145abb9: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148f000)
Location: block/blk-mq.c:425
Inline: False
```
**Symbols:**

```
ffffffff8148f000-ffffffff8148f145: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a8a90)
Location: block/blk-mq.c:438
Inline: False
```
**Symbols:**

```
ffffffff814a8a90-ffffffff814a8bcd: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6480)
Location: block/blk-mq.c:435
Inline: False
```
**Symbols:**

```
ffffffff814d6480-ffffffff814d65bd: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ef7f0)
Location: block/blk-mq.c:446
Inline: False
```
**Symbols:**

```
ffffffff814ef7f0-ffffffff814ef92d: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154eac0)
Location: block/blk-mq.c:433
Inline: False
```
**Symbols:**

```
ffffffff8154eac0-ffffffff8154ec57: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156afc0)
Location: block/blk-mq.c:429
Inline: False
```
**Symbols:**

```
ffffffff8156afc0-ffffffff8156b14f: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81572dc0)
Location: block/blk-mq.c:430
Inline: False
```
**Symbols:**

```
ffffffff81572dc0-ffffffff81572f50: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d7460)
Location: block/blk-mq.c:437
Inline: False
```
**Symbols:**

```
ffffffff815d7460-ffffffff815d761c: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81683a50)
Location: block/blk-mq.c:539
Inline: False
```
**Symbols:**

```
ffffffff81683a50-ffffffff81683c2c: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, blk_opf_t opf, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81741030)
Location: block/blk-mq.c:636
Inline: False
```
**Symbols:**

```
ffffffff81741030-ffffffff8174125c: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, blk_opf_t opf, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81781fb0)
Location: block/blk-mq.c:610
Inline: False
```
**Symbols:**

```
ffffffff81781fb0-ffffffff81782230: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, blk_opf_t opf, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c4300)
Location: block/blk-mq.c:614
Inline: False
```
**Symbols:**

```
ffffffff817c4300-ffffffff817c45c9: blk_mq_alloc_request_hctx (STB_GLOBAL)
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
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105efc10)
Location: block/blk-mq.c:446
Inline: False
```
**Symbols:**

```
ffff8000105efc10-ffff8000105efd48: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079ad18)
Location: block/blk-mq.c:446
Inline: False
```
**Symbols:**

```
c079ad18-c079ae7c: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000784b70)
Location: block/blk-mq.c:446
Inline: False
```
**Symbols:**

```
c000000000784b70-c000000000784d40: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042dc7a)
Location: block/blk-mq.c:446
Inline: False
```
**Symbols:**

```
ffffffe00042dc7a-ffffffe00042dd72: blk_mq_alloc_request_hctx (STB_GLOBAL)
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
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7dd0)
Location: block/blk-mq.c:446
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_alloc_request
```
**Symbols:**

```
ffffffff814e7dd0-ffffffff814e7f0d: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8340)
Location: block/blk-mq.c:446
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_alloc_request
```
**Symbols:**

```
ffffffff814d8340-ffffffff814d847d: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3e60)
Location: block/blk-mq.c:446
Inline: False
```
**Symbols:**

```
ffffffff814e3e60-ffffffff814e3f9d: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request *blk_mq_alloc_request_hctx(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fd3c0)
Location: block/blk-mq.c:446
Inline: False
```
**Symbols:**

```
ffffffff814fd3c0-ffffffff814fd4fd: blk_mq_alloc_request_hctx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int flags</code> ➡️ <code>blk_mq_req_flags_t flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int op</code>
</li>
</ul>
</details>
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
