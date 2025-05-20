# Function: <code>emit_ldx</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void emit_ldx(u8 **pprog, u32 size, u32 dst_reg, u32 src_reg, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810a2af6)
Location: arch/x86/net/bpf_jit_comp.c:567
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109fd90-ffffffff8109ff1c: emit_ldx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void emit_ldx(u8 **pprog, u32 size, u32 dst_reg, u32 src_reg, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109e41e)
Location: arch/x86/net/bpf_jit_comp.c:685
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109b2a0-ffffffff8109b42c: emit_ldx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void emit_ldx(u8 **pprog, u32 size, u32 dst_reg, u32 src_reg, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109f4e1)
Location: arch/x86/net/bpf_jit_comp.c:736
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109be20-ffffffff8109bfd0: emit_ldx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void emit_ldx(u8 **pprog, u32 size, u32 dst_reg, u32 src_reg, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:739
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810acb30-ffffffff810acd3c: emit_ldx (STB_LOCAL)
ffffffff81ca35c7-ffffffff81ca35e8: emit_ldx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void emit_ldx(u8 **pprog, u32 size, u32 dst_reg, u32 src_reg, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:740
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810c2a20-ffffffff810c2c44: emit_ldx (STB_LOCAL)
ffffffff81e52d1b-ffffffff81e52d3c: emit_ldx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void emit_ldx(u8 **pprog, u32 size, u32 dst_reg, u32 src_reg, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:753
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810df6c0-ffffffff810df8e4: emit_ldx (STB_LOCAL)
ffffffff820558c9-ffffffff820558ea: emit_ldx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void emit_ldx(u8 **pprog, u32 size, u32 dst_reg, u32 src_reg, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:753
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810eac90-ffffffff810eaea2: emit_ldx (STB_LOCAL)
ffffffff820d3ec4-ffffffff820d3ee5: emit_ldx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void emit_ldx(u8 **pprog, u32 size, u32 dst_reg, u32 src_reg, int off);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f1d20)
Location: arch/x86/net/bpf_jit_comp.c:919
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:restore_regs
  - arch/x86/net/bpf_jit_comp.c:save_args
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810f3690-ffffffff810f38ab: emit_ldx (STB_LOCAL)
ffffffff821aee1c-ffffffff821aee3d: emit_ldx.cold (STB_LOCAL)
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
