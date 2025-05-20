# Function: <code>load_too_imbalanced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool load_too_imbalanced(long int src_load, long int dst_load, struct task_numa_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b1ed0)
Location: kernel/sched/fair.c:1202
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810b1ed0-ffffffff810b1f50: load_too_imbalanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool load_too_imbalanced(long int src_load, long int dst_load, struct task_numa_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b4a10)
Location: kernel/sched/fair.c:1347
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810b4a10-ffffffff810b4a90: load_too_imbalanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool load_too_imbalanced(long int src_load, long int dst_load, struct task_numa_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810baff0)
Location: kernel/sched/fair.c:1471
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810baff0-ffffffff810bb070: load_too_imbalanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool load_too_imbalanced(long int src_load, long int dst_load, struct task_numa_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b58a0)
Location: kernel/sched/fair.c:1467
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810b58a0-ffffffff810b591e: load_too_imbalanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool load_too_imbalanced(long int src_load, long int dst_load, struct task_numa_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bcb80)
Location: kernel/sched/fair.c:1508
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810bcb80-ffffffff810bcbfe: load_too_imbalanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool load_too_imbalanced(long int src_load, long int dst_load, struct task_numa_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c48c0)
Location: kernel/sched/fair.c:1536
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810c48c0-ffffffff810c4932: load_too_imbalanced (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810d118f)
Location: kernel/sched/fair.c:1529
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810d93bd)
Location: kernel/sched/fair.c:1590
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810e3b25)
Location: kernel/sched/fair.c:1548
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810efbb0)
Location: kernel/sched/fair.c:1687
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
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
In kernel/sched/fair.c (ffffffff810edbc7)
Location: kernel/sched/fair.c:1700
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
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
In kernel/sched/fair.c (ffffffff810efbf4)
Location: kernel/sched/fair.c:1697
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
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
In kernel/sched/fair.c (ffffffff811085c0)
Location: kernel/sched/fair.c:1686
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
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
In kernel/sched/fair.c (ffffffff81123527)
Location: kernel/sched/fair.c:1689
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
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
In kernel/sched/fair.c (ffffffff8114b4a2)
Location: kernel/sched/fair.c:1875
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
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
In kernel/sched/fair.c (ffffffff8115d702)
Location: kernel/sched/fair.c:1875
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
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
In kernel/sched/fair.c (ffffffff81168a22)
Location: kernel/sched/fair.c:2116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
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
In kernel/sched/fair.c (ffff800010143bd0)
Location: kernel/sched/fair.c:1548
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (c000000000193214)
Location: kernel/sched/fair.c:1548
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810ddcd5)
Location: kernel/sched/fair.c:1548
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810ccce5)
Location: kernel/sched/fair.c:1548
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810da055)
Location: kernel/sched/fair.c:1548
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810e5791)
Location: kernel/sched/fair.c:1548
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_find_cpu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
