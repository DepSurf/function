# Function: <code>rcu_tasks_trace_pertask</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_tasks_trace_pertask(struct task_struct *t, struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81131221)
Location: kernel/rcu/tasks.h:949
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
```
**Symbols:**

```
ffffffff81131260-ffffffff81131294: rcu_tasks_trace_pertask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rcu_tasks_trace_pertask(struct task_struct *t, struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112cd4a)
Location: kernel/rcu/tasks.h:966
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
```
**Symbols:**

```
ffffffff8112ccd0-ffffffff8112cd09: rcu_tasks_trace_pertask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_tasks_trace_pertask(struct task_struct *t, struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112d282)
Location: kernel/rcu/tasks.h:1000
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
```
**Symbols:**

```
ffffffff8112d2d0-ffffffff8112d32b: rcu_tasks_trace_pertask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_tasks_trace_pertask(struct task_struct *t, struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114e085)
Location: kernel/rcu/tasks.h:1054
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
```
**Symbols:**

```
ffffffff8114e0f0-ffffffff8114e140: rcu_tasks_trace_pertask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rcu_tasks_trace_pertask(struct task_struct *t, struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81174ece)
Location: kernel/rcu/tasks.h:1387
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postscan
```
**Symbols:**

```
ffffffff81174f40-ffffffff81174fb9: rcu_tasks_trace_pertask (STB_LOCAL)
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
In kernel/rcu/update.c (ffffffff811abbcb)
Location: kernel/rcu/tasks.h:1500
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
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
In kernel/rcu/update.c (ffffffff811bdaeb)
Location: kernel/rcu/tasks.h:1537
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
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
In kernel/rcu/update.c (ffffffff811ce00b)
Location: kernel/rcu/tasks.h:1653
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
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
</ul>
