# Function: <code>is_kernel_text</code>

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
In arch/x86/net/bpf_jit_comp.c (ffffffff810a2795)
Location: include/linux/kallsyms.h:32
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109e0b5)
Location: include/linux/kallsyms.h:32
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
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
In arch/x86/net/bpf_jit_comp.c (ffffffff8109eec5)
Location: include/linux/kallsyms.h:32
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810b0085)
Location: include/linux/kallsyms.h:35
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c5e15)
Location: include/linux/kallsyms.h:27
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
```
In kernel/extable.c (ffffffff810f7c95)
Location: include/linux/kallsyms.h:27
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e2bd5)
Location: include/linux/kallsyms.h:27
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
```
In kernel/extable.c (ffffffff8111a4e5)
Location: include/linux/kallsyms.h:27
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ee2a5)
Location: include/linux/kallsyms.h:27
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
```
In kernel/extable.c (ffffffff81127755)
Location: include/linux/kallsyms.h:27
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f7d65)
Location: include/linux/kallsyms.h:27
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
```
In kernel/extable.c (ffffffff81131d35)
Location: include/linux/kallsyms.h:27
Inline: True
Inline callers:
  - kernel/extable.c:func_ptr_is_kernel_text
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
