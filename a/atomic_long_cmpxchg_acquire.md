# Function: <code>atomic_long_cmpxchg_acquire</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a999c4)
Location: include/asm-generic/atomic-long.h:416
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81103610)
Location: include/asm-generic/atomic-long.h:416
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
</details>
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
Location: include/asm-generic/atomic-long.h:417
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
Location: include/asm-generic/atomic-long.h:417
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
Location: include/asm-generic/atomic-long.h:417
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff8000101687dc)
Location: include/asm-generic/atomic-long.h:416
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c03b4ee8)
Location: include/asm-generic/atomic-long.h:910
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0000000001c05b0)
Location: include/asm-generic/atomic-long.h:416
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe00010a4e6)
Location: include/asm-generic/atomic-long.h:416
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810fc920)
Location: include/asm-generic/atomic-long.h:416
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810ecb30)
Location: include/asm-generic/atomic-long.h:416
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff810f9ae0)
Location: include/asm-generic/atomic-long.h:416
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81104c50)
Location: include/asm-generic/atomic-long.h:416
Inline: True
Inline callers:
  - kernel/locking/mutex.c:mutex_trylock_recursive
```
</details>
</li>
</ul>

## Differences
