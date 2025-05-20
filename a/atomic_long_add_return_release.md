# Function: <code>atomic_long_add_return_release</code>

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
In kernel/locking/rwsem.c (ffffffff810f7f15)
Location: include/asm-generic/atomic-long.h:68
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff81103d45)
Location: include/asm-generic/atomic-long.h:68
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (0)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (0)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (0)
Location: include/asm-generic/atomic-long.h:69
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8112d1d5)
Location: include/linux/atomic/atomic-instrumented.h:1230
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8114e4f5)
Location: include/linux/atomic/atomic-instrumented.h:1314
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8117d4e0)
Location: include/linux/atomic/atomic-instrumented.h:1314
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8118e1c0)
Location: include/linux/atomic/atomic-instrumented.h:3285
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem.c (ffffffff8119cb70)
Location: include/linux/atomic/atomic-instrumented.h:3285
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
</details>
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
In kernel/locking/rwsem.c (ffff8000101697f0)
Location: include/asm-generic/atomic-long.h:68
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (c03b5854)
Location: include/asm-generic/atomic-long.h:562
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (c0000000001c10f0)
Location: include/asm-generic/atomic-long.h:68
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffe00010abca)
Location: include/asm-generic/atomic-long.h:68
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff810fd055)
Location: include/asm-generic/atomic-long.h:68
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff810ed265)
Location: include/asm-generic/atomic-long.h:68
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff810fa215)
Location: include/asm-generic/atomic-long.h:68
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
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
In kernel/locking/rwsem.c (ffffffff81105385)
Location: include/asm-generic/atomic-long.h:68
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
```
</details>
</li>
</ul>

## Differences
