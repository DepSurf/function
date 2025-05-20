# Function: <code>attempt_front_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813c1ad0)
Location: block/blk-merge.c:734
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff813c1ad0-ffffffff813c1b01: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81405ab0)
Location: block/blk-merge.c:760
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff81405ab0-ffffffff81405ae1: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141fd50)
Location: block/blk-merge.c:751
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
```
**Symbols:**

```
ffffffff8141fd50-ffffffff8141fd81: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142dc90)
Location: block/blk-merge.c:747
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8142dc90-ffffffff8142dcbf: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81458ec0)
Location: block/blk-merge.c:748
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff81458ec0-ffffffff81458eef: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148c420)
Location: block/blk-merge.c:779
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8148c420-ffffffff8148c44f: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a6030)
Location: block/blk-merge.c:824
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814a6030-ffffffff814a605f: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d3f00)
Location: block/blk-merge.c:771
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814d3f00-ffffffff814d3f31: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814ed230)
Location: block/blk-merge.c:824
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814ed230-ffffffff814ed261: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154cd00)
Location: block/blk-merge.c:821
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff8154cd00-ffffffff8154cd99: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815690b7)
Location: block/blk-merge.c:839
Inline: True
Inline callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
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
In block/blk-merge.c (ffffffff81571017)
Location: block/blk-merge.c:842
Inline: True
Inline callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
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
In block/blk-merge.c (ffffffff815d56d7)
Location: block/blk-merge.c:828
Inline: True
Inline callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff816814bb)
Location: block/blk-merge.c:837
Inline: True
Inline callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173ea5b)
Location: block/blk-merge.c:902
Inline: True
Inline callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177afbb)
Location: block/blk-merge.c:898
Inline: True
Inline callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bd3ab)
Location: block/blk-merge.c:894
Inline: True
Inline callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
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
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105ebc58)
Location: block/blk-merge.c:824
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffff8000105ebc58-ffff8000105ebca0: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c07981a0)
Location: block/blk-merge.c:824
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c07981a0-c07981dc: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c0000000007810e0)
Location: block/blk-merge.c:824
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
c0000000007810e0-c000000000781158: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042b9da)
Location: block/blk-merge.c:824
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffe00042b9da-ffffffe00042ba1c: attempt_front_merge (STB_GLOBAL)
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
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e5810)
Location: block/blk-merge.c:824
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814e5810-ffffffff814e5841: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d5dc0)
Location: block/blk-merge.c:824
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814d5dc0-ffffffff814d5df1: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e18a0)
Location: block/blk-merge.c:824
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814e18a0-ffffffff814e18d1: attempt_front_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request *attempt_front_merge(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814fa760)
Location: block/blk-merge.c:824
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_try_merge
```
**Symbols:**

```
ffffffff814fa760-ffffffff814fa791: attempt_front_merge (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct request *</code>
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
