# Function: <code>rcu_barrier_tasks_trace</code>

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
void rcu_barrier_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1148
Inline: False
```
**Symbols:**

```
ffffffff81130590-ffffffff811305df: rcu_barrier_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_barrier_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1171
Inline: False
```
**Symbols:**

```
ffffffff8112c440-ffffffff8112c48f: rcu_barrier_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_barrier_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1205
Inline: False
```
**Symbols:**

```
ffffffff8112c9c0-ffffffff8112ca0f: rcu_barrier_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_barrier_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:1259
Inline: False
```
**Symbols:**

```
ffffffff8114d670-ffffffff8114d6bf: rcu_barrier_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_barrier_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81173370)
Location: kernel/rcu/tasks.h:1628
Inline: False
```
**Symbols:**

```
ffffffff81173370-ffffffff8117338d: rcu_barrier_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_barrier_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811ab030)
Location: kernel/rcu/tasks.h:1753
Inline: False
Direct callers:
  - kernel/bpf/memalloc.c:free_mem_alloc_deferred
```
**Symbols:**

```
ffffffff811ab030-ffffffff811ab04d: rcu_barrier_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_barrier_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bcf50)
Location: kernel/rcu/tasks.h:1790
Inline: False
Direct callers:
  - kernel/bpf/memalloc.c:free_mem_alloc_deferred
```
**Symbols:**

```
ffffffff811bcf50-ffffffff811bcf6d: rcu_barrier_tasks_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_barrier_tasks_trace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cd370)
Location: kernel/rcu/tasks.h:1906
Inline: False
Direct callers:
  - kernel/bpf/memalloc.c:destroy_mem_alloc
  - kernel/bpf/memalloc.c:free_mem_alloc_deferred
```
**Symbols:**

```
ffffffff811cd370-ffffffff811cd38d: rcu_barrier_tasks_trace (STB_GLOBAL)
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
