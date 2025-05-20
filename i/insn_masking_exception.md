# Function: <code>insn_masking_exception</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81068544)
Location: arch/x86/include/asm/insn.h:222
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff8106f03a)
Location: arch/x86/include/asm/insn.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff8106e3a4)
Location: arch/x86/include/asm/insn.h:222
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff810750aa)
Location: arch/x86/include/asm/insn.h:222
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff810723f4)
Location: arch/x86/include/asm/insn.h:209
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81078c9d)
Location: arch/x86/include/asm/insn.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff81073424)
Location: arch/x86/include/asm/insn.h:209
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81079ced)
Location: arch/x86/include/asm/insn.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff81079cf8)
Location: arch/x86/include/asm/insn.h:215
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff8108113b)
Location: arch/x86/include/asm/insn.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff81079908)
Location: arch/x86/include/asm/insn.h:230
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81080be1)
Location: arch/x86/include/asm/insn.h:230
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff8107b47b)
Location: arch/x86/include/asm/insn.h:269
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff810819b1)
Location: arch/x86/include/asm/insn.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff8108960b)
Location: arch/x86/include/asm/insn.h:269
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff810909d0)
Location: arch/x86/include/asm/insn.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff810999af)
Location: arch/x86/include/asm/insn.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/uprobes.c (ffffffff810a1a1e)
Location: arch/x86/include/asm/insn.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff810b02e6)
Location: arch/x86/include/asm/insn.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/uprobes.c (ffffffff810b9521)
Location: arch/x86/include/asm/insn.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff810b3306)
Location: arch/x86/include/asm/insn.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/uprobes.c (ffffffff810bc801)
Location: arch/x86/include/asm/insn.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff810ba766)
Location: arch/x86/include/asm/insn.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/uprobes.c (ffffffff810c3981)
Location: arch/x86/include/asm/insn.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:uprobe_init_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff81072424)
Location: arch/x86/include/asm/insn.h:209
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81078ced)
Location: arch/x86/include/asm/insn.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff810624a4)
Location: arch/x86/include/asm/insn.h:209
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff8106849d)
Location: arch/x86/include/asm/insn.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff810723d4)
Location: arch/x86/include/asm/insn.h:209
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81078c9d)
Location: arch/x86/include/asm/insn.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff81074424)
Location: arch/x86/include/asm/insn.h:209
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff8107ad9d)
Location: arch/x86/include/asm/insn.h:209
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
</ul>

## Differences
