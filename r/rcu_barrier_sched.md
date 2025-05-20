# Function: <code>rcu_barrier_sched</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e4cb6)
Location: kernel/rcu/tree.c:4116
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_barrier
```
**Symbols:**

```
ffffffff810e4cd0-ffffffff810e4ce0: rcu_barrier_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eb056)
Location: kernel/rcu/tree.c:3710
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_barrier
```
**Symbols:**

```
ffffffff810eb070-ffffffff810eb080: rcu_barrier_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2a16)
Location: kernel/rcu/tree.c:3708
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_barrier
```
**Symbols:**

```
ffffffff810f2a30-ffffffff810f2a40: rcu_barrier_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4676)
Location: kernel/rcu/tree.c:3697
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_barrier
```
**Symbols:**

```
ffffffff810f4690-ffffffff810f46a0: rcu_barrier_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fe546)
Location: kernel/rcu/tree.c:3683
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_barrier
```
**Symbols:**

```
ffffffff810fe560-ffffffff810fe570: rcu_barrier_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rcu_barrier_sched();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81105475)
Location: kernel/rcu/tree.c:3472
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_barrier
Direct callers:
  - init/main.c:kernel_init
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff81105490-ffffffff811054a0: rcu_barrier_sched (STB_GLOBAL)
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
