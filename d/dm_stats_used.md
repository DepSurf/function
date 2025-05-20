# Function: <code>dm_stats_used</code>

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
In drivers/md/dm.c (ffffffff816a0a70)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_requeue_original_request
  - drivers/md/dm.c:dm_softirq_done
  - drivers/md/dm.c:dm_softirq_done
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_start_request
  - drivers/md/dm.c:dm_mq_queue_rq
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
In drivers/md/dm.c (ffffffff81703177)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff8170f934)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff81735041)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff81741950)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff8174e45f)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff8175b117)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff817c0480)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff817cd36a)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff818075e5)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffffffff81816173)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_start_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff818335d6)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffffffff81841c25)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff8187550b)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffffffff81884a4f)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff818a72bb)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffffffff818b6bf0)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff81976ff9)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:end_io_acct
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffffffff819874b0)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff8197bb8b)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm.c:end_io_acct
```
```
In drivers/md/dm-rq.c (ffffffff8198b450)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff81961360)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff8196fb40)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff81a0b01d)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:dm_io_dec_pending
```
```
In drivers/md/dm-rq.c (ffffffff81a18485)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff81b6fc80)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm.c:setup_split_accounting
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-rq.c (ffffffff81b81195)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff81d0c686)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-rq.c (ffffffff81d1f4c5)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff81d78cc4)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-rq.c (ffffffff81d886a5)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff81e2cfaf)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm.c:dm_io_acct
```
```
In drivers/md/dm-rq.c (ffffffff81e3fdb5)
Location: drivers/md/dm-stats.h:37
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffff800010afe59c)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffff800010b0ec28)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (c0bdcce0)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (c0bed018)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (c000000000beaca0)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (c000000000c01e14)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffe0006ed836)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffffffe0006fbe72)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff8184d13b)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffffffff8185ca70)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff8181475b)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffffffff81824040)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff8189c76b)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffffffff818ac0a0)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
In drivers/md/dm.c (ffffffff818b89ab)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:alloc_io
```
```
In drivers/md/dm-rq.c (ffffffff818c82f0)
Location: drivers/md/dm-stats.h:38
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
</details>
</li>
</ul>

## Differences
