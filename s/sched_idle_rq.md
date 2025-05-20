# Function: <code>sched_idle_rq</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f567c)
Location: kernel/sched/fair.c:5444
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_smt
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f376c)
Location: kernel/sched/fair.c:5487
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_smt
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f5f6c)
Location: kernel/sched/fair.c:5550
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110ffdc)
Location: kernel/sched/fair.c:5584
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff8112beba)
Location: kernel/sched/fair.c:5629
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff81155af3)
Location: kernel/sched/fair.c:6026
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff81165c73)
Location: kernel/sched/fair.c:6279
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
In kernel/sched/fair.c (ffffffff811729d3)
Location: kernel/sched/fair.c:6685
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:dequeue_task_fair
  - kernel/sched/fair.c:dequeue_task_fair
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
