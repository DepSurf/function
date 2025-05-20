# Function: <code>numa_group_count_active_nodes</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bdd96)
Location: kernel/sched/fair.c:1726
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810c32dc)
Location: kernel/sched/fair.c:1858
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810bdf20)
Location: kernel/sched/fair.c:1854
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810c5c10)
Location: kernel/sched/fair.c:1895
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810cd42b)
Location: kernel/sched/fair.c:1923
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810d6365)
Location: kernel/sched/fair.c:1872
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810d8b75)
Location: kernel/sched/fair.c:1937
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff810e3475)
Location: kernel/sched/fair.c:1895
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void numa_group_count_active_nodes(struct numa_group *numa_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8d20)
Location: kernel/sched/fair.c:2124
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810e8d20-ffffffff810e8e35: numa_group_count_active_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void numa_group_count_active_nodes(struct numa_group *numa_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6ab0)
Location: kernel/sched/fair.c:2138
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810e6ab0-ffffffff810e6bc5: numa_group_count_active_nodes (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810ee26d)
Location: kernel/sched/fair.c:2135
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff811052c5)
Location: kernel/sched/fair.c:2124
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff8111f0da)
Location: kernel/sched/fair.c:2129
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff81148472)
Location: kernel/sched/fair.c:2324
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff81158311)
Location: kernel/sched/fair.c:2324
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff81164558)
Location: kernel/sched/fair.c:2565
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffff800010147be0)
Location: kernel/sched/fair.c:1895
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (c000000000193ab4)
Location: kernel/sched/fair.c:1895
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff810dd625)
Location: kernel/sched/fair.c:1895
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff810cc635)
Location: kernel/sched/fair.c:1895
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff810d99a5)
Location: kernel/sched/fair.c:1895
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff810e53d5)
Location: kernel/sched/fair.c:1895
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
