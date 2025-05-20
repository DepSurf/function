# Function: <code>vclock_was_used</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff810041f3)
Location: arch/x86/include/asm/vgtod.h:41
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
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
In arch/x86/entry/vdso/vma.c (ffffffff81003f73)
Location: arch/x86/include/asm/vgtod.h:41
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
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
In arch/x86/entry/vdso/vma.c (ffffffff81003e94)
Location: arch/x86/include/asm/vgtod.h:41
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810040e4)
Location: arch/x86/include/asm/vgtod.h:42
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff8106bb10)
Location: arch/x86/include/asm/vgtod.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004884)
Location: arch/x86/include/asm/vgtod.h:42
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff8106e7c0)
Location: arch/x86/include/asm/vgtod.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff810047b2)
Location: arch/x86/include/asm/vgtod.h:55
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff810747e0)
Location: arch/x86/include/asm/vgtod.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff81004a4b)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff81078330)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff81004ac4)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff810793a0)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81005a53)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080680)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff81004a03)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff81080290)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff810049f3)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff81081130)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff81005023)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff810900d0)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff8100402c)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff810a1040)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff81004739)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff810b8ed0)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff81003ef9)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff810bc0a0)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff81006809)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff810c3220)
Location: arch/x86/include/asm/clocksource.h:11
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81004ac4)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff810783a0)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff810031a4)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff81067c50)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff81004a84)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff81078350)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
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
In arch/x86/entry/vdso/vma.c (ffffffff81004bc4)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vvar_fault
  - arch/x86/entry/vdso/vma.c:vvar_fault
```
```
In arch/x86/kernel/pvclock.c (ffffffff8107a450)
Location: arch/x86/include/asm/vgtod.h:19
Inline: True
Inline callers:
  - arch/x86/kernel/pvclock.c:pvclock_set_pvti_cpu0_va
```
</details>
</li>
</ul>

## Differences
