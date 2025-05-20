# Function: <code>emit_bpf_tail_call_direct</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810a1153)
Location: arch/x86/net/bpf_jit_comp.c:421
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor *poke, u8 **pprog, int addr, u8 *image, bool *callee_regs_used, u32 stack_depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:495
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109b9c0-ffffffff8109bb10: emit_bpf_tail_call_direct (STB_LOCAL)
ffffffff81bdadd8-ffffffff81bdadf5: emit_bpf_tail_call_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor *poke, u8 **pprog, int addr, u8 *image, bool *callee_regs_used, u32 stack_depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:507
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109c0e0-ffffffff8109c226: emit_bpf_tail_call_direct (STB_LOCAL)
ffffffff81bcceb3-ffffffff81bcced0: emit_bpf_tail_call_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor *poke, u8 **pprog, int addr, u8 *image, bool *callee_regs_used, u32 stack_depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:502
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810abdc0-ffffffff810abeff: emit_bpf_tail_call_direct (STB_LOCAL)
ffffffff81ca3494-ffffffff81ca34b1: emit_bpf_tail_call_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor *poke, u8 **pprog, u8 *ip, bool *callee_regs_used, u32 stack_depth, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:531
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810c1930-ffffffff810c1ab5: emit_bpf_tail_call_direct (STB_LOCAL)
ffffffff81e52c40-ffffffff81e52c57: emit_bpf_tail_call_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor *poke, u8 **pprog, u8 *ip, bool *callee_regs_used, u32 stack_depth, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810de3b0)
Location: arch/x86/net/bpf_jit_comp.c:544
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810de3b0-ffffffff810de54b: emit_bpf_tail_call_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor *poke, u8 **pprog, u8 *ip, bool *callee_regs_used, u32 stack_depth, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e99b0)
Location: arch/x86/net/bpf_jit_comp.c:544
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810e99b0-ffffffff810e9b4b: emit_bpf_tail_call_direct (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_prog *bpf_prog, struct bpf_jit_poke_descriptor *poke, u8 **pprog, u8 *ip, bool *callee_regs_used, u32 stack_depth, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:672
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810f2460-ffffffff810f265b: emit_bpf_tail_call_direct (STB_LOCAL)
ffffffff821aedce-ffffffff821aedf3: emit_bpf_tail_call_direct.cold (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *ip</code>
</li>
<li>
<b>Param added. </b>
<code>struct jit_context *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 *image</code>
</li>
<li>
<b>Param reordered. </b>
<code>poke, pprog, addr, image, callee_regs_used, stack_depth</code> ➡️ <code>poke, pprog, ip, callee_regs_used, stack_depth, ctx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog *bpf_prog</code>
</li>
<li>
<b>Param reordered. </b>
<code>poke, pprog, ip, callee_regs_used, stack_depth, ctx</code> ➡️ <code>bpf_prog, poke, pprog, ip, callee_regs_used, stack_depth, ctx</code>
</li>
</ul>
</details>
</li>
</ul>
