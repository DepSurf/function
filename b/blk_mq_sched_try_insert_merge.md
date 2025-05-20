# Function: <code>blk_mq_sched_try_insert_merge</code>

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
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814353a0)
Location: block/blk-mq-sched.c:250
Inline: False
```
**Symbols:**

```
ffffffff814353a0-ffffffff814353e2: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814611d0)
Location: block/blk-mq-sched.c:338
Inline: False
```
**Symbols:**

```
ffffffff814611d0-ffffffff81461212: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81494bf0)
Location: block/blk-mq-sched.c:354
Inline: False
```
**Symbols:**

```
ffffffff81494bf0-ffffffff81494c31: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814aed30)
Location: block/blk-mq-sched.c:346
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814aed30-ffffffff814aed74: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dcff0)
Location: block/blk-mq-sched.c:348
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814dcff0-ffffffff814dd034: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f6460)
Location: block/blk-mq-sched.c:348
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814f6460-ffffffff814f64a4: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81556ac0)
Location: block/blk-mq-sched.c:413
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81556ac0-ffffffff81556b04: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81573530)
Location: block/blk-mq-sched.c:381
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81573530-ffffffff81573574: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8157b430)
Location: block/blk-mq-sched.c:393
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff8157b430-ffffffff8157b471: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq, struct list_head *free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815e07b0)
Location: block/blk-mq-sched.c:402
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_request
```
**Symbols:**

```
ffffffff815e07b0-ffffffff815e07f5: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq, struct list_head *free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8168f2e0)
Location: block/blk-mq-sched.c:381
Inline: False
```
**Symbols:**

```
ffffffff8168f2e0-ffffffff8168f343: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq, struct list_head *free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8174dd70)
Location: block/blk-mq-sched.c:380
Inline: False
```
**Symbols:**

```
ffffffff8174dd70-ffffffff8174ddd3: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq, struct list_head *free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8178a2f0)
Location: block/blk-mq-sched.c:375
Inline: False
```
**Symbols:**

```
ffffffff8178a2f0-ffffffff8178a353: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq, struct list_head *free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff817cca50)
Location: block/blk-mq-sched.c:373
Inline: False
```
**Symbols:**

```
ffffffff817cca50-ffffffff817ccab3: blk_mq_sched_try_insert_merge (STB_GLOBAL)
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
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f6830)
Location: block/blk-mq-sched.c:348
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffff8000105f6830-ffff8000105f68c0: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a21cc)
Location: block/blk-mq-sched.c:348
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
c07a21cc-c07a2240: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078ecc0)
Location: block/blk-mq-sched.c:348
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
c00000000078ecc0-c00000000078ed50: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe000434226)
Location: block/blk-mq-sched.c:348
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffe000434226-ffffffe00043429e: blk_mq_sched_try_insert_merge (STB_GLOBAL)
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
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eea40)
Location: block/blk-mq-sched.c:348
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814eea40-ffffffff814eea84: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814def90)
Location: block/blk-mq-sched.c:348
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814def90-ffffffff814defd4: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eaad0)
Location: block/blk-mq-sched.c:348
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814eaad0-ffffffff814eab14: blk_mq_sched_try_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_mq_sched_try_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81503ac0)
Location: block/blk-mq-sched.c:348
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81503ac0-ffffffff81503b04: blk_mq_sched_try_insert_merge (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_head *free</code>
</li>
</ul>
</details>
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
