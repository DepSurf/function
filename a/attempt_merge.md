# Function: <code>attempt_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813c1280)
Location: block/blk-merge.c:647
Inline: False
Direct callers:
  - block/blk-merge.c:attempt_back_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
**Symbols:**

```
ffffffff813c1280-ffffffff813c1a8d: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81405460)
Location: block/blk-merge.c:673
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff81405460-ffffffff81405a6d: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141f3e0)
Location: block/blk-merge.c:664
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff8141f3e0-ffffffff8141fd01: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142d260)
Location: block/blk-merge.c:648
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff8142d260-ffffffff8142dc58: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814584b0)
Location: block/blk-merge.c:649
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff814584b0-ffffffff81458e85: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148b960)
Location: block/blk-merge.c:676
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff8148b960-ffffffff8148c3e5: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a5620)
Location: block/blk-merge.c:724
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff814a5620-ffffffff814a6000: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d36e0)
Location: block/blk-merge.c:671
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff814d36e0-ffffffff814d3eb2: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814eca10)
Location: block/blk-merge.c:724
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff814eca10-ffffffff814ed1e2: attempt_merge (STB_LOCAL)
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
In block/blk-merge.c (ffffffff8154cda5)
Location: block/blk-merge.c:721
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff8154ca10-ffffffff8154cc51: attempt_merge.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffffffff815692c5)
Location: block/blk-merge.c:736
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_req_merge
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
**Symbols:**

```
ffffffff81568a90-ffffffff81568d93: attempt_merge.part.0 (STB_LOCAL)
ffffffff81568da0-ffffffff81568e11: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffffffff81571225)
Location: block/blk-merge.c:739
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_req_merge
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
**Symbols:**

```
ffffffff81570610-ffffffff81570acf: attempt_merge.part.0 (STB_LOCAL)
ffffffff81570ad0-ffffffff81570b41: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffffffff815d58e5)
Location: block/blk-merge.c:725
Inline: True
Inline callers:
  - block/blk-merge.c:blk_attempt_req_merge
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
**Symbols:**

```
ffffffff815d4cc0-ffffffff815d5171: attempt_merge.part.0 (STB_LOCAL)
ffffffff815d5180-ffffffff815d51f2: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81680b10)
Location: block/blk-merge.c:746
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
**Symbols:**

```
ffffffff81680b10-ffffffff81680fce: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173dfe0)
Location: block/blk-merge.c:811
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
**Symbols:**

```
ffffffff8173dfe0-ffffffff8173e4c7: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177a530)
Location: block/blk-merge.c:805
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
**Symbols:**

```
ffffffff8177a530-ffffffff8177aa23: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bc910)
Location: block/blk-merge.c:801
Inline: False
Direct callers:
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_mq_sched_try_merge
  - block/blk-merge.c:blk_attempt_req_merge
```
**Symbols:**

```
ffffffff817bc910-ffffffff817bce03: attempt_merge (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-merge.c (ffff8000105eb430)
Location: block/blk-merge.c:724
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffff8000105eb430-ffff8000105ebb24: attempt_merge.part.0 (STB_LOCAL)
ffff8000105ebb28-ffff8000105ebc0c: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c07979b4)
Location: block/blk-merge.c:724
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
c07979b4-c0798164: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c000000000780820)
Location: block/blk-merge.c:724
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
c000000000780820-c000000000781058: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042b3d2)
Location: block/blk-merge.c:724
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffe00042b3d2-ffffffe00042b998: attempt_merge (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e4ff0)
Location: block/blk-merge.c:724
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff814e4ff0-ffffffff814e57c2: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d56b0)
Location: block/blk-merge.c:724
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff814d56b0-ffffffff814d5d7a: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e1080)
Location: block/blk-merge.c:724
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff814e1080-ffffffff814e1852: attempt_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct request *attempt_merge(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814f9f00)
Location: block/blk-merge.c:724
Inline: True
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/blk-merge.c:attempt_front_merge
  - block/blk-merge.c:attempt_back_merge
```
**Symbols:**

```
ffffffff814f9f00-ffffffff814fa718: attempt_merge (STB_LOCAL)
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
