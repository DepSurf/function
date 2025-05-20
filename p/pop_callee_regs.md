# Function: <code>pop_callee_regs</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pop_callee_regs(u8 **pprog, bool *callee_regs_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109afe0)
Location: arch/x86/net/bpf_jit_comp.c:243
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
```
**Symbols:**

```
ffffffff8109afe0-ffffffff8109b038: pop_callee_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pop_callee_regs(u8 **pprog, bool *callee_regs_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109b790)
Location: arch/x86/net/bpf_jit_comp.c:255
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
```
**Symbols:**

```
ffffffff8109b790-ffffffff8109b7e8: pop_callee_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pop_callee_regs(u8 **pprog, bool *callee_regs_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:254
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
```
**Symbols:**

```
ffffffff810abc90-ffffffff810abd3a: pop_callee_regs (STB_LOCAL)
ffffffff81ca33d5-ffffffff81ca3429: pop_callee_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pop_callee_regs(u8 **pprog, bool *callee_regs_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:272
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
```
**Symbols:**

```
ffffffff810c1760-ffffffff810c1818: pop_callee_regs (STB_LOCAL)
ffffffff81e52bb5-ffffffff81e52c09: pop_callee_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pop_callee_regs(u8 **pprog, bool *callee_regs_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:273
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
```
**Symbols:**

```
ffffffff810de180-ffffffff810de238: pop_callee_regs (STB_LOCAL)
ffffffff82055856-ffffffff820558aa: pop_callee_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pop_callee_regs(u8 **pprog, bool *callee_regs_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:273
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
```
**Symbols:**

```
ffffffff810e9770-ffffffff810e9828: pop_callee_regs (STB_LOCAL)
ffffffff820d3e51-ffffffff820d3ea5: pop_callee_regs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pop_callee_regs(u8 **pprog, bool *callee_regs_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:295
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
```
**Symbols:**

```
ffffffff810f1a30-ffffffff810f1ae8: pop_callee_regs (STB_LOCAL)
ffffffff821aecf7-ffffffff821aed4b: pop_callee_regs.cold (STB_LOCAL)
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
