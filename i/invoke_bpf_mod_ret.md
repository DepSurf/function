# Function: <code>invoke_bpf_mod_ret</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810a2450)
Location: arch/x86/net/bpf_jit_comp.c:1478
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
**Symbols:**

```
ffffffff810a2450-ffffffff810a253d: invoke_bpf_mod_ret.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109bcf0)
Location: arch/x86/net/bpf_jit_comp.c:1651
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
**Symbols:**

```
ffffffff8109bcf0-ffffffff8109bddd: invoke_bpf_mod_ret.isra.0 (STB_LOCAL)
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109f203)
Location: arch/x86/net/bpf_jit_comp.c:1862
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810b04a4)
Location: arch/x86/net/bpf_jit_comp.c:1890
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810c63e7)
Location: arch/x86/net/bpf_jit_comp.c:1909
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810e32bd)
Location: arch/x86/net/bpf_jit_comp.c:2032
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810eea15)
Location: arch/x86/net/bpf_jit_comp.c:2037
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810f4222)
Location: arch/x86/net/bpf_jit_comp.c:2395
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
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
