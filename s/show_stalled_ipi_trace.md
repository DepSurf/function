# Function: <code>show_stalled_ipi_trace</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void show_stalled_ipi_trace();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1001
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
**Symbols:**

```
ffffffff81130020-ffffffff8113006f: show_stalled_ipi_trace (STB_LOCAL)
ffffffff811314eb-ffffffff811314ff: show_stalled_ipi_trace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void show_stalled_ipi_trace();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1023
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
**Symbols:**

```
ffffffff8112be60-ffffffff8112beaf: show_stalled_ipi_trace (STB_LOCAL)
ffffffff81be1ebf-ffffffff81be1ed3: show_stalled_ipi_trace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void show_stalled_ipi_trace();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1057
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
**Symbols:**

```
ffffffff8112c2f0-ffffffff8112c33f: show_stalled_ipi_trace (STB_LOCAL)
ffffffff81bd3f4b-ffffffff81bd3f5f: show_stalled_ipi_trace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void show_stalled_ipi_trace();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1111
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
**Symbols:**

```
ffffffff8114d020-ffffffff8114d09a: show_stalled_ipi_trace (STB_LOCAL)
ffffffff81cadf5e-ffffffff81cadf86: show_stalled_ipi_trace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void show_stalled_ipi_trace();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1469
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
```
**Symbols:**

```
ffffffff811735b0-ffffffff81173633: show_stalled_ipi_trace (STB_LOCAL)
ffffffff81e5e4e9-ffffffff81e5e511: show_stalled_ipi_trace.cold (STB_LOCAL)
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
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1625
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
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1662
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
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1778
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
