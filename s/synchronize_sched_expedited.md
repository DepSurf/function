# Function: <code>synchronize_sched_expedited</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void synchronize_sched_expedited();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e5030)
Location: kernel/rcu/tree.c:3844
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff810e5030-ffffffff810e58a4: synchronize_sched_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void synchronize_sched_expedited();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eb8e0)
Location: kernel/rcu/tree_exp.h:535
Inline: True
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff810eb300-ffffffff810eb34e: synchronize_sched_expedited.part.62 (STB_LOCAL)
ffffffff810eb8e0-ffffffff810ec452: synchronize_sched_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void synchronize_sched_expedited();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4cb0)
Location: kernel/rcu/tree_exp.h:622
Inline: True
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff810f4cb0-ffffffff810f4cdc: synchronize_sched_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void synchronize_sched_expedited();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f59f0)
Location: kernel/rcu/tree_exp.h:639
Inline: True
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff810f59f0-ffffffff810f5a1c: synchronize_sched_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void synchronize_sched_expedited();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ff7f0)
Location: kernel/rcu/tree_exp.h:639
Inline: True
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff810ff7f0-ffffffff810ff81c: synchronize_sched_expedited (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void synchronize_sched_expedited();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81107315)
Location: kernel/rcu/tree_exp.h:709
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81107200-ffffffff81107210: synchronize_sched_expedited.part.65 (STB_LOCAL)
ffffffff81107210-ffffffff8110723e: synchronize_sched_expedited (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
