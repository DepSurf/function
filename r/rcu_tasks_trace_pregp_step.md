# Function: <code>rcu_tasks_trace_pregp_step</code>

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
void rcu_tasks_trace_pregp_step();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81130070)
Location: kernel/rcu/tasks.h:932
Inline: False
```
**Symbols:**

```
ffffffff81130070-ffffffff811300c8: rcu_tasks_trace_pregp_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_tasks_trace_pregp_step();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112beb0)
Location: kernel/rcu/tasks.h:949
Inline: False
```
**Symbols:**

```
ffffffff8112beb0-ffffffff8112bf08: rcu_tasks_trace_pregp_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_tasks_trace_pregp_step();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c340)
Location: kernel/rcu/tasks.h:983
Inline: False
```
**Symbols:**

```
ffffffff8112c340-ffffffff8112c39d: rcu_tasks_trace_pregp_step (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_tasks_trace_pregp_step();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1037
Inline: False
```
**Symbols:**

```
ffffffff8114d0a0-ffffffff8114d131: rcu_tasks_trace_pregp_step (STB_LOCAL)
ffffffff81cadf86-ffffffff81cadfa1: rcu_tasks_trace_pregp_step.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_tasks_trace_pregp_step();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1370
Inline: False
```
**Symbols:**

```
ffffffff81173ca0-ffffffff81173d42: rcu_tasks_trace_pregp_step (STB_LOCAL)
ffffffff81e5e5de-ffffffff81e5e5ff: rcu_tasks_trace_pregp_step.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rcu_tasks_trace_pregp_step(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1507
Inline: False
```
**Symbols:**

```
ffffffff811ab8b0-ffffffff811abd24: rcu_tasks_trace_pregp_step (STB_LOCAL)
ffffffff82059e6b-ffffffff82059e8f: rcu_tasks_trace_pregp_step.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rcu_tasks_trace_pregp_step(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1544
Inline: False
```
**Symbols:**

```
ffffffff811bd7d0-ffffffff811bdc44: rcu_tasks_trace_pregp_step (STB_LOCAL)
ffffffff820d8662-ffffffff820d8686: rcu_tasks_trace_pregp_step.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_tasks_trace_pregp_step(struct list_head *hop);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1660
Inline: False
```
**Symbols:**

```
ffffffff811cdcf0-ffffffff811ce164: rcu_tasks_trace_pregp_step (STB_LOCAL)
ffffffff821b392c-ffffffff821b3950: rcu_tasks_trace_pregp_step.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_head *hop</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
