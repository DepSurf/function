# Function: <code>__copy_instruction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __copy_instruction(u8 *dest, u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105fb50)
Location: arch/x86/kernel/kprobes/core.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8105fb50-ffffffff8105fd18: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __copy_instruction(u8 *dest, u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f950)
Location: arch/x86/kernel/kprobes/core.c:355
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8105f950-ffffffff8105fb11: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __copy_instruction(u8 *dest, u8 *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810629f0)
Location: arch/x86/kernel/kprobes/core.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff810629f0-ffffffff81062bb1: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81061910)
Location: arch/x86/kernel/kprobes/core.c:352
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff81061910-ffffffff81061a1c: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81065960)
Location: arch/x86/kernel/kprobes/core.c:353
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff81065960-ffffffff81065a77: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:353
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff81068990-ffffffff810689a6: __copy_instruction.cold.18 (STB_LOCAL)
ffffffff810684c0-ffffffff810685d3: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8106e383)
Location: arch/x86/kernel/kprobes/core.c:351
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff8106e753-ffffffff8106e769: __copy_instruction.cold.15 (STB_LOCAL)
ffffffff8106e320-ffffffff8106e433: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810723d3)
Location: arch/x86/kernel/kprobes/core.c:338
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff81072825-ffffffff8107283b: __copy_instruction.cold (STB_LOCAL)
ffffffff81072370-ffffffff81072483: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81073403)
Location: arch/x86/kernel/kprobes/core.c:338
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff8107380f-ffffffff81073825: __copy_instruction.cold (STB_LOCAL)
ffffffff810733a0-ffffffff810734b3: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a4e0)
Location: arch/x86/kernel/kprobes/core.c:339
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff81079cb0-ffffffff81079d83: __copy_instruction.part.0 (STB_LOCAL)
ffffffff8107a909-ffffffff8107a91d: __copy_instruction.part.0.cold (STB_LOCAL)
ffffffff8107a4e0-ffffffff8107a582: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a260)
Location: arch/x86/kernel/kprobes/core.c:340
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff810798c0-ffffffff81079993: __copy_instruction.part.0 (STB_LOCAL)
ffffffff81bd7b78-ffffffff81bd7b8c: __copy_instruction.part.0.cold (STB_LOCAL)
ffffffff8107a260-ffffffff8107a302: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107b455)
Location: arch/x86/kernel/kprobes/core.c:311
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff81bc9b44-ffffffff81bc9b58: __copy_instruction.cold (STB_LOCAL)
ffffffff8107b3f0-ffffffff8107b511: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810895e5)
Location: arch/x86/kernel/kprobes/core.c:311
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff81c9e9e4-ffffffff81c9e9f8: __copy_instruction.cold (STB_LOCAL)
ffffffff81089580-ffffffff8108969e: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff81e4de17-ffffffff81e4de2d: __copy_instruction.cold (STB_LOCAL)
ffffffff81099910-ffffffff81099a56: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b0220)
Location: arch/x86/kernel/kprobes/core.c:323
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff810b0220-ffffffff810b038c: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b3240)
Location: arch/x86/kernel/kprobes/core.c:323
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff810b3240-ffffffff810b33ac: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810ba6a0)
Location: arch/x86/kernel/kprobes/core.c:357
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff810ba6a0-ffffffff810ba80c: __copy_instruction (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81072403)
Location: arch/x86/kernel/kprobes/core.c:338
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff8107280f-ffffffff81072825: __copy_instruction.cold (STB_LOCAL)
ffffffff810723a0-ffffffff810724b3: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81062483)
Location: arch/x86/kernel/kprobes/core.c:338
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff8106288f-ffffffff810628a5: __copy_instruction.cold (STB_LOCAL)
ffffffff81062420-ffffffff81062533: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810723b3)
Location: arch/x86/kernel/kprobes/core.c:338
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff810727bf-ffffffff810727d5: __copy_instruction.cold (STB_LOCAL)
ffffffff81072350-ffffffff81072463: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __copy_instruction(u8 *dest, u8 *src, u8 *real, struct insn *insn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81074403)
Location: arch/x86/kernel/kprobes/core.c:338
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff8107480f-ffffffff81074825: __copy_instruction.cold (STB_LOCAL)
ffffffff810743a0-ffffffff810744b3: __copy_instruction (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct insn *insn</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *real</code>
</li>
<li>
<b>Param reordered. </b>
<code>dest, src, insn</code> ➡️ <code>dest, src, real, insn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
