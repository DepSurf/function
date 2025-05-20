# Function: <code>task_rcu_dereference</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *task_rcu_dereference(struct task_struct **ptask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810866e0)
Location: kernel/exit.c:217
Inline: False
Direct callers:
  - kernel/exit.c:try_get_task_struct
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810866e0-ffffffff81086754: task_rcu_dereference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *task_rcu_dereference(struct task_struct **ptask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108b650)
Location: kernel/exit.c:226
Inline: False
Direct callers:
  - kernel/exit.c:try_get_task_struct
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff8108b650-ffffffff8108b6c4: task_rcu_dereference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *task_rcu_dereference(struct task_struct **ptask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810887d0)
Location: kernel/exit.c:233
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
```
**Symbols:**

```
ffffffff810887d0-ffffffff81088844: task_rcu_dereference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *task_rcu_dereference(struct task_struct **ptask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108f500)
Location: kernel/exit.c:233
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/membarrier.c:SyS_membarrier
```
**Symbols:**

```
ffffffff8108f500-ffffffff8108f574: task_rcu_dereference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *task_rcu_dereference(struct task_struct **ptask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff81093090)
Location: kernel/exit.c:233
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
**Symbols:**

```
ffffffff81093090-ffffffff81093101: task_rcu_dereference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *task_rcu_dereference(struct task_struct **ptask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109b340)
Location: kernel/exit.c:234
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
**Symbols:**

```
ffffffff8109b340-ffffffff8109b3b1: task_rcu_dereference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *task_rcu_dereference(struct task_struct **ptask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f990)
Location: kernel/exit.c:236
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/membarrier.c:membarrier_global_expedited
```
**Symbols:**

```
ffffffff8109f990-ffffffff8109fa00: task_rcu_dereference (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
