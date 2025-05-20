# Function: <code>recover_probed_instruction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f9b0)
Location: arch/x86/kernel/kprobes/core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8105f9b0-ffffffff8105fa75: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f7b0)
Location: arch/x86/kernel/kprobes/core.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8105f7b0-ffffffff8105f87a: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81062850)
Location: arch/x86/kernel/kprobes/core.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81062850-ffffffff8106291a: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81061780)
Location: arch/x86/kernel/kprobes/core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81061780-ffffffff8106183f: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810657d0)
Location: arch/x86/kernel/kprobes/core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff810657d0-ffffffff8106588f: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81068340)
Location: arch/x86/kernel/kprobes/core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81068340-ffffffff810683e2: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8106e1a0)
Location: arch/x86/kernel/kprobes/core.c:275
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8106e1a0-ffffffff8106e242: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8107280f-ffffffff81072825: recover_probed_instruction.cold (STB_LOCAL)
ffffffff810721f0-ffffffff8107229b: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81073220)
Location: arch/x86/kernel/kprobes/core.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81073220-ffffffff810732c7: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a11c)
Location: arch/x86/kernel/kprobes/core.c:263
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8107a4a0-ffffffff8107a4d1: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81079b7c)
Location: arch/x86/kernel/kprobes/core.c:264
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8107a220-ffffffff8107a251: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107b290)
Location: arch/x86/kernel/kprobes/core.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8107b290-ffffffff8107b330: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81089420)
Location: arch/x86/kernel/kprobes/core.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81089420-ffffffff810894c0: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81099730)
Location: arch/x86/kernel/kprobes/core.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81099730-ffffffff810997e1: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b0263)
Location: arch/x86/kernel/kprobes/core.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff810b0190-ffffffff810b01d1: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b3283)
Location: arch/x86/kernel/kprobes/core.c:243
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff810b31b0-ffffffff810b31f1: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810ba6e3)
Location: arch/x86/kernel/kprobes/core.c:244
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff810ba610-ffffffff810ba651: recover_probed_instruction (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81072220)
Location: arch/x86/kernel/kprobes/core.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81072220-ffffffff810722c7: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810622a0)
Location: arch/x86/kernel/kprobes/core.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff810622a0-ffffffff81062347: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810721d0)
Location: arch/x86/kernel/kprobes/core.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff810721d0-ffffffff81072277: recover_probed_instruction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int recover_probed_instruction(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81074220)
Location: arch/x86/kernel/kprobes/core.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81074220-ffffffff810742c7: recover_probed_instruction (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
