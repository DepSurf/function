# Function: <code>emit_mov_imm64</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810893a6)
Location: arch/x86/net/bpf_jit_comp.c:369
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (ffffffff81090d51)
Location: arch/x86/net/bpf_jit_comp.c:369
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (ffffffff81094d4c)
Location: arch/x86/net/bpf_jit_comp.c:338
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109b2f6)
Location: arch/x86/net/bpf_jit_comp.c:338
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void emit_mov_imm64(u8 **pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109fbe0)
Location: arch/x86/net/bpf_jit_comp.c:524
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109fbe0-ffffffff8109fc8d: emit_mov_imm64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void emit_mov_imm64(u8 **pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109b0f0)
Location: arch/x86/net/bpf_jit_comp.c:642
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109b0f0-ffffffff8109b19d: emit_mov_imm64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void emit_mov_imm64(u8 **pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109b8a0)
Location: arch/x86/net/bpf_jit_comp.c:657
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109b8a0-ffffffff8109b94d: emit_mov_imm64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void emit_mov_imm64(u8 **pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ac810)
Location: arch/x86/net/bpf_jit_comp.c:650
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810ac810-ffffffff810ac8f9: emit_mov_imm64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void emit_mov_imm64(u8 **pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c2660)
Location: arch/x86/net/bpf_jit_comp.c:651
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810c2660-ffffffff810c2768: emit_mov_imm64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void emit_mov_imm64(u8 **pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810df290)
Location: arch/x86/net/bpf_jit_comp.c:664
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810df290-ffffffff810df398: emit_mov_imm64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void emit_mov_imm64(u8 **pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ea880)
Location: arch/x86/net/bpf_jit_comp.c:664
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810ea880-ffffffff810ea988: emit_mov_imm64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void emit_mov_imm64(u8 **pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f31a0)
Location: arch/x86/net/bpf_jit_comp.c:798
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810f31a0-ffffffff810f32a8: emit_mov_imm64 (STB_LOCAL)
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
In arch/x86/net/bpf_jit_comp.c (ffffffff81094c16)
Location: arch/x86/net/bpf_jit_comp.c:338
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810836a6)
Location: arch/x86/net/bpf_jit_comp.c:338
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (ffffffff81094bc6)
Location: arch/x86/net/bpf_jit_comp.c:338
Inline: True
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109c7c6)
Location: arch/x86/net/bpf_jit_comp.c:338
Inline: True
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
