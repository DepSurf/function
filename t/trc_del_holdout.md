# Function: <code>trc_del_holdout</code>

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
void trc_del_holdout(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81131147)
Location: kernel/rcu/tasks.h:783
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:trc_inspect_reader
```
**Symbols:**

```
ffffffff811308a0-ffffffff8113090f: trc_del_holdout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trc_del_holdout(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c5b0)
Location: kernel/rcu/tasks.h:793
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:trc_inspect_reader
  - kernel/rcu/update.c:trc_inspect_reader
```
**Symbols:**

```
ffffffff8112c5b0-ffffffff8112c61f: trc_del_holdout (STB_LOCAL)
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
In kernel/rcu/update.c (ffffffff8112cdc9)
Location: kernel/rcu/tasks.h:829
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
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
In kernel/rcu/update.c (ffffffff8114da91)
Location: kernel/rcu/tasks.h:876
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
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
In kernel/rcu/update.c (ffffffff81174816)
Location: kernel/rcu/tasks.h:1221
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
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
In kernel/rcu/update.c (ffffffff811ab46a)
Location: kernel/rcu/tasks.h:1332
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
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
In kernel/rcu/update.c (ffffffff811bd38a)
Location: kernel/rcu/tasks.h:1369
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
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
In kernel/rcu/update.c (ffffffff811cd9cf)
Location: kernel/rcu/tasks.h:1485
Inline: True
Inline callers:
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
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
</ul>
