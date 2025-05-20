# Function: <code>maybe_emit_mod</code>

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
void maybe_emit_mod(u8 **pprog, u32 dst_reg, u32 src_reg, bool is64);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109dc6a)
Location: arch/x86/net/bpf_jit_comp.c:723
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff8109baa0-ffffffff8109bb1b: maybe_emit_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void maybe_emit_mod(u8 **pprog, u32 dst_reg, u32 src_reg, bool is64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ac330)
Location: arch/x86/net/bpf_jit_comp.c:713
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff810ac330-ffffffff810ac38f: maybe_emit_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void maybe_emit_mod(u8 **pprog, u32 dst_reg, u32 src_reg, bool is64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c1ee0)
Location: arch/x86/net/bpf_jit_comp.c:714
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff810c1ee0-ffffffff810c1f5b: maybe_emit_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void maybe_emit_mod(u8 **pprog, u32 dst_reg, u32 src_reg, bool is64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ded00)
Location: arch/x86/net/bpf_jit_comp.c:727
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff810ded00-ffffffff810ded7b: maybe_emit_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void maybe_emit_mod(u8 **pprog, u32 dst_reg, u32 src_reg, bool is64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ea2f0)
Location: arch/x86/net/bpf_jit_comp.c:727
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff810ea2f0-ffffffff810ea36b: maybe_emit_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void maybe_emit_mod(u8 **pprog, u32 dst_reg, u32 src_reg, bool is64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f2990)
Location: arch/x86/net/bpf_jit_comp.c:893
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:emit_atomic
```
**Symbols:**

```
ffffffff810f2990-ffffffff810f2a0b: maybe_emit_mod (STB_LOCAL)
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
