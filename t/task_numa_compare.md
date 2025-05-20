# Function: <code>task_numa_compare</code>

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
In kernel/sched/fair.c (ffffffff810b5616)
Location: kernel/sched/fair.c:1252
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810b7c26)
Location: kernel/sched/fair.c:1397
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810be7d6)
Location: kernel/sched/fair.c:1521
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810b8fd6)
Location: kernel/sched/fair.c:1517
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810c10ed)
Location: kernel/sched/fair.c:1558
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810c8045)
Location: kernel/sched/fair.c:1586
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
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
In kernel/sched/fair.c (ffffffff810d1218)
Location: kernel/sched/fair.c:1570
Inline: True
Inline callers:
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
In kernel/sched/fair.c (ffffffff810d9163)
Location: kernel/sched/fair.c:1631
Inline: True
Inline callers:
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
In kernel/sched/fair.c (ffffffff810e38d3)
Location: kernel/sched/fair.c:1589
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool task_numa_compare(struct task_numa_env *env, long int taskimp, long int groupimp, bool maymove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ef3b0)
Location: kernel/sched/fair.c:1728
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810ef3b0-ffffffff810efaa4: task_numa_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool task_numa_compare(struct task_numa_env *env, long int taskimp, long int groupimp, bool maymove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ed390)
Location: kernel/sched/fair.c:1741
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810ed390-ffffffff810edaa6: task_numa_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool task_numa_compare(struct task_numa_env *env, long int taskimp, long int groupimp, bool maymove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ef460)
Location: kernel/sched/fair.c:1738
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810ef460-ffffffff810efb01: task_numa_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool task_numa_compare(struct task_numa_env *env, long int taskimp, long int groupimp, bool maymove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81107de0)
Location: kernel/sched/fair.c:1727
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff81107de0-ffffffff811084b1: task_numa_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool task_numa_compare(struct task_numa_env *env, long int taskimp, long int groupimp, bool maymove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81122cd0)
Location: kernel/sched/fair.c:1730
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff81122cd0-ffffffff811233e7: task_numa_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool task_numa_compare(struct task_numa_env *env, long int taskimp, long int groupimp, bool maymove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114ac20)
Location: kernel/sched/fair.c:1916
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff8114ac20-ffffffff8114b34d: task_numa_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool task_numa_compare(struct task_numa_env *env, long int taskimp, long int groupimp, bool maymove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115ce80)
Location: kernel/sched/fair.c:1916
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff8115ce80-ffffffff8115d5ad: task_numa_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool task_numa_compare(struct task_numa_env *env, long int taskimp, long int groupimp, bool maymove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811681a0)
Location: kernel/sched/fair.c:2157
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff811681a0-ffffffff811688cd: task_numa_compare (STB_LOCAL)
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
In kernel/sched/fair.c (ffff80001014398c)
Location: kernel/sched/fair.c:1589
Inline: True
Inline callers:
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
In kernel/sched/fair.c (c000000000192fb8)
Location: kernel/sched/fair.c:1589
Inline: True
Inline callers:
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
In kernel/sched/fair.c (ffffffff810dda83)
Location: kernel/sched/fair.c:1589
Inline: True
Inline callers:
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
In kernel/sched/fair.c (ffffffff810cca93)
Location: kernel/sched/fair.c:1589
Inline: True
Inline callers:
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
In kernel/sched/fair.c (ffffffff810d9e03)
Location: kernel/sched/fair.c:1589
Inline: True
Inline callers:
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
In kernel/sched/fair.c (ffffffff810e582a)
Location: kernel/sched/fair.c:1589
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_find_cpu
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
