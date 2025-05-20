# Function: <code>rcu_tasks_trace_postscan</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_tasks_trace_postscan(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811311e0)
Location: kernel/rcu/tasks.h:962
Inline: False
```
**Symbols:**

```
ffffffff811311e0-ffffffff81131256: rcu_tasks_trace_postscan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_tasks_trace_postscan(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112cd10)
Location: kernel/rcu/tasks.h:984
Inline: False
```
**Symbols:**

```
ffffffff8112cd10-ffffffff8112cd8b: rcu_tasks_trace_postscan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_tasks_trace_postscan(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112d260)
Location: kernel/rcu/tasks.h:1018
Inline: False
```
**Symbols:**

```
ffffffff8112d260-ffffffff8112d2d0: rcu_tasks_trace_postscan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_tasks_trace_postscan(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114e040)
Location: kernel/rcu/tasks.h:1072
Inline: False
```
**Symbols:**

```
ffffffff8114e040-ffffffff8114e0e2: rcu_tasks_trace_postscan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_tasks_trace_postscan(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81174e90)
Location: kernel/rcu/tasks.h:1405
Inline: False
```
**Symbols:**

```
ffffffff81174e90-ffffffff81174f31: rcu_tasks_trace_postscan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_tasks_trace_postscan(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1563
Inline: False
```
**Symbols:**

```
ffffffff811a9f10-ffffffff811a9f24: rcu_tasks_trace_postscan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_tasks_trace_postscan(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1600
Inline: False
```
**Symbols:**

```
ffffffff811bbe40-ffffffff811bbe54: rcu_tasks_trace_postscan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_tasks_trace_postscan(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1716
Inline: False
```
**Symbols:**

```
ffffffff811cc2a0-ffffffff811cc2b4: rcu_tasks_trace_postscan (STB_LOCAL)
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
