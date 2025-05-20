# Function: <code>emit_atomic</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int emit_atomic(u8 **pprog, u8 atomic_op, u32 dst_reg, u32 src_reg, s16 off, u8 bpf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:801
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff8109bb70-ffffffff8109bc99: emit_atomic (STB_LOCAL)
ffffffff81bcce9d-ffffffff81bcceb3: emit_atomic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int emit_atomic(u8 **pprog, u8 atomic_op, u32 dst_reg, u32 src_reg, s16 off, u8 bpf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:802
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810ac390-ffffffff810ac4de: emit_atomic (STB_LOCAL)
ffffffff81ca3534-ffffffff81ca354a: emit_atomic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int emit_atomic(u8 **pprog, u8 atomic_op, u32 dst_reg, u32 src_reg, s16 off, u8 bpf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:803
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810c1f60-ffffffff810c20a6: emit_atomic (STB_LOCAL)
ffffffff81e52c90-ffffffff81e52ca6: emit_atomic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int emit_atomic(u8 **pprog, u8 atomic_op, u32 dst_reg, u32 src_reg, s16 off, u8 bpf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ded90)
Location: arch/x86/net/bpf_jit_comp.c:816
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810ded90-ffffffff810deee5: emit_atomic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int emit_atomic(u8 **pprog, u8 atomic_op, u32 dst_reg, u32 src_reg, s16 off, u8 bpf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ea380)
Location: arch/x86/net/bpf_jit_comp.c:816
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810ea380-ffffffff810ea4dd: emit_atomic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int emit_atomic(u8 **pprog, u8 atomic_op, u32 dst_reg, u32 src_reg, s16 off, u8 bpf_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f2a20)
Location: arch/x86/net/bpf_jit_comp.c:1005
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
**Symbols:**

```
ffffffff810f2a20-ffffffff810f2b7d: emit_atomic (STB_LOCAL)
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
