# Function: <code>futex_match</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2c7f)
Location: kernel/futex/futex.h:135
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_top_waiter
```
```
In kernel/futex/requeue.c (ffffffff811b641a)
Location: kernel/futex/futex.h:135
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/futex/waitwake.c (ffffffff811b6fc0)
Location: kernel/futex/futex.h:135
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
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
In kernel/futex/core.c (ffffffff811f3b3f)
Location: kernel/futex/futex.h:135
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_top_waiter
```
```
In kernel/futex/requeue.c (ffffffff811f755a)
Location: kernel/futex/futex.h:135
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/futex/waitwake.c (ffffffff811f8150)
Location: kernel/futex/futex.h:135
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
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
In kernel/futex/core.c (ffffffff812082df)
Location: kernel/futex/futex.h:135
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_top_waiter
```
```
In kernel/futex/requeue.c (ffffffff8120bcfa)
Location: kernel/futex/futex.h:135
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/futex/waitwake.c (ffffffff8120c8f2)
Location: kernel/futex/futex.h:135
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
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
In kernel/futex/core.c (ffffffff8121f16f)
Location: kernel/futex/futex.h:212
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_top_waiter
```
```
In kernel/futex/requeue.c (ffffffff8122328f)
Location: kernel/futex/futex.h:212
Inline: True
Inline callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
```
In kernel/futex/waitwake.c (ffffffff81223cbc)
Location: kernel/futex/futex.h:212
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
</details>
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
