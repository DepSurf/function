# Function: <code>synchronize_rcu_tasks_generic</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:163
Inline: True
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
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:171
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
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
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:171
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
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
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:171
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
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
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:327
Inline: True
Inline callers:
  - kernel/rcu/update.c:synchronize_rcu_tasks_trace
  - kernel/rcu/update.c:synchronize_rcu_tasks_rude
  - kernel/rcu/update.c:synchronize_rcu_tasks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void synchronize_rcu_tasks_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:563
Inline: False
Direct callers:
  - kernel/rcu/update.c:synchronize_rcu_tasks_trace
  - kernel/rcu/update.c:synchronize_rcu_tasks_rude
  - kernel/rcu/update.c:synchronize_rcu_tasks
```
**Symbols:**

```
ffffffff811a9cc0-ffffffff811a9d94: synchronize_rcu_tasks_generic (STB_LOCAL)
ffffffff82059d53-ffffffff82059d70: synchronize_rcu_tasks_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void synchronize_rcu_tasks_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:575
Inline: False
Direct callers:
  - kernel/rcu/update.c:synchronize_rcu_tasks_trace
  - kernel/rcu/update.c:synchronize_rcu_tasks_rude
  - kernel/rcu/update.c:synchronize_rcu_tasks
```
**Symbols:**

```
ffffffff811bbbb0-ffffffff811bbc81: synchronize_rcu_tasks_generic (STB_LOCAL)
ffffffff820d8534-ffffffff820d8549: synchronize_rcu_tasks_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void synchronize_rcu_tasks_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:633
Inline: False
Direct callers:
  - kernel/rcu/update.c:synchronize_rcu_tasks_trace
  - kernel/rcu/update.c:synchronize_rcu_tasks_rude
  - kernel/rcu/update.c:synchronize_rcu_tasks
```
**Symbols:**

```
ffffffff811cc050-ffffffff811cc121: synchronize_rcu_tasks_generic (STB_LOCAL)
ffffffff821b37ea-ffffffff821b37ff: synchronize_rcu_tasks_generic.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
