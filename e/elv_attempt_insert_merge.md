# Function: <code>elv_attempt_insert_merge</code>

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
In block/elevator.c (ffffffff813b40c7)
Location: block/elevator.c:462
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
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
In block/elevator.c (ffffffff813f7d6c)
Location: block/elevator.c:461
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
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
In block/elevator.c (ffffffff81411793)
Location: block/elevator.c:459
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141f000)
Location: block/elevator.c:488
Inline: True
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff8141f000-ffffffff8141f098: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449ae0)
Location: block/elevator.c:505
Inline: True
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff81449ae0-ffffffff81449b77: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c830)
Location: block/elevator.c:474
Inline: True
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff8147c830-ffffffff8147c8c6: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a800)
Location: block/elevator.c:345
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff8149a800-ffffffff8149a890: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c88c0)
Location: block/elevator.c:346
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff814c88c0-ffffffff814c8952: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e19e0)
Location: block/elevator.c:356
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff814e19e0-ffffffff814e1a71: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81540550)
Location: block/elevator.c:356
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff81540550-ffffffff815405e1: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155ccf0)
Location: block/elevator.c:355
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff8155ccf0-ffffffff8155cd81: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81565580)
Location: block/elevator.c:355
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff81565580-ffffffff81565611: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq, struct list_head *free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9930)
Location: block/elevator.c:359
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff815c9930-ffffffff815c9a01: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq, struct list_head *free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674c10)
Location: block/elevator.c:364
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff81674c10-ffffffff81674d09: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq, struct list_head *free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730970)
Location: block/elevator.c:332
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff81730970-ffffffff81730a69: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq, struct list_head *free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176cbd0)
Location: block/elevator.c:332
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff8176cbd0-ffffffff8176cccf: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq, struct list_head *free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817aee00)
Location: block/elevator.c:332
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff817aee00-ffffffff817aeefa: elv_attempt_insert_merge (STB_GLOBAL)
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
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105deb10)
Location: block/elevator.c:356
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffff8000105deb10-ffff8000105debc4: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078ba90)
Location: block/elevator.c:356
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
c078ba90-c078bb38: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770930)
Location: block/elevator.c:356
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
c000000000770930-c000000000770a34: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe0004216aa)
Location: block/elevator.c:356
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffe0004216aa-ffffffe000421736: elv_attempt_insert_merge (STB_GLOBAL)
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
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9fc0)
Location: block/elevator.c:356
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff814d9fc0-ffffffff814da051: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca970)
Location: block/elevator.c:356
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff814ca970-ffffffff814caa01: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d6050)
Location: block/elevator.c:356
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff814d6050-ffffffff814d60e1: elv_attempt_insert_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814eec50)
Location: block/elevator.c:356
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_insert_merge
```
**Symbols:**

```
ffffffff814eec50-ffffffff814eece1: elv_attempt_insert_merge (STB_GLOBAL)
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
