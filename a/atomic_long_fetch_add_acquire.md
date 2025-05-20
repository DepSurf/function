# Function: <code>atomic_long_fetch_add_acquire</code>

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
In kernel/locking/rwsem.c (ffffffff81a9b2af)
Location: include/asm-generic/atomic-long.h:86
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
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
In kernel/locking/rwsem.c (ffffffff81ad2bff)
Location: include/asm-generic/atomic-long.h:86
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
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
In kernel/locking/rwsem.c (ffffffff81bcac50)
Location: include/asm-generic/atomic-long.h:87
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffff800010da5104)
Location: include/asm-generic/atomic-long.h:86
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
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
In kernel/locking/rwsem.c (c0e9d34c)
Location: include/asm-generic/atomic-long.h:580
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
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
In kernel/locking/rwsem.c (c000000000ee79ac)
Location: include/asm-generic/atomic-long.h:86
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/locking/rwsem.c (ffffffff81a71a6f)
Location: include/asm-generic/atomic-long.h:86
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
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
In kernel/locking/rwsem.c (ffffffff81a2de47)
Location: include/asm-generic/atomic-long.h:86
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
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
In kernel/locking/rwsem.c (ffffffff81adde7f)
Location: include/asm-generic/atomic-long.h:86
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
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
In kernel/locking/rwsem.c (ffffffff81aea45b)
Location: include/asm-generic/atomic-long.h:86
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_optimistic_spin
```
</details>
</li>
</ul>

## Differences
