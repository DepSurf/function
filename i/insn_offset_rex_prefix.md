# Function: <code>insn_offset_rex_prefix</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/include/asm/insn.h:172
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/include/asm/insn.h:172
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105fa71)
Location: arch/x86/include/asm/insn.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/uprobes.c (ffffffff8106597c)
Location: arch/x86/include/asm/insn.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81062b11)
Location: arch/x86/include/asm/insn.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/uprobes.c (ffffffff81068eac)
Location: arch/x86/include/asm/insn.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810619c3)
Location: arch/x86/include/asm/insn.h:182
Inline: True
```
```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/include/asm/insn.h:182
Inline: True
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
In arch/x86/kernel/kprobes/core.c (ffffffff81065a1e)
Location: arch/x86/include/asm/insn.h:182
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff8106c373)
Location: arch/x86/include/asm/insn.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff81068572)
Location: arch/x86/include/asm/insn.h:182
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff8106f1aa)
Location: arch/x86/include/asm/insn.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff8106e3d2)
Location: arch/x86/include/asm/insn.h:182
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff8107521a)
Location: arch/x86/include/asm/insn.h:182
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff81072422)
Location: arch/x86/include/asm/insn.h:169
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81078db5)
Location: arch/x86/include/asm/insn.h:169
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
In arch/x86/kernel/kprobes/core.c (ffffffff81073452)
Location: arch/x86/include/asm/insn.h:169
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81079e05)
Location: arch/x86/include/asm/insn.h:169
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
In arch/x86/kernel/kprobes/core.c (ffffffff81079d26)
Location: arch/x86/include/asm/insn.h:175
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81080c98)
Location: arch/x86/include/asm/insn.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:riprel_analyze
  - arch/x86/kernel/uprobes.c:riprel_analyze
  - arch/x86/kernel/uprobes.c:riprel_analyze
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
In arch/x86/kernel/kprobes/core.c (ffffffff81079936)
Location: arch/x86/include/asm/insn.h:175
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81080748)
Location: arch/x86/include/asm/insn.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:riprel_analyze
  - arch/x86/kernel/uprobes.c:riprel_analyze
  - arch/x86/kernel/uprobes.c:riprel_analyze
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
In arch/x86/kernel/kprobes/core.c (ffffffff8107b4a9)
Location: arch/x86/include/asm/insn.h:214
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81081b1f)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff81089639)
Location: arch/x86/include/asm/insn.h:214
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81090b4f)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff81099a11)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/uprobes.c (ffffffff810a1bfb)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff810b0312)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/uprobes.c (ffffffff810b9d6f)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/alternative.c (ffffffff8105a217)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:apply_relocation
  - arch/x86/kernel/alternative.c:apply_relocation
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810b3332)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/uprobes.c (ffffffff810bcf2b)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/alternative.c (ffffffff81061387)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:apply_relocation
  - arch/x86/kernel/alternative.c:apply_relocation
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810ba792)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/uprobes.c (ffffffff810c40ab)
Location: arch/x86/include/asm/insn.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
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
In arch/x86/kernel/kprobes/core.c (ffffffff81072452)
Location: arch/x86/include/asm/insn.h:169
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81078e05)
Location: arch/x86/include/asm/insn.h:169
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
In arch/x86/kernel/kprobes/core.c (ffffffff810624d2)
Location: arch/x86/include/asm/insn.h:169
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff810685b5)
Location: arch/x86/include/asm/insn.h:169
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
In arch/x86/kernel/kprobes/core.c (ffffffff81072402)
Location: arch/x86/include/asm/insn.h:169
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff81078db5)
Location: arch/x86/include/asm/insn.h:169
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
In arch/x86/kernel/kprobes/core.c (ffffffff81074452)
Location: arch/x86/include/asm/insn.h:169
Inline: True
```
```
In arch/x86/kernel/uprobes.c (ffffffff8107aeb5)
Location: arch/x86/include/asm/insn.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn
```
</details>
</li>
</ul>

## Differences
