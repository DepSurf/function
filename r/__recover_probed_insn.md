# Function: <code>__recover_probed_insn</code>

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
In arch/x86/kernel/kprobes/core.c (ffffffff8105f9df)
Location: arch/x86/kernel/kprobes/core.c:223
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff8105f7df)
Location: arch/x86/kernel/kprobes/core.c:225
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff8106287f)
Location: arch/x86/kernel/kprobes/core.c:226
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff810617b3)
Location: arch/x86/kernel/kprobes/core.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff81065803)
Location: arch/x86/kernel/kprobes/core.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff8106836f)
Location: arch/x86/kernel/kprobes/core.c:220
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff8106e1cf)
Location: arch/x86/kernel/kprobes/core.c:218
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff8107221f)
Location: arch/x86/kernel/kprobes/core.c:205
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff8107324f)
Location: arch/x86/kernel/kprobes/core.c:205
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __recover_probed_insn(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810798d0)
Location: arch/x86/kernel/kprobes/core.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
**Symbols:**

```
ffffffff810798d0-ffffffff81079976: __recover_probed_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __recover_probed_insn(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810797b0)
Location: arch/x86/kernel/kprobes/core.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_probe
```
**Symbols:**

```
ffffffff810797b0-ffffffff81079856: __recover_probed_insn (STB_LOCAL)
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
In arch/x86/kernel/kprobes/core.c (ffffffff8107b2bf)
Location: arch/x86/kernel/kprobes/core.c:193
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff8108944f)
Location: arch/x86/kernel/kprobes/core.c:193
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff81099769)
Location: arch/x86/kernel/kprobes/core.c:194
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __recover_probed_insn(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810af9f0)
Location: arch/x86/kernel/kprobes/core.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
```
**Symbols:**

```
ffffffff810af9f0-ffffffff810afaa8: __recover_probed_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __recover_probed_insn(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b2a10)
Location: arch/x86/kernel/kprobes/core.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
```
**Symbols:**

```
ffffffff810b2a10-ffffffff810b2ac8: __recover_probed_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __recover_probed_insn(kprobe_opcode_t *buf, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b9e70)
Location: arch/x86/kernel/kprobes/core.c:194
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:__copy_instruction
  - arch/x86/kernel/kprobes/core.c:can_probe
```
**Symbols:**

```
ffffffff810b9e70-ffffffff810b9f28: __recover_probed_insn (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107224f)
Location: arch/x86/kernel/kprobes/core.c:205
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff810622cf)
Location: arch/x86/kernel/kprobes/core.c:205
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff810721ff)
Location: arch/x86/kernel/kprobes/core.c:205
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
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
In arch/x86/kernel/kprobes/core.c (ffffffff8107424f)
Location: arch/x86/kernel/kprobes/core.c:205
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:recover_probed_instruction
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
