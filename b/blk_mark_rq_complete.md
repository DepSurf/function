# Function: <code>blk_mark_rq_complete</code>

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
In block/blk-softirq.c (ffffffff813c1f55)
Location: block/blk.h:127
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff813c21cb)
Location: block/blk.h:127
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_rq_timed_out_timer
```
```
In block/blk-mq.c (ffffffff813c4205)
Location: block/blk.h:127
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
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
In block/blk-softirq.c (ffffffff81405ee5)
Location: block/blk.h:125
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff8140617f)
Location: block/blk.h:125
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff81407925)
Location: block/blk.h:125
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
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
In block/blk-softirq.c (ffffffff81420175)
Location: block/blk.h:121
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff8142040f)
Location: block/blk.h:121
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff81422555)
Location: block/blk.h:121
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
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
In block/blk-softirq.c (ffffffff8142e135)
Location: block/blk.h:135
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff8142e3cc)
Location: block/blk.h:135
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff8142f925)
Location: block/blk.h:135
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
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
In block/blk-softirq.c (ffffffff81459369)
Location: block/blk.h:142
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff814595d6)
Location: block/blk.h:142
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
```
```
In block/blk-mq.c (ffffffff8145aea9)
Location: block/blk.h:142
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
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
In block/blk-softirq.c (ffffffff8148c8b5)
Location: block/blk.h:197
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_complete_request
```
```
In block/blk-timeout.c (ffffffff8148cb26)
Location: block/blk.h:197
Inline: True
Inline callers:
  - block/blk-timeout.c:blk_timeout_work
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
