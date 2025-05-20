# Function: <code>emit_bpf_tail_call</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107ba2c)
Location: arch/x86/net/bpf_jit_comp.c:255
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107d1f6)
Location: arch/x86/net/bpf_jit_comp.c:267
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81081796)
Location: arch/x86/net/bpf_jit_comp.c:267
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107ec4e)
Location: arch/x86/net/bpf_jit_comp.c:271
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81085480)
Location: arch/x86/net/bpf_jit_comp.c:274
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:do_jit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810887b0)
Location: arch/x86/net/bpf_jit_comp.c:261
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
In arch/x86/net/bpf_jit_comp.c (ffffffff81091167)
Location: arch/x86/net/bpf_jit_comp.c:261
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810948b9)
Location: arch/x86/net/bpf_jit_comp.c:230
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109ae4a)
Location: arch/x86/net/bpf_jit_comp.c:230
Inline: True
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int emit_bpf_tail_call(struct jit_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b27e8)
Location: arch/arm64/net/bpf_jit_comp.c:243
Inline: False
Direct callers:
  - arch/arm64/net/bpf_jit_comp.c:build_insn
```
**Symbols:**

```
ffff8000100b27e8-ffff8000100b2c90: emit_bpf_tail_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int emit_bpf_tail_call(struct jit_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/net/bpf_jit_32.c (c0328b80)
Location: arch/arm/net/bpf_jit_32.c:1130
Inline: False
Direct callers:
  - arch/arm/net/bpf_jit_32.c:build_insn
```
**Symbols:**

```
c0328b80-c0328f60: emit_bpf_tail_call (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int emit_bpf_tail_call(int insn, struct rv_jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/net/bpf_jit_comp.c (ffffffe0000bad44)
Location: arch/riscv/net/bpf_jit_comp.c:615
Inline: False
Direct callers:
  - arch/riscv/net/bpf_jit_comp.c:emit_insn
```
**Symbols:**

```
ffffffe0000bad44-ffffffe0000baff2: emit_bpf_tail_call (STB_LOCAL)
```
</details>
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109476a)
Location: arch/x86/net/bpf_jit_comp.c:230
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810831fa)
Location: arch/x86/net/bpf_jit_comp.c:230
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109471a)
Location: arch/x86/net/bpf_jit_comp.c:230
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109c31a)
Location: arch/x86/net/bpf_jit_comp.c:230
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
