# Function: <code>cpu_entry_stack</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030bf9)
Location: arch/x86/include/asm/cpu_entry_area.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041885)
Location: arch/x86/include/asm/cpu_entry_area.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81031d29)
Location: arch/x86/include/asm/cpu_entry_area.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043158)
Location: arch/x86/include/asm/cpu_entry_area.h:76
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81033029)
Location: arch/x86/include/asm/cpu_entry_area.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810447c0)
Location: arch/x86/include/asm/cpu_entry_area.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81034e39)
Location: arch/x86/include/asm/cpu_entry_area.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046d94)
Location: arch/x86/include/asm/cpu_entry_area.h:130
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81035669)
Location: arch/x86/include/asm/cpu_entry_area.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047514)
Location: arch/x86/include/asm/cpu_entry_area.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81037579)
Location: arch/x86/include/asm/cpu_entry_area.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b2dd)
Location: arch/x86/include/asm/cpu_entry_area.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81c36544)
Location: arch/x86/include/asm/cpu_entry_area.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a9af)
Location: arch/x86/include/asm/cpu_entry_area.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81c289d4)
Location: arch/x86/include/asm/cpu_entry_area.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c279)
Location: arch/x86/include/asm/cpu_entry_area.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81d46b74)
Location: arch/x86/include/asm/cpu_entry_area.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810534e3)
Location: arch/x86/include/asm/cpu_entry_area.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81f15094)
Location: arch/x86/include/asm/cpu_entry_area.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105ef66)
Location: arch/x86/include/asm/cpu_entry_area.h:146
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff820bc544)
Location: arch/x86/include/asm/cpu_entry_area.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d6c6)
Location: arch/x86/include/asm/cpu_entry_area.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff8213dc84)
Location: arch/x86/include/asm/cpu_entry_area.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106f02c)
Location: arch/x86/include/asm/cpu_entry_area.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff8221fc84)
Location: arch/x86/include/asm/cpu_entry_area.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8107639b)
Location: arch/x86/include/asm/cpu_entry_area.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff810357c9)
Location: arch/x86/include/asm/cpu_entry_area.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047694)
Location: arch/x86/include/asm/cpu_entry_area.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81025119)
Location: arch/x86/include/asm/cpu_entry_area.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036833)
Location: arch/x86/include/asm/cpu_entry_area.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81035629)
Location: arch/x86/include/asm/cpu_entry_area.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810474d4)
Location: arch/x86/include/asm/cpu_entry_area.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
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
In arch/x86/kernel/dumpstack.c (ffffffff81036609)
Location: arch/x86/include/asm/cpu_entry_area.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:in_entry_stack
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810488d4)
Location: arch/x86/include/asm/cpu_entry_area.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
```
</details>
</li>
</ul>

## Differences
