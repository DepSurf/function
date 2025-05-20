# Function: <code>deref_curr_numa_group</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810de98a)
Location: kernel/sched/fair.c:1099
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8eda)
Location: kernel/sched/fair.c:1098
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f35a0)
Location: kernel/sched/fair.c:1109
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
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
In kernel/sched/fair.c (ffffffff810f17e0)
Location: kernel/sched/fair.c:1116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
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
In kernel/sched/fair.c (ffffffff810f3acf)
Location: kernel/sched/fair.c:1113
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
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
In kernel/sched/fair.c (ffffffff8110d37c)
Location: kernel/sched/fair.c:1102
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
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
In kernel/sched/fair.c (ffffffff81128f82)
Location: kernel/sched/fair.c:1104
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
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
In kernel/sched/fair.c (ffffffff811529eb)
Location: kernel/sched/fair.c:1143
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
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
In kernel/sched/fair.c (ffffffff81162294)
Location: kernel/sched/fair.c:1160
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
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
In kernel/sched/fair.c (ffffffff8116ed64)
Location: kernel/sched/fair.c:1401
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_group
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
```
</details>
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
In kernel/sched/fair.c (ffff800010148e98)
Location: kernel/sched/fair.c:1098
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019ab0c)
Location: kernel/sched/fair.c:1098
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e308a)
Location: kernel/sched/fair.c:1098
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d219a)
Location: kernel/sched/fair.c:1098
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
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
In kernel/sched/fair.c (ffffffff810df40a)
Location: kernel/sched/fair.c:1098
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eaf74)
Location: kernel/sched/fair.c:1098
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
```
</details>
</li>
</ul>

## Differences
