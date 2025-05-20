# Function: <code>arch_cpu_online</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81bbddf7)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe1a7)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81c366ec)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c36a97)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81c28b7c)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c28f47)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81d46d19)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d471c7)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81f15278)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f156d7)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
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
In arch/x86/kernel/nmi.c (ffffffff820bc708)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bcd07)
Location: arch/x86/include/asm/cpumask.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8213de77)
Location: arch/x86/include/asm/cpumask.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213e717)
Location: arch/x86/include/asm/cpumask.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8221fe76)
Location: arch/x86/include/asm/cpumask.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220707)
Location: arch/x86/include/asm/cpumask.h:14
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_check_crashing_cpu
```
</details>
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
