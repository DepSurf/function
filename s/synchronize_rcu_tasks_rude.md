# Function: <code>synchronize_rcu_tasks_rude</code>

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
void synchronize_rcu_tasks_rude();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:659
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
```
**Symbols:**

```
ffffffff81130720-ffffffff8113076f: synchronize_rcu_tasks_rude (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks_rude();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:669
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
```
**Symbols:**

```
ffffffff8112c230-ffffffff8112c27f: synchronize_rcu_tasks_rude (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks_rude();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:669
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
```
**Symbols:**

```
ffffffff8112c760-ffffffff8112c7af: synchronize_rcu_tasks_rude (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks_rude();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:713
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
```
**Symbols:**

```
ffffffff8114d460-ffffffff8114d4af: synchronize_rcu_tasks_rude (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void synchronize_rcu_tasks_rude();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81173e80)
Location: kernel/rcu/tasks.h:1058
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
```
**Symbols:**

```
ffffffff81173e80-ffffffff81173eed: synchronize_rcu_tasks_rude (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void synchronize_rcu_tasks_rude();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811a9de0)
Location: kernel/rcu/tasks.h:1121
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
```
**Symbols:**

```
ffffffff811a9de0-ffffffff811a9dfd: synchronize_rcu_tasks_rude (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void synchronize_rcu_tasks_rude();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bbcd0)
Location: kernel/rcu/tasks.h:1158
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
```
**Symbols:**

```
ffffffff811bbcd0-ffffffff811bbced: synchronize_rcu_tasks_rude (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void synchronize_rcu_tasks_rude();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cc170)
Location: kernel/rcu/tasks.h:1262
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
```
**Symbols:**

```
ffffffff811cc170-ffffffff811cc18d: synchronize_rcu_tasks_rude (STB_GLOBAL)
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
