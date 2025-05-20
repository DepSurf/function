# Function: <code>restore_regs</code>

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
void restore_regs(const struct btf_func_model *m, u8 **prog, int nr_args, int stack_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810a0120)
Location: arch/x86/net/bpf_jit_comp.c:1359
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
**Symbols:**

```
ffffffff810a0120-ffffffff810a0230: restore_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void restore_regs(const struct btf_func_model *m, u8 **prog, int nr_args, int stack_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109b630)
Location: arch/x86/net/bpf_jit_comp.c:1522
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
**Symbols:**

```
ffffffff8109b630-ffffffff8109b740: restore_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void restore_regs(const struct btf_func_model *m, u8 **prog, int nr_args, int stack_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109bfd0)
Location: arch/x86/net/bpf_jit_comp.c:1745
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
**Symbols:**

```
ffffffff8109bfd0-ffffffff8109c0db: restore_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void restore_regs(const struct btf_func_model *m, u8 **prog, int nr_args, int stack_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810acd40)
Location: arch/x86/net/bpf_jit_comp.c:1769
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
**Symbols:**

```
ffffffff810acd40-ffffffff810ace4b: restore_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void restore_regs(const struct btf_func_model *m, u8 **prog, int nr_args, int stack_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c2c50)
Location: arch/x86/net/bpf_jit_comp.c:1767
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
**Symbols:**

```
ffffffff810c2c50-ffffffff810c2d54: restore_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void restore_regs(const struct btf_func_model *m, u8 **prog, int nr_args, int stack_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810df900)
Location: arch/x86/net/bpf_jit_comp.c:1881
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
**Symbols:**

```
ffffffff810df900-ffffffff810dfa82: restore_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void restore_regs(const struct btf_func_model *m, u8 **prog, int nr_regs, int stack_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810eaec0)
Location: arch/x86/net/bpf_jit_comp.c:1888
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline
```
**Symbols:**

```
ffffffff810eaec0-ffffffff810eafe4: restore_regs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void restore_regs(const struct btf_func_model *m, u8 **prog, int stack_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:2231
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
  - arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline
```
**Symbols:**

```
ffffffff810f1c50-ffffffff810f1eb3: restore_regs (STB_LOCAL)
ffffffff821aed4b-ffffffff821aed8f: restore_regs.cold (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nr_regs</code>
</li>
<li>
<b>Param removed. </b>
<code>int nr_args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nr_regs</code>
</li>
<li>
<b>Param reordered. </b>
<code>m, prog, nr_regs, stack_size</code> ➡️ <code>m, prog, stack_size</code>
</li>
</ul>
</details>
</li>
</ul>
