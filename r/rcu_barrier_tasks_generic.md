# Function: <code>rcu_barrier_tasks_generic</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_barrier_tasks_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81173130)
Location: kernel/rcu/tasks.h:351
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_trace
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff81173130-ffffffff8117332b: rcu_barrier_tasks_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_barrier_tasks_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811aadb0)
Location: kernel/rcu/tasks.h:348
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_trace
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff811aadb0-ffffffff811aafb5: rcu_barrier_tasks_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_barrier_tasks_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bcce0)
Location: kernel/rcu/tasks.h:357
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_trace
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff811bcce0-ffffffff811bced8: rcu_barrier_tasks_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_barrier_tasks_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cd100)
Location: kernel/rcu/tasks.h:397
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_trace
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff811cd100-ffffffff811cd2f8: rcu_barrier_tasks_generic (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
