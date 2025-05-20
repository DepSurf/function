# Function: <code>task_node</code>

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
In kernel/sched/fair.c (ffffffff810b492d)
Location: include/linux/sched.h:3093
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/debug.c (ffffffff810c6982)
Location: include/linux/sched.h:3093
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/fair.c (ffffffff810b7485)
Location: include/linux/sched.h:3370
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810cc9f7)
Location: include/linux/sched.h:3370
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
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
In kernel/sched/fair.c (ffffffff810be175)
Location: include/linux/sched.h:3543
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810d2a17)
Location: include/linux/sched.h:3543
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
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
In kernel/sched/fair.c (ffffffff810ba255)
Location: include/linux/sched/topology.h:221
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810d1b62)
Location: include/linux/sched/topology.h:221
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
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
In kernel/sched/fair.c (ffffffff810c22b4)
Location: include/linux/sched/topology.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810d9703)
Location: include/linux/sched/topology.h:222
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
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
In kernel/sched/fair.c (ffffffff810c7be1)
Location: include/linux/sched/topology.h:222
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810e0718)
Location: include/linux/sched/topology.h:222
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
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
In kernel/sched/fair.c (ffffffff810d1a11)
Location: include/linux/sched/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/debug.c (ffffffff810eaece)
Location: include/linux/sched/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
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
In kernel/sched/fair.c (ffffffff810d8f9c)
Location: include/linux/sched/topology.h:218
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810f1d02)
Location: include/linux/sched/topology.h:218
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/fair.c (ffffffff810e2bac)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810fd9c2)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/fair.c (ffffffff810ebc5c)
Location: include/linux/sched/topology.h:235
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/debug.c (ffffffff81105afb)
Location: include/linux/sched/topology.h:235
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
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
In kernel/sched/fair.c (ffffffff810ef433)
Location: include/linux/sched/topology.h:269
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/debug.c (ffffffff8110414b)
Location: include/linux/sched/topology.h:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
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
In kernel/sched/fair.c (ffffffff810f0e43)
Location: include/linux/sched/topology.h:269
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/debug.c (ffffffff81106e6b)
Location: include/linux/sched/topology.h:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
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
In kernel/sched/fair.c (ffffffff8110a8d3)
Location: include/linux/sched/topology.h:269
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/debug.c (ffffffff81124a4d)
Location: include/linux/sched/topology.h:269
Inline: True
Inline callers:
  - kernel/sched/debug.c:sched_show_numa
  - kernel/sched/debug.c:sched_show_numa
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
In kernel/sched/fair.c (ffffffff81126292)
Location: include/linux/sched/topology.h:278
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/build_utility.c (ffffffff8113d63e)
Location: include/linux/sched/topology.h:278
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
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
In kernel/sched/fair.c (ffffffff8114f6fd)
Location: include/linux/sched/topology.h:278
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/build_utility.c (ffffffff811680bc)
Location: include/linux/sched/topology.h:278
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
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
In kernel/sched/fair.c (ffffffff8115e598)
Location: include/linux/sched/topology.h:278
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/build_utility.c (ffffffff8117877c)
Location: include/linux/sched/topology.h:278
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
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
In kernel/sched/fair.c (ffffffff8116cb7c)
Location: include/linux/sched/topology.h:290
Inline: True
Inline callers:
  - kernel/sched/fair.c:dequeue_entity
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/sched/build_utility.c (ffffffff8118649c)
Location: include/linux/sched/topology.h:290
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_show_numa
  - kernel/sched/build_utility.c:sched_show_numa
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
In kernel/sched/fair.c (ffff8000101427e0)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffff8000101631b8)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000192e0c)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (c0000000001b99c8)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/sched/fair.c (ffffffff810dcd5c)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810f6ce2)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/fair.c (ffffffff810cbd6c)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810e6eb2)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/fair.c (ffffffff810d90dc)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810f3ef2)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/fair.c (ffffffff810e4b0c)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/fair.c:account_entity_dequeue
  - kernel/sched/fair.c:account_entity_enqueue
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/debug.c (ffffffff810feee5)
Location: include/linux/sched/topology.h:228
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
</ul>

## Differences
