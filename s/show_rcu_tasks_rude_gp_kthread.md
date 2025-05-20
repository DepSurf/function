# Function: <code>show_rcu_tasks_rude_gp_kthread</code>

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
In kernel/rcu/update.c (ffffffff811315f5)
Location: kernel/rcu/tasks.h:685
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_rcu_tasks_rude_gp_kthread();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81be1d96)
Location: kernel/rcu/tasks.h:696
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff81be1d96-ffffffff81be1db4: show_rcu_tasks_rude_gp_kthread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_rcu_tasks_rude_gp_kthread();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81bd3e22)
Location: kernel/rcu/tasks.h:696
Inline: False
Direct callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff81bd3e22-ffffffff81bd3e40: show_rcu_tasks_rude_gp_kthread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void show_rcu_tasks_rude_gp_kthread();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114e452)
Location: kernel/rcu/tasks.h:740
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff81cae04f-ffffffff81cae05b: show_rcu_tasks_rude_gp_kthread.cold (STB_LOCAL)
ffffffff8114e140-ffffffff8114e227: show_rcu_tasks_rude_gp_kthread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void show_rcu_tasks_rude_gp_kthread();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81175154)
Location: kernel/rcu/tasks.h:1085
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff81172cc0-ffffffff81172ce6: show_rcu_tasks_rude_gp_kthread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void show_rcu_tasks_rude_gp_kthread();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811ac214)
Location: kernel/rcu/tasks.h:1148
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff811aa730-ffffffff811aa756: show_rcu_tasks_rude_gp_kthread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void show_rcu_tasks_rude_gp_kthread();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811be134)
Location: kernel/rcu/tasks.h:1185
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff811bc670-ffffffff811bc696: show_rcu_tasks_rude_gp_kthread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void show_rcu_tasks_rude_gp_kthread();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811ce654)
Location: kernel/rcu/tasks.h:1294
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_gp_kthreads
```
**Symbols:**

```
ffffffff811ccd40-ffffffff811ccd66: show_rcu_tasks_rude_gp_kthread (STB_GLOBAL)
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
