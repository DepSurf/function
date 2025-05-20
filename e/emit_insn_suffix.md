# Function: <code>emit_insn_suffix</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void emit_insn_suffix(u8 **pprog, u32 ptr_reg, u32 val_reg, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109f207)
Location: arch/x86/net/bpf_jit_comp.c:700
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff8109ba40-ffffffff8109ba9b: emit_insn_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void emit_insn_suffix(u8 **pprog, u32 ptr_reg, u32 val_reg, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810b04c2)
Location: arch/x86/net/bpf_jit_comp.c:691
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:emit_ldx
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff810abb00-ffffffff810abc1c: emit_insn_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void emit_insn_suffix(u8 **pprog, u32 ptr_reg, u32 val_reg, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c62a0)
Location: arch/x86/net/bpf_jit_comp.c:692
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:emit_ldx
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff810c1600-ffffffff810c172a: emit_insn_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void emit_insn_suffix(u8 **pprog, u32 ptr_reg, u32 val_reg, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e31ab)
Location: arch/x86/net/bpf_jit_comp.c:705
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:emit_ldx
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff810ddfc0-ffffffff810de0ea: emit_insn_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void emit_insn_suffix(u8 **pprog, u32 ptr_reg, u32 val_reg, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ee83b)
Location: arch/x86/net/bpf_jit_comp.c:705
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:emit_ldx
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff810e95b0-ffffffff810e96da: emit_insn_suffix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void emit_insn_suffix(u8 **pprog, u32 ptr_reg, u32 val_reg, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f4030)
Location: arch/x86/net/bpf_jit_comp.c:871
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:restore_regs
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:save_args
  - arch/x86/net/bpf_jit_comp.c:save_args
  - arch/x86/net/bpf_jit_comp.c:save_args
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff810f17a0-ffffffff810f18ca: emit_insn_suffix (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
