# Function: <code>atomic64_and</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818d1748)
Location: arch/x86/include/asm/atomic64_64.h:259
Inline: True
Inline callers:
  - kernel/locking/mutex.c:__ww_mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__ww_mutex_lock_slowpath
  - kernel/locking/mutex.c:__mutex_lock_interruptible_slowpath
  - kernel/locking/mutex.c:__mutex_lock_killable_slowpath
  - kernel/locking/mutex.c:__mutex_lock_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81907dd9)
Location: arch/x86/include/asm/atomic64_64.h:251
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81991e98)
Location: arch/x86/include/asm/atomic64_64.h:230
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819ee7e6)
Location: include/asm-generic/atomic-instrumented.h:154
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a29a46)
Location: include/asm-generic/atomic-instrumented.h:171
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a9a100)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810f7f3c)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad1a50)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff81103d6c)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee5944)
Location: arch/powerpc/include/asm/atomic.h:384
Inline: True
```
```
In kernel/locking/rwsem.c (c0000000001c1128)
Location: arch/powerpc/include/asm/atomic.h:384
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c6fba)
Location: arch/riscv/include/asm/atomic.h:78
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffe00010afb8)
Location: arch/riscv/include/asm/atomic.h:78
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
```
In mm/memory.c (ffffffe00020a000)
Location: arch/riscv/include/asm/atomic.h:78
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/hugetlb.c (ffffffe00023133e)
Location: arch/riscv/include/asm/atomic.h:78
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a708c0)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810fd07c)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2ccb0)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810ed28c)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81adccd0)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff810fa23c)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae8e90)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
```
```
In kernel/locking/rwsem.c (ffffffff811053ac)
Location: include/asm-generic/atomic-instrumented.h:1226
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
</li>
</ul>

## Differences
