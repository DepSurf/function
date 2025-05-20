# Function: <code>show_rcu_tasks_generic_gp_kthread</code>

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
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks *rtp, char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81131393)
Location: kernel/rcu/tasks.h:272
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff81131393-ffffffff8113144d: show_rcu_tasks_generic_gp_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks *rtp, char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81be1cdc)
Location: kernel/rcu/tasks.h:281
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_rcu_tasks_trace_gp_kthread
  - kernel/rcu/update.c:show_rcu_tasks_rude_gp_kthread
```
**Symbols:**

```
ffffffff81be1cdc-ffffffff81be1d96: show_rcu_tasks_generic_gp_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks *rtp, char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81bd3d93)
Location: kernel/rcu/tasks.h:281
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_rcu_tasks_trace_gp_kthread
  - kernel/rcu/update.c:show_rcu_tasks_rude_gp_kthread
```
**Symbols:**

```
ffffffff81bd3d93-ffffffff81bd3e22: show_rcu_tasks_generic_gp_kthread (STB_LOCAL)
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
In kernel/rcu/update.c (ffffffff8114e452)
Location: kernel/rcu/tasks.h:280
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks *rtp, char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:586
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff81172b20-ffffffff81172c90: show_rcu_tasks_generic_gp_kthread (STB_LOCAL)
ffffffff81e5e460-ffffffff81e5e46c: show_rcu_tasks_generic_gp_kthread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks *rtp, char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811aa570)
Location: kernel/rcu/tasks.h:622
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff811aa570-ffffffff811aa6d7: show_rcu_tasks_generic_gp_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks *rtp, char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bc4a0)
Location: kernel/rcu/tasks.h:634
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff811bc4a0-ffffffff811bc612: show_rcu_tasks_generic_gp_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_rcu_tasks_generic_gp_kthread(struct rcu_tasks *rtp, char *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cca10)
Location: kernel/rcu/tasks.h:692
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff811cca10-ffffffff811cccea: show_rcu_tasks_generic_gp_kthread (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
