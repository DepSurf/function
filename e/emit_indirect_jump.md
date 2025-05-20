# Function: <code>emit_indirect_jump</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void emit_indirect_jump(u8 **pprog, int reg, u8 *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:411
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
```
**Symbols:**

```
ffffffff810c1c60-ffffffff810c1d11: emit_indirect_jump (STB_LOCAL)
ffffffff81e52c7f-ffffffff81e52c90: emit_indirect_jump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void emit_indirect_jump(u8 **pprog, int reg, u8 *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810de7b0)
Location: arch/x86/net/bpf_jit_comp.c:419
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
```
**Symbols:**

```
ffffffff810de7b0-ffffffff810de890: emit_indirect_jump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void emit_indirect_jump(u8 **pprog, int reg, u8 *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e9db0)
Location: arch/x86/net/bpf_jit_comp.c:419
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
```
**Symbols:**

```
ffffffff810e9db0-ffffffff810e9e90: emit_indirect_jump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void emit_indirect_jump(u8 **pprog, int reg, u8 *ip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f2670)
Location: arch/x86/net/bpf_jit_comp.c:541
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect
```
**Symbols:**

```
ffffffff810f2670-ffffffff810f2750: emit_indirect_jump (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
