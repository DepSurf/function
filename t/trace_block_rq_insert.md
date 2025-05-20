# Function: <code>trace_block_rq_insert</code>

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
In block/elevator.c (ffffffff813b3f8b)
Location: include/trace/events/block.h:223
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-mq.c (ffffffff813c34d3)
Location: include/trace/events/block.h:223
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
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
In block/elevator.c (ffffffff813f7c6b)
Location: include/trace/events/block.h:225
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-mq.c (ffffffff81409f18)
Location: include/trace/events/block.h:225
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_request
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
In block/elevator.c (ffffffff8141169b)
Location: include/trace/events/block.h:223
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-mq.c (ffffffff814248a2)
Location: include/trace/events/block.h:223
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_request
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
In block/elevator.c (ffffffff8141f289)
Location: include/trace/events/block.h:191
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-mq.c (ffffffff8143163f)
Location: include/trace/events/block.h:191
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_requests
```
```
In block/blk-mq-sched.c (ffffffff81435185)
Location: include/trace/events/block.h:191
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/elevator.c (ffffffff81449d69)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-mq.c (ffffffff8145d007)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_requests
```
```
In block/blk-mq-sched.c (ffffffff81460d8e)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/elevator.c (ffffffff8147caa5)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/elevator.c:__elv_add_request
```
```
In block/blk-mq.c (ffffffff814910af)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffff81494645)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffff814aa34d)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffff814ae775)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffff814d8b49)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffff814dca95)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffff814f1f09)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffff814f5f05)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffff81552619)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffff81556b35)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffff8156e7a1)
Location: include/trace/events/block.h:190
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffff815735a5)
Location: include/trace/events/block.h:190
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffff81576381)
Location: include/trace/events/block.h:190
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/mq-deadline.c (ffffffff81599313)
Location: include/trace/events/block.h:190
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_requests
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
In block/blk-mq.c (ffffffff815daf71)
Location: include/trace/events/block.h:190
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/mq-deadline.c (ffffffff816019d4)
Location: include/trace/events/block.h:190
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_insert_request
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
In block/blk-mq.c (ffffffff81688e61)
Location: include/trace/events/block.h:213
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/mq-deadline.c (ffffffff816b4463)
Location: include/trace/events/block.h:213
Inline: True
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
In block/blk-mq.c (ffffffff81747381)
Location: include/trace/events/block.h:213
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/mq-deadline.c (ffffffff81773e63)
Location: include/trace/events/block.h:213
Inline: True
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
In block/blk-mq.c (ffffffff8178037e)
Location: include/trace/events/block.h:213
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
```
```
In block/mq-deadline.c (ffffffff817b4031)
Location: include/trace/events/block.h:213
Inline: True
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
In block/blk-mq.c (ffffffff817c294e)
Location: include/trace/events/block.h:215
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_insert_requests
```
```
In block/mq-deadline.c (ffffffff817f7fc4)
Location: include/trace/events/block.h:215
Inline: True
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
In block/blk-mq.c (ffff8000105f16b8)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffff8000105f6940)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (c079d768)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (c07a1c18)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (c0000000007884c4)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (c00000000078e400)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffe000430200)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffe000433e3a)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffff814ea4e9)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffff814ee4e5)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffff814daa39)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffff814dea35)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffff814e6579)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffff814ea575)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
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
In block/blk-mq.c (ffffffff814ff54c)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:__blk_mq_insert_request
  - block/blk-mq.c:__blk_mq_insert_request
```
```
In block/blk-mq-sched.c (ffffffff81503545)
Location: include/trace/events/block.h:192
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_request_inserted
```
</details>
</li>
</ul>

## Differences
