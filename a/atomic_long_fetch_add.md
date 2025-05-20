# Function: <code>atomic_long_fetch_add</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d054a)
Location: include/asm-generic/atomic-long.h:124
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/rwsem-xadd.c (ffffffff810d6f1f)
Location: include/asm-generic/atomic-long.h:124
Inline: True
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
In kernel/locking/rwsem-xadd.c (ffffffff810d5f7f)
Location: include/asm-generic/atomic-long.h:124
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
In kernel/locking/rwsem-xadd.c (ffffffff810ddf3f)
Location: include/asm-generic/atomic-long.h:125
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
In kernel/locking/rwsem-xadd.c (ffffffff810e65c5)
Location: include/asm-generic/atomic-long.h:142
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
In kernel/locking/rwsem-xadd.c (ffffffff810f1b5c)
Location: include/asm-generic/atomic-long.h:142
Inline: True
Inline callers:
  - kernel/locking/rwsem-xadd.c:__rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff810f7b98)
Location: include/asm-generic/atomic-long.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff811039c8)
Location: include/asm-generic/atomic-long.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff8110e51f)
Location: include/asm-generic/atomic-long.h:81
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff8110b7af)
Location: include/asm-generic/atomic-long.h:81
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff8110d5cf)
Location: include/asm-generic/atomic-long.h:81
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff8112ce1f)
Location: include/linux/atomic/atomic-instrumented.h:1244
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff8114e0ee)
Location: include/linux/atomic/atomic-instrumented.h:1329
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff8117d06e)
Location: include/linux/atomic/atomic-instrumented.h:1329
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff8118dd1e)
Location: include/linux/atomic/atomic-instrumented.h:3322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff8119c6ce)
Location: include/linux/atomic/atomic-instrumented.h:3322
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffff80001016940c)
Location: include/asm-generic/atomic-long.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (c03b53ac)
Location: include/asm-generic/atomic-long.h:574
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (c0000000001c0bc0)
Location: include/asm-generic/atomic-long.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffe00010a8e6)
Location: include/asm-generic/atomic-long.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff810fccd8)
Location: include/asm-generic/atomic-long.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff810ecee8)
Location: include/asm-generic/atomic-long.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff810f9e98)
Location: include/asm-generic/atomic-long.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
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
In kernel/locking/rwsem.c (ffffffff81105008)
Location: include/asm-generic/atomic-long.h:80
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
</details>
</li>
</ul>

## Differences
