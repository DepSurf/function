# Function: <code>task_numa_assign</code>

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
In kernel/sched/fair.c (ffffffff810b58fa)
Location: kernel/sched/fair.c:1191
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
In kernel/sched/fair.c (ffffffff810b7eb8)
Location: kernel/sched/fair.c:1334
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
In kernel/sched/fair.c (ffffffff810bea68)
Location: kernel/sched/fair.c:1458
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
In kernel/sched/fair.c (ffffffff810b929b)
Location: kernel/sched/fair.c:1454
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
In kernel/sched/fair.c (ffffffff810c1363)
Location: kernel/sched/fair.c:1495
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
In kernel/sched/fair.c (ffffffff810c828d)
Location: kernel/sched/fair.c:1523
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
In kernel/sched/fair.c (ffffffff810d14f8)
Location: kernel/sched/fair.c:1501
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
In kernel/sched/fair.c (ffffffff810d9450)
Location: kernel/sched/fair.c:1562
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
In kernel/sched/fair.c (ffffffff810e3bbd)
Location: kernel/sched/fair.c:1520
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
void task_numa_assign(struct task_numa_env *env, struct task_struct *p, long int imp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb950)
Location: kernel/sched/fair.c:1640
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff810eb950-ffffffff810ebb20: task_numa_assign (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void task_numa_assign(struct task_numa_env *env, struct task_struct *p, long int imp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9770)
Location: kernel/sched/fair.c:1653
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff810e9770-ffffffff810e9949: task_numa_assign (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void task_numa_assign(struct task_numa_env *env, struct task_struct *p, long int imp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea040)
Location: kernel/sched/fair.c:1650
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff810ea040-ffffffff810ea216: task_numa_assign (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void task_numa_assign(struct task_numa_env *env, struct task_struct *p, long int imp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811017b0)
Location: kernel/sched/fair.c:1639
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff811017b0-ffffffff81101a57: task_numa_assign (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void task_numa_assign(struct task_numa_env *env, struct task_struct *p, long int imp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111bcd0)
Location: kernel/sched/fair.c:1642
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff8111bcd0-ffffffff8111bf85: task_numa_assign (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void task_numa_assign(struct task_numa_env *env, struct task_struct *p, long int imp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811451e0)
Location: kernel/sched/fair.c:1828
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff811451e0-ffffffff81145527: task_numa_assign (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void task_numa_assign(struct task_numa_env *env, struct task_struct *p, long int imp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811556f0)
Location: kernel/sched/fair.c:1828
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff811556f0-ffffffff81155a41: task_numa_assign (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void task_numa_assign(struct task_numa_env *env, struct task_struct *p, long int imp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81163340)
Location: kernel/sched/fair.c:2069
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
```
**Symbols:**

```
ffffffff81163340-ffffffff81163691: task_numa_assign (STB_LOCAL)
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
In kernel/sched/fair.c (ffff800010143c94)
Location: kernel/sched/fair.c:1520
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
In kernel/sched/fair.c (c000000000193338)
Location: kernel/sched/fair.c:1520
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
In kernel/sched/fair.c (ffffffff810ddd6d)
Location: kernel/sched/fair.c:1520
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
In kernel/sched/fair.c (ffffffff810ccd71)
Location: kernel/sched/fair.c:1520
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
In kernel/sched/fair.c (ffffffff810da0ed)
Location: kernel/sched/fair.c:1520
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
In kernel/sched/fair.c (ffffffff810e5b14)
Location: kernel/sched/fair.c:1520
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
