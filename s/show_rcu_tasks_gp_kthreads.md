# Function: <code>show_rcu_tasks_gp_kthreads</code>

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
void show_rcu_tasks_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811315c6)
Location: kernel/rcu/tasks.h:1183
Inline: False
Direct callers:
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
```
**Symbols:**

```
ffffffff811315c6-ffffffff81131659: show_rcu_tasks_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_rcu_tasks_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81be1f13)
Location: kernel/rcu/tasks.h:1219
Inline: False
Direct callers:
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
```
**Symbols:**

```
ffffffff81be1f13-ffffffff81be1f28: show_rcu_tasks_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_rcu_tasks_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81bd3fa3)
Location: kernel/rcu/tasks.h:1253
Inline: False
Direct callers:
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
```
**Symbols:**

```
ffffffff81bd3fa3-ffffffff81bd3fb8: show_rcu_tasks_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void show_rcu_tasks_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1307
Inline: False
Direct callers:
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
```
**Symbols:**

```
ffffffff81cae07b-ffffffff81cae129: show_rcu_tasks_gp_kthreads.cold (STB_LOCAL)
ffffffff8114e420-ffffffff8114e5ab: show_rcu_tasks_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void show_rcu_tasks_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81175120)
Location: kernel/rcu/tasks.h:1676
Inline: False
Direct callers:
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
```
**Symbols:**

```
ffffffff81175120-ffffffff811751db: show_rcu_tasks_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void show_rcu_tasks_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811ac1e0)
Location: kernel/rcu/tasks.h:1801
Inline: False
Direct callers:
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
```
**Symbols:**

```
ffffffff811ac1e0-ffffffff811ac28d: show_rcu_tasks_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void show_rcu_tasks_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811be100)
Location: kernel/rcu/tasks.h:1838
Inline: False
Direct callers:
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
```
**Symbols:**

```
ffffffff811be100-ffffffff811be1ad: show_rcu_tasks_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_rcu_tasks_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811ce620)
Location: kernel/rcu/tasks.h:1965
Inline: False
Direct callers:
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
```
**Symbols:**

```
ffffffff811ce620-ffffffff811ce6cd: show_rcu_tasks_gp_kthreads (STB_GLOBAL)
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
