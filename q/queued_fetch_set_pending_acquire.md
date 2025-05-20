# Function: <code>queued_fetch_set_pending_acquire</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810f0947)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810f8c67)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff81104a77)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff8110f9e8)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff8110cba8)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff8110e89b)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff8112e074)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff8114f0d5)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff820d63db)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
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
In kernel/locking/qspinlock.c (ffffffff821597bb)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
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
In kernel/locking/qspinlock.c (ffffffff8223d03b)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:native_queued_spin_lock_slowpath
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
In kernel/locking/qspinlock.c (ffff80001016a9cc)
Location: kernel/locking/qspinlock.c:248
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810fdd87)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff810edf87)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff810faf47)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
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
In kernel/locking/qspinlock.c (ffffffff81106117)
Location: arch/x86/include/asm/qspinlock.h:14
Inline: True
```
</details>
</li>
</ul>

## Differences
