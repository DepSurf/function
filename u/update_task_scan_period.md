# Function: <code>update_task_scan_period</code>

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
In kernel/sched/fair.c (ffffffff810baac8)
Location: kernel/sched/fair.c:1650
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810bdd4e)
Location: kernel/sched/fair.c:1763
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
In kernel/sched/fair.c (ffffffff810c3294)
Location: kernel/sched/fair.c:1895
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
In kernel/sched/fair.c (ffffffff810bdebb)
Location: kernel/sched/fair.c:1891
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
In kernel/sched/fair.c (ffffffff810c5bab)
Location: kernel/sched/fair.c:1932
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
In kernel/sched/fair.c (ffffffff810cda6a)
Location: kernel/sched/fair.c:1960
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
In kernel/sched/fair.c (ffffffff810d64ae)
Location: kernel/sched/fair.c:1909
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
In kernel/sched/fair.c (ffffffff810d8cb3)
Location: kernel/sched/fair.c:1974
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
In kernel/sched/fair.c (ffffffff810e35b3)
Location: kernel/sched/fair.c:1932
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff810ecb01)
Location: kernel/sched/fair.c:2161
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff810ea901)
Location: kernel/sched/fair.c:2175
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
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
In kernel/sched/fair.c (ffffffff810ee39d)
Location: kernel/sched/fair.c:2172
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
In kernel/sched/fair.c (ffffffff811053f9)
Location: kernel/sched/fair.c:2161
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_task_scan_period(struct task_struct *p, long unsigned int shared, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111c3e0)
Location: kernel/sched/fair.c:2166
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff8111c3e0-ffffffff8111c595: update_task_scan_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_task_scan_period(struct task_struct *p, long unsigned int shared, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81143f20)
Location: kernel/sched/fair.c:2361
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff81143f20-ffffffff811440d7: update_task_scan_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void update_task_scan_period(struct task_struct *p, long unsigned int shared, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81153ec0)
Location: kernel/sched/fair.c:2361
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff81153ec0-ffffffff81154072: update_task_scan_period (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_task_scan_period(struct task_struct *p, long unsigned int shared, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81160010)
Location: kernel/sched/fair.c:2602
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff81160010-ffffffff811601c2: update_task_scan_period (STB_LOCAL)
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
In kernel/sched/fair.c (ffff800010147950)
Location: kernel/sched/fair.c:1932
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
In kernel/sched/fair.c (c000000000193f0c)
Location: kernel/sched/fair.c:1932
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
In kernel/sched/fair.c (ffffffff810dd763)
Location: kernel/sched/fair.c:1932
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
In kernel/sched/fair.c (ffffffff810cc76d)
Location: kernel/sched/fair.c:1932
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
In kernel/sched/fair.c (ffffffff810d9ae3)
Location: kernel/sched/fair.c:1932
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
In kernel/sched/fair.c (ffffffff810e550a)
Location: kernel/sched/fair.c:1932
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
