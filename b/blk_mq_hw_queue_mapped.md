# Function: <code>blk_mq_hw_queue_mapped</code>

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
In block/blk-mq.c (ffffffff813c3394)
Location: block/blk-mq.h:116
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_timer
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff813c7792)
Location: block/blk-mq.h:116
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff81407355)
Location: block/blk-mq.h:117
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff8140b9d2)
Location: block/blk-mq.h:117
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff81421b15)
Location: block/blk-mq.h:111
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff81425fb9)
Location: block/blk-mq.h:111
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff8142fc25)
Location: block/blk-mq.h:132
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff81433d19)
Location: block/blk-mq.h:132
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff8145b754)
Location: block/blk-mq.h:134
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff8145f9dc)
Location: block/blk-mq.h:134
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff8148e1e4)
Location: block/blk-mq.h:147
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff814932da)
Location: block/blk-mq.h:147
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff814a7ae0)
Location: block/blk-mq.h:189
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff814ad29c)
Location: block/blk-mq.h:189
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff814d73b5)
Location: block/blk-mq.h:182
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff814db50d)
Location: block/blk-mq.h:182
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff814f0735)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff814f493d)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff81550985)
Location: block/blk-mq.h:173
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff815552f9)
Location: block/blk-mq.h:173
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff8156d0c5)
Location: block/blk-mq.h:180
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff815719af)
Location: block/blk-mq.h:180
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff81574e05)
Location: block/blk-mq.h:181
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff815799f6)
Location: block/blk-mq.h:181
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff815d9715)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff815decf6)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff816847a5)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff8168d1ad)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff81742435)
Location: block/blk-mq.h:184
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff8174b9ca)
Location: block/blk-mq.h:184
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff8177db45)
Location: block/blk-mq.h:234
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff817880ea)
Location: block/blk-mq.h:234
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff817c01b5)
Location: block/blk-mq.h:234
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff817ca7ba)
Location: block/blk-mq.h:234
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffff8000105ee208)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffff8000105f4794)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (c079a348)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (c07a03c4)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (c000000000783efc)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (c00000000078c0ac)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffe00042eb86)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffe00043271c)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff814e8d15)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff814ecf1d)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff814d9285)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff814dd46d)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff814e4da5)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff814e8fad)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
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
In block/blk-mq.c (ffffffff814fc4b5)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_hctx
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_wake_waiters
```
```
In block/blk-mq-tag.c (ffffffff81501f70)
Location: block/blk-mq.h:183
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
```
</details>
</li>
</ul>

## Differences
