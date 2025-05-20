# Function: <code>ioc_lookup_icq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff813bedf0)
Location: block/blk-ioc.c:317
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-ioc.c:ioc_create_icq
  - block/cfq-iosched.c:cfq_allow_merge
  - block/cfq-iosched.c:cfq_merge
  - block/cfq-iosched.c:cfq_may_queue
```
**Symbols:**

```
ffffffff813bedf0-ffffffff813bee3b: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81402dc0)
Location: block/blk-ioc.c:317
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-ioc.c:ioc_create_icq
  - block/cfq-iosched.c:cfq_may_queue
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_merge
```
**Symbols:**

```
ffffffff81402dc0-ffffffff81402e09: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8141caf0)
Location: block/blk-ioc.c:317
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-ioc.c:ioc_create_icq
  - block/cfq-iosched.c:cfq_may_queue
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_merge
```
**Symbols:**

```
ffffffff8141caf0-ffffffff8141cb39: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8142aa60)
Location: block/blk-ioc.c:348
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
  - block/cfq-iosched.c:cfq_may_queue
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_merge
```
**Symbols:**

```
ffffffff8142aa60-ffffffff8142aaac: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81455c50)
Location: block/blk-ioc.c:349
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
  - block/cfq-iosched.c:cfq_may_queue
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_merge
```
**Symbols:**

```
ffffffff81455c50-ffffffff81455c9c: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81488fd0)
Location: block/blk-ioc.c:349
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
  - block/cfq-iosched.c:cfq_may_queue
  - block/cfq-iosched.c:cfq_allow_bio_merge
  - block/cfq-iosched.c:cfq_merge
```
**Symbols:**

```
ffffffff81488fd0-ffffffff8148901c: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814a2e40)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814a2e40-ffffffff814a2e8c: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814d0ef0)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814d0ef0-ffffffff814d0f3c: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814ea2b0)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814ea2b0-ffffffff814ea2f9: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81549250)
Location: block/blk-ioc.c:332
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff81549250-ffffffff81549299: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81565030)
Location: block/blk-ioc.c:332
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff81565030-ffffffff81565092: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8156d6a0)
Location: block/blk-ioc.c:332
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff8156d6a0-ffffffff8156d702: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff815d1c90)
Location: block/blk-ioc.c:332
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff815d1c90-ffffffff815d1cf2: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8167d8a0)
Location: block/blk-ioc.c:328
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff8167d8a0-ffffffff8167d923: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8173a4a0)
Location: block/blk-ioc.c:328
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff8173a4a0-ffffffff8173a523: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff81776ba0)
Location: block/blk-ioc.c:324
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff81776ba0-ffffffff81776c26: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff817b8dd0)
Location: block/blk-ioc.c:324
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:ioc_create_icq
```
**Symbols:**

```
ffffffff817b8dd0-ffffffff817b8e56: ioc_lookup_icq (STB_GLOBAL)
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
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffff8000105e85c0)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffff8000105e85c0-ffff8000105e8630: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c07950f0)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
c07950f0-c0795154: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (c00000000077d380)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
c00000000077d380-c00000000077d448: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffe0004291e6)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffe0004291e6-ffffffe000429244: ioc_lookup_icq (STB_GLOBAL)
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
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814e2890)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814e2890-ffffffff814e28d9: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814d3220)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814d3220-ffffffff814d3269: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814de920)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814de920-ffffffff814de969: ioc_lookup_icq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct io_cq *ioc_lookup_icq(struct io_context *ioc, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff814f7830)
Location: block/blk-ioc.c:325
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_create_icq
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
**Symbols:**

```
ffffffff814f7830-ffffffff814f7897: ioc_lookup_icq (STB_GLOBAL)
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
<b>Param reordered. </b>
<code>ioc, q</code> ➡️ <code>q</code>
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
