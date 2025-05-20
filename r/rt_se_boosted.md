# Function: <code>rt_se_boosted</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810edcc1)
Location: kernel/sched/rt.c:528
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014ec60)
Location: kernel/sched/rt.c:528
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039cdb4)
Location: kernel/sched/rt.c:528
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
  - kernel/sched/rt.c:__enqueue_rt_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a2c34)
Location: kernel/sched/rt.c:528
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f760a)
Location: kernel/sched/rt.c:528
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d7011)
Location: kernel/sched/rt.c:528
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e41f1)
Location: kernel/sched/rt.c:528
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_rt_stack
  - kernel/sched/rt.c:__enqueue_rt_entity
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
