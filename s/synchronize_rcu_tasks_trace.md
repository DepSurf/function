# Function: <code>synchronize_rcu_tasks_trace</code>

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
void synchronize_rcu_tasks_trace();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81130630)
Location: kernel/rcu/tasks.h:1135
Inline: True
```
**Symbols:**

```
ffffffff81130630-ffffffff8113067f: synchronize_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks_trace();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c4e0)
Location: kernel/rcu/tasks.h:1158
Inline: True
```
**Symbols:**

```
ffffffff8112c4e0-ffffffff8112c52f: synchronize_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks_trace();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112ca10)
Location: kernel/rcu/tasks.h:1192
Inline: True
```
**Symbols:**

```
ffffffff8112ca10-ffffffff8112ca5f: synchronize_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void synchronize_rcu_tasks_trace();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114d710)
Location: kernel/rcu/tasks.h:1246
Inline: True
```
**Symbols:**

```
ffffffff8114d710-ffffffff8114d75f: synchronize_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void synchronize_rcu_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81174350)
Location: kernel/rcu/tasks.h:1615
Inline: False
```
**Symbols:**

```
ffffffff81174350-ffffffff811743bd: synchronize_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void synchronize_rcu_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811a9e10)
Location: kernel/rcu/tasks.h:1740
Inline: False
```
**Symbols:**

```
ffffffff811a9e10-ffffffff811a9e2d: synchronize_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void synchronize_rcu_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bbd00)
Location: kernel/rcu/tasks.h:1777
Inline: False
```
**Symbols:**

```
ffffffff811bbd00-ffffffff811bbd1d: synchronize_rcu_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void synchronize_rcu_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cc1a0)
Location: kernel/rcu/tasks.h:1893
Inline: False
```
**Symbols:**

```
ffffffff811cc1a0-ffffffff811cc1bd: synchronize_rcu_tasks_trace (STB_GLOBAL)
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
