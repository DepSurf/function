# Function: <code>get_stack_guard_info</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81d45be6)
Location: arch/x86/include/asm/stacktrace.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/mm/fault.c (ffffffff81097947)
Location: arch/x86/include/asm/stacktrace.h:42
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
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
In arch/x86/kernel/traps.c (ffffffff81f13ee1)
Location: arch/x86/include/asm/stacktrace.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/mm/fault.c (ffffffff810aa4b5)
Location: arch/x86/include/asm/stacktrace.h:42
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
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
In arch/x86/kernel/traps.c (ffffffff820bb0bc)
Location: arch/x86/include/asm/stacktrace.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/mm/fault.c (ffffffff810c3fcd)
Location: arch/x86/include/asm/stacktrace.h:42
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
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
In arch/x86/kernel/traps.c (ffffffff8213c7dc)
Location: arch/x86/include/asm/stacktrace.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/mm/fault.c (ffffffff810c780d)
Location: arch/x86/include/asm/stacktrace.h:42
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
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
In arch/x86/kernel/traps.c (ffffffff8221e7dc)
Location: arch/x86/include/asm/stacktrace.h:42
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/mm/fault.c (ffffffff810cfcdd)
Location: arch/x86/include/asm/stacktrace.h:42
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:page_fault_oops
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
