# Function: <code>blk_account_io_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba910)
Location: block/blk-core.c:2327
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_bio_to_request
```
**Symbols:**

```
ffffffff813ba910-ffffffff813baadb: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe6a0)
Location: block/blk-core.c:2297
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813fe6a0-ffffffff813fe86d: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418080)
Location: block/blk-core.c:2280
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81418080-ffffffff81418265: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425f30)
Location: block/blk-core.c:2469
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81425f30-ffffffff814260cf: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814513a0)
Location: block/blk-core.c:2638
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_bio_to_request
```
**Symbols:**

```
ffffffff814513a0-ffffffff8145150d: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484610)
Location: block/blk-core.c:2781
Inline: False
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:blk_queue_bio
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_bio_to_request
```
**Symbols:**

```
ffffffff81484610-ffffffff81484771: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149f5e0)
Location: block/blk-core.c:1349
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff8149f5e0-ffffffff8149f74a: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd6d0)
Location: block/blk-core.c:1315
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814cd6d0-ffffffff814cd846: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e69c0)
Location: block/blk-core.c:1350
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814e69c0-ffffffff814e6b36: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81545f20)
Location: block/blk-core.c:1445
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81545f20-ffffffff81545f6a: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81561d40)
Location: block/blk-core.c:1311
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81561d40-ffffffff81561d8a: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_account_io_start(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8156a4a0)
Location: block/blk-core.c:1296
Inline: True
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff8156a4a0-ffffffff8156a4f3: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_account_io_start(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ce9a0)
Location: block/blk-core.c:1273
Inline: True
Direct callers:
  - block/blk-exec.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff815ce9a0-ffffffff815ce9f3: blk_account_io_start (STB_GLOBAL)
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
In block/blk-mq.c (ffffffff81688023)
Location: block/blk-mq.c:911
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_execute_rq_nowait
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
In block/blk-mq.c (ffffffff81746401)
Location: block/blk-mq.c:1020
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_execute_rq_nowait
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
In block/blk-mq.c (ffffffff817837a4)
Location: block/blk-mq.c:1000
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_execute_rq_nowait
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
In block/blk-mq.c (ffffffff817c5b14)
Location: block/blk-mq.c:1010
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_execute_rq_nowait
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
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e41d8)
Location: block/blk-core.c:1350
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffff8000105e41d8-ffff8000105e43f8: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c07914e0)
Location: block/blk-core.c:1350
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c07914e0-c0791694: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000777f00)
Location: block/blk-core.c:1350
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
c000000000777f00-c000000000778150: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000425a9c)
Location: block/blk-core.c:1350
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffe000425a9c-ffffffe000425bfa: blk_account_io_start (STB_GLOBAL)
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
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814defa0)
Location: block/blk-core.c:1350
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814defa0-ffffffff814df116: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cf940)
Location: block/blk-core.c:1350
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814cf940-ffffffff814cfab6: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db030)
Location: block/blk-core.c:1350
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814db030-ffffffff814db1a6: blk_account_io_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_account_io_start(struct request *rq, bool new_io);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f3e10)
Location: block/blk-core.c:1350
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814f3e10-ffffffff814f3fea: blk_account_io_start (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool new_io</code>
</li>
</ul>
</details>
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
