# Function: <code>kernel_insn_init</code>

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
In arch/x86/kernel/kprobes/core.c (ffffffff8105fad3)
Location: arch/x86/include/asm/insn.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81060147)
Location: arch/x86/include/asm/insn.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff8105fa31)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8105ff47)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff81062ad1)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81062fe7)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff81061893)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81061fed)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff810658e3)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff810660d1)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff81068443)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81068c91)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff8106e2a3)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8106ea51)
Location: arch/x86/include/asm/insn.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff810722f3)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072af2)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff81073323)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81073ae2)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/traps.c (ffffffff81034167)
Location: arch/x86/include/asm/insn.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:get_kernel_gp_address
```
```
In arch/x86/kernel/alternative.c (ffffffff8103c984)
Location: arch/x86/include/asm/insn.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_loc_init
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a0e8)
Location: arch/x86/include/asm/insn.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107acc7)
Location: arch/x86/include/asm/insn.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/traps.c (ffffffff81034b67)
Location: arch/x86/include/asm/insn.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:get_kernel_gp_address
```
```
In arch/x86/kernel/alternative.c (ffffffff8103ce24)
Location: arch/x86/include/asm/insn.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke_loc_init
```
```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81052aed)
Location: arch/x86/include/asm/insn.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81079b48)
Location: arch/x86/include/asm/insn.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107aa57)
Location: arch/x86/include/asm/insn.h:108
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81072323)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072ae2)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff810623a3)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81062b62)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff810722d3)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072a92)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
In arch/x86/kernel/kprobes/core.c (ffffffff81074323)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
```
In arch/x86/kernel/kprobes/opt.c (ffffffff81074ae2)
Location: arch/x86/include/asm/insn.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
</details>
</li>
</ul>

## Differences
