# Function: <code>paravirt_arch_dup_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107ffd2)
Location: arch/x86/include/asm/paravirt.h:309
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810818f2)
Location: arch/x86/include/asm/paravirt.h:299
Inline: True
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
In kernel/fork.c (ffffffff810862e2)
Location: arch/x86/include/asm/paravirt.h:290
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
In kernel/fork.c (ffffffff810834c1)
Location: arch/x86/include/asm/paravirt.h:290
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
In kernel/fork.c (ffffffff81089dda)
Location: arch/x86/include/asm/paravirt.h:282
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
In kernel/fork.c (ffffffff8108bab5)
Location: arch/x86/include/asm/paravirt.h:282
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
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
In kernel/fork.c (ffffffff810958c8)
Location: arch/x86/include/asm/paravirt.h:320
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
In kernel/fork.c (ffffffff81097a9b)
Location: arch/x86/include/asm/paravirt.h:320
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
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
In kernel/fork.c (ffffffff8109e15b)
Location: arch/x86/include/asm/paravirt.h:308
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
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
In kernel/fork.c (ffffffff810a567f)
Location: arch/x86/include/asm/paravirt.h:322
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
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
In kernel/fork.c (ffffffff810a0dfb)
Location: arch/x86/include/asm/paravirt.h:318
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
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
In kernel/fork.c (ffffffff810a1b72)
Location: arch/x86/include/asm/paravirt.h:335
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
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
In kernel/fork.c (ffffffff810b3732)
Location: arch/x86/include/asm/paravirt.h:335
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
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
In kernel/fork.c (ffffffff810c9976)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff83e9a6cc)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - arch/x86/mm/init.c:poking_init
```
```
In kernel/fork.c (ffffffff810e717d)
Location: arch/x86/include/asm/paravirt.h:341
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097a7b)
Location: arch/x86/include/asm/paravirt.h:308
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
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
In kernel/fork.c (0)
Location: arch/x86/include/asm/paravirt.h:936
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
In kernel/fork.c (ffffffff81097a2b)
Location: arch/x86/include/asm/paravirt.h:308
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
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
In kernel/fork.c (ffffffff8109f62b)
Location: arch/x86/include/asm/paravirt.h:308
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
</details>
</li>
</ul>

## Differences
