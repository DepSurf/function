# Function: <code>blk_mq_queue_reinit</code>

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
In block/blk-mq.c (ffffffff813c5970)
Location: block/blk-mq.c:2101
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_queue_reinit(struct request_queue *q, const struct cpumask *online_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814085e0)
Location: block/blk-mq.c:2155
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff814085e0-ffffffff81408654: blk_mq_queue_reinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_queue_reinit(struct request_queue *q, const struct cpumask *online_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81423080)
Location: block/blk-mq.c:2204
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_queue_reinit_work
```
**Symbols:**

```
ffffffff81423080-ffffffff814230df: blk_mq_queue_reinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81433099)
Location: block/blk-mq.c:2410
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145ec4a)
Location: block/blk-mq.c:2557
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8149259b)
Location: block/blk-mq.c:2619
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
