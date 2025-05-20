# Function: <code>blk_mq_sched_insert_request</code>

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
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async, bool can_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81435b30)
Location: block/blk-mq-sched.c:357
Inline: False
Direct callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff81435b30-ffffffff81435cae: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async, bool can_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814618d0)
Location: block/blk-mq-sched.c:430
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff814618d0-ffffffff81461a2e: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81495210)
Location: block/blk-mq-sched.c:446
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff81495210-ffffffff81495386: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814af1a0)
Location: block/blk-mq-sched.c:376
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff814af1a0-ffffffff814af309: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-sched.c (0)
Location: block/blk-mq-sched.c:378
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff814dd96b-ffffffff814dd99a: blk_mq_sched_insert_request.cold (STB_LOCAL)
ffffffff814dd420-ffffffff814dd581: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f6890)
Location: block/blk-mq-sched.c:384
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff814f6890-ffffffff814f6a13: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81557340)
Location: block/blk-mq-sched.c:449
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff81557340-ffffffff815574bc: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815739c0)
Location: block/blk-mq-sched.c:417
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff815739c0-ffffffff81573add: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8157ba50)
Location: block/blk-mq-sched.c:419
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff8157ba50-ffffffff8157bb63: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815e0e40)
Location: block/blk-mq-sched.c:429
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff815e0e40-ffffffff815e0f42: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8168fa00)
Location: block/blk-mq-sched.c:408
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff8168fa00-ffffffff8168fb0a: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8174e560)
Location: block/blk-mq-sched.c:407
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
```
**Symbols:**

```
ffffffff8174e560-ffffffff8174e66a: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f6ef0)
Location: block/blk-mq-sched.c:384
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffff8000105f6ef0-ffff8000105f70c0: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a2650)
Location: block/blk-mq-sched.c:384
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
c07a2650-c07a2810: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078f3e0)
Location: block/blk-mq-sched.c:384
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
c00000000078f3e0-c00000000078f628: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe000434668)
Location: block/blk-mq-sched.c:384
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffe000434668-ffffffe0004347c4: blk_mq_sched_insert_request (STB_GLOBAL)
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
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eee70)
Location: block/blk-mq-sched.c:384
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff814eee70-ffffffff814eeff3: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814df3b0)
Location: block/blk-mq-sched.c:384
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff814df3b0-ffffffff814df533: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eaf00)
Location: block/blk-mq-sched.c:384
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff814eaf00-ffffffff814eb083: blk_mq_sched_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request *rq, bool at_head, bool run_queue, bool async);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81503ed0)
Location: block/blk-mq-sched.c:384
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
**Symbols:**

```
ffffffff81503ed0-ffffffff81504052: blk_mq_sched_insert_request (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool can_block</code>
</li>
</ul>
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
