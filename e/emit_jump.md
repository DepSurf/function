# Function: <code>emit_jump</code>

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
In arch/x86/net/bpf_jit_comp.c (ffffffff810a2749)
Location: arch/x86/net/bpf_jit_comp.c:278
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109c279)
Location: arch/x86/net/bpf_jit_comp.c:312
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109cae7)
Location: arch/x86/net/bpf_jit_comp.c:324
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810ac2e7)
Location: arch/x86/net/bpf_jit_comp.c:320
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c1a02)
Location: arch/x86/net/bpf_jit_comp.c:343
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_return
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810de481)
Location: arch/x86/net/bpf_jit_comp.c:351
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_return
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e9a81)
Location: arch/x86/net/bpf_jit_comp.c:351
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_return
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f2530)
Location: arch/x86/net/bpf_jit_comp.c:473
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_direct
  - arch/x86/net/bpf_jit_comp.c:emit_return
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
  - arch/x86/net/bpf_jit_comp.c:__bpf_arch_text_poke
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
