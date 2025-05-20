# Function: <code>readers_active_check</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff810d5760)
Location: kernel/locking/percpu-rwsem.c:126
Inline: True
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
**Symbols:**

```
ffffffff810d5760-ffffffff810d57cc: readers_active_check.isra.2 (STB_LOCAL)
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
In kernel/locking/percpu-rwsem.c (ffffffff810d4751)
Location: kernel/locking/percpu-rwsem.c:125
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff810dc6d2)
Location: kernel/locking/percpu-rwsem.c:125
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff810e4d57)
Location: kernel/locking/percpu-rwsem.c:125
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff810f0337)
Location: kernel/locking/percpu-rwsem.c:125
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff810f8998)
Location: kernel/locking/percpu-rwsem.c:128
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff811047c1)
Location: kernel/locking/percpu-rwsem.c:128
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff8110f42e)
Location: kernel/locking/percpu-rwsem.c:199
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff8110c5ee)
Location: kernel/locking/percpu-rwsem.c:199
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff8110e427)
Location: kernel/locking/percpu-rwsem.c:199
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff8112db49)
Location: kernel/locking/percpu-rwsem.c:199
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff81f25e1e)
Location: kernel/locking/percpu-rwsem.c:203
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff820d1895)
Location: kernel/locking/percpu-rwsem.c:209
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff82155c05)
Location: kernel/locking/percpu-rwsem.c:209
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff82238a45)
Location: kernel/locking/percpu-rwsem.c:209
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffff80001016a3b0)
Location: kernel/locking/percpu-rwsem.c:128
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (c03b6358)
Location: kernel/locking/percpu-rwsem.c:128
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (c0000000001c1f98)
Location: kernel/locking/percpu-rwsem.c:128
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffe00010b1b2)
Location: kernel/locking/percpu-rwsem.c:128
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff810fdad1)
Location: kernel/locking/percpu-rwsem.c:128
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff810edcd1)
Location: kernel/locking/percpu-rwsem.c:128
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff810fac91)
Location: kernel/locking/percpu-rwsem.c:128
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
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
In kernel/locking/percpu-rwsem.c (ffffffff81105e61)
Location: kernel/locking/percpu-rwsem.c:128
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_down_write
```
</details>
</li>
</ul>

## Differences
