# Function: <code>atomic64_cmpxchg_acquire</code>

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
In kernel/locking/mutex.c (ffffffff8110e130)
Location: include/asm-generic/atomic-instrumented.h:1472
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (ffffffff8110b3f0)
Location: include/asm-generic/atomic-instrumented.h:1472
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
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
In kernel/locking/mutex.c (ffffffff81c34284)
Location: include/asm-generic/atomic-instrumented.h:1472
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da4214)
Location: include/asm-generic/atomic-instrumented.h:1471
Inline: True
Inline callers:
  - kernel/locking/mutex.c:ww_mutex_lock_interruptible
  - kernel/locking/mutex.c:ww_mutex_lock
  - kernel/locking/mutex.c:mutex_lock_killable
  - kernel/locking/mutex.c:mutex_lock_interruptible
  - kernel/locking/mutex.c:mutex_lock
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
```
In kernel/locking/rwsem.c (ffff800010168fe8)
Location: include/asm-generic/atomic-instrumented.h:1471
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:down_write_trylock
  - kernel/locking/rwsem.c:down_write_killable
  - kernel/locking/rwsem.c:down_write
  - kernel/locking/rwsem.c:down_read_trylock
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
</details>
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
