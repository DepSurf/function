# Function: <code>blk_do_io_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba116)
Location: block/blk.h:254
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-merge.c (ffffffff813c189d)
Location: block/blk.h:254
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff813c3242)
Location: block/blk.h:254
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe6a5)
Location: block/blk.h:252
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-merge.c (ffffffff814057b5)
Location: block/blk.h:252
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418085)
Location: block/blk.h:248
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-merge.c (ffffffff8141fa47)
Location: block/blk.h:248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425f35)
Location: block/blk.h:264
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-merge.c (ffffffff8142d928)
Location: block/blk.h:264
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814513a5)
Location: block/blk.h:234
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-merge.c (ffffffff81458b78)
Location: block/blk.h:234
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484615)
Location: block/blk.h:300
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In block/blk-merge.c (ffffffff8148bc98)
Location: block/blk.h:300
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149f5e5)
Location: block/blk.h:220
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814a593c)
Location: block/blk.h:220
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd6d5)
Location: block/blk.h:239
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814d394f)
Location: block/blk.h:239
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e69c5)
Location: block/blk.h:253
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814ecc7f)
Location: block/blk.h:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815437c5)
Location: block/blk.h:262
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff8154ae45)
Location: block/blk.h:262
Inline: True
Inline callers:
  - block/blk-merge.c:blk_account_io_merge_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8156069d)
Location: block/blk.h:239
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff81566c05)
Location: block/blk.h:239
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81568cfe)
Location: block/blk.h:243
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff8156f145)
Location: block/blk.h:243
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ccf98)
Location: block/blk.h:247
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff815d37f5)
Location: block/blk.h:247
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81680ded)
Location: block/blk.h:325
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff81688023)
Location: block/blk.h:325
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_mq_check_inflight
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173e2d3)
Location: block/blk.h:340
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff81746401)
Location: block/blk.h:340
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_end_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_mq_check_inflight
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177a835)
Location: block/blk.h:343
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff817837a9)
Location: block/blk.h:343
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_mq_check_inflight
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bcc15)
Location: block/blk.h:341
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In block/blk-mq.c (ffffffff817c5b19)
Location: block/blk.h:341
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_execute_rq
  - block/blk-mq.c:blk_execute_rq_nowait
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_account_io_done
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_mq_check_inflight
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e41f4)
Location: block/blk.h:253
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffff8000105eb660)
Location: block/blk.h:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c07914f4)
Location: block/blk.h:253
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (c0797c14)
Location: block/blk.h:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000777f10)
Location: block/blk.h:253
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (c000000000780c8c)
Location: block/blk.h:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000425ab8)
Location: block/blk.h:253
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffe00042b6ea)
Location: block/blk.h:253
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814defa5)
Location: block/blk.h:253
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814e525f)
Location: block/blk.h:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cf945)
Location: block/blk.h:253
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814d590e)
Location: block/blk.h:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814db035)
Location: block/blk.h:253
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814e12ef)
Location: block/blk.h:253
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f3e15)
Location: block/blk.h:253
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814fa16f)
Location: block/blk.h:253
Inline: True
```
</details>
</li>
</ul>

## Differences
