# Function: <code>emit_bpf_tail_call_indirect</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void emit_bpf_tail_call_indirect(u8 **pprog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109fa70)
Location: arch/x86/net/bpf_jit_comp.c:354
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109fa70-ffffffff8109fb2a: emit_bpf_tail_call_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void emit_bpf_tail_call_indirect(u8 **pprog, bool *callee_regs_used, u32 stack_depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109b850)
Location: arch/x86/net/bpf_jit_comp.c:405
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109b850-ffffffff8109b9b3: emit_bpf_tail_call_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void emit_bpf_tail_call_indirect(u8 **pprog, bool *callee_regs_used, u32 stack_depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109bcc0)
Location: arch/x86/net/bpf_jit_comp.c:417
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109bcc0-ffffffff8109be1e: emit_bpf_tail_call_indirect (STB_LOCAL)
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810ae27c)
Location: arch/x86/net/bpf_jit_comp.c:413
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void emit_bpf_tail_call_indirect(u8 **pprog, bool *callee_regs_used, u32 stack_depth, u8 *ip, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c1d20)
Location: arch/x86/net/bpf_jit_comp.c:457
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810c1d20-ffffffff810c1ee0: emit_bpf_tail_call_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void emit_bpf_tail_call_indirect(u8 **pprog, bool *callee_regs_used, u32 stack_depth, u8 *ip, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810de8a0)
Location: arch/x86/net/bpf_jit_comp.c:470
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810de8a0-ffffffff810dea60: emit_bpf_tail_call_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void emit_bpf_tail_call_indirect(u8 **pprog, bool *callee_regs_used, u32 stack_depth, u8 *ip, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e9ea0)
Location: arch/x86/net/bpf_jit_comp.c:470
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810e9ea0-ffffffff810ea060: emit_bpf_tail_call_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void emit_bpf_tail_call_indirect(struct bpf_prog *bpf_prog, u8 **pprog, bool *callee_regs_used, u32 stack_depth, u8 *ip, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:592
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810f2760-ffffffff810f2977: emit_bpf_tail_call_indirect (STB_LOCAL)
ffffffff821aedf3-ffffffff821aee1c: emit_bpf_tail_call_indirect.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *callee_regs_used</code>
</li>
<li>
<b>Param added. </b>
<code>u32 stack_depth</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
<code>pprog, callee_regs_used, stack_depth, ip, ctx</code> ➡️ <code>bpf_prog, pprog, callee_regs_used, stack_depth, ip, ctx</code>
</li>
</ul>
</details>
</li>
</ul>
