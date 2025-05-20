# Function: <code>emit_mov_imm32</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81088490)
Location: arch/x86/net/bpf_jit_comp.c:328
Inline: False
```
**Symbols:**

```
ffffffff81088490-ffffffff81088546: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8108ff60)
Location: arch/x86/net/bpf_jit_comp.c:328
Inline: False
```
**Symbols:**

```
ffffffff8108ff60-ffffffff81090016: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81093d00)
Location: arch/x86/net/bpf_jit_comp.c:297
Inline: False
```
**Symbols:**

```
ffffffff81093d00-ffffffff81093db6: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109a2d0)
Location: arch/x86/net/bpf_jit_comp.c:297
Inline: False
```
**Symbols:**

```
ffffffff8109a2d0-ffffffff8109a386: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109fb30)
Location: arch/x86/net/bpf_jit_comp.c:483
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_mov_imm64
```
**Symbols:**

```
ffffffff8109fb30-ffffffff8109fbde: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109b040)
Location: arch/x86/net/bpf_jit_comp.c:601
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_mov_imm64
```
**Symbols:**

```
ffffffff8109b040-ffffffff8109b0ee: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109f207)
Location: arch/x86/net/bpf_jit_comp.c:616
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_mov_imm64
```
**Symbols:**

```
ffffffff8109b7f0-ffffffff8109b89e: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ac690)
Location: arch/x86/net/bpf_jit_comp.c:610
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_mov_imm64
```
**Symbols:**

```
ffffffff810ac690-ffffffff810ac802: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c24d0)
Location: arch/x86/net/bpf_jit_comp.c:611
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_mov_imm64
```
**Symbols:**

```
ffffffff810c24d0-ffffffff810c2654: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810df0f0)
Location: arch/x86/net/bpf_jit_comp.c:624
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_mov_imm64
```
**Symbols:**

```
ffffffff810df0f0-ffffffff810df274: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ea6e0)
Location: arch/x86/net/bpf_jit_comp.c:624
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_mov_imm64
```
**Symbols:**

```
ffffffff810ea6e0-ffffffff810ea864: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f3000)
Location: arch/x86/net/bpf_jit_comp.c:758
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_mov_imm64
```
**Symbols:**

```
ffffffff810f3000-ffffffff810f3184: emit_mov_imm32 (STB_LOCAL)
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
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81093bf0)
Location: arch/x86/net/bpf_jit_comp.c:297
Inline: False
```
**Symbols:**

```
ffffffff81093bf0-ffffffff81093ca6: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81082680)
Location: arch/x86/net/bpf_jit_comp.c:297
Inline: False
```
**Symbols:**

```
ffffffff81082680-ffffffff81082736: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81093ba0)
Location: arch/x86/net/bpf_jit_comp.c:297
Inline: False
```
**Symbols:**

```
ffffffff81093ba0-ffffffff81093c56: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void emit_mov_imm32(u8 **pprog, bool sign_propagate, u32 dst_reg, const u32 imm32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109b7a0)
Location: arch/x86/net/bpf_jit_comp.c:297
Inline: False
```
**Symbols:**

```
ffffffff8109b7a0-ffffffff8109b856: emit_mov_imm32 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
