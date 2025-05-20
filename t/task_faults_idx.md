# Function: <code>task_faults_idx</code>

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
In kernel/sched/fair.c (ffffffff810b30bc)
Location: kernel/sched/fair.c:916
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2782)
Location: kernel/sched/fair.c:1051
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c8807)
Location: kernel/sched/fair.c:1175
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
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
In kernel/sched/fair.c (ffffffff810c2a38)
Location: kernel/sched/fair.c:1172
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
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
In kernel/sched/fair.c (ffffffff810ca228)
Location: kernel/sched/fair.c:1189
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff810d21e8)
Location: kernel/sched/fair.c:1217
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dbb58)
Location: kernel/sched/fair.c:1213
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2add)
Location: kernel/sched/fair.c:1273
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff810ed18d)
Location: kernel/sched/fair.c:1231
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff810f70a1)
Location: kernel/sched/fair.c:1242
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff810f52c1)
Location: kernel/sched/fair.c:1249
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff810f7397)
Location: kernel/sched/fair.c:1246
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff81111907)
Location: kernel/sched/fair.c:1235
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff8112db86)
Location: kernel/sched/fair.c:1237
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff81157986)
Location: kernel/sched/fair.c:1276
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff811679d6)
Location: kernel/sched/fair.c:1293
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff811747d6)
Location: kernel/sched/fair.c:1534
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffff80001014d828)
Location: kernel/sched/fair.c:1231
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (c0000000001a07c0)
Location: kernel/sched/fair.c:1231
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff810e72ed)
Location: kernel/sched/fair.c:1231
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff810d648d)
Location: kernel/sched/fair.c:1231
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff810e36bd)
Location: kernel/sched/fair.c:1231
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
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
In kernel/sched/fair.c (ffffffff810ef2a5)
Location: kernel/sched/fair.c:1231
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
</details>
</li>
</ul>

## Differences
