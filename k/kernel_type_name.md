# Function: <code>kernel_type_name</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *kernel_type_name(u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120bfcc)
Location: kernel/bpf/verifier.c:536
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:print_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81210190-ffffffff812101b7: kernel_type_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *kernel_type_name(const struct btf *btf, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207549)
Location: kernel/bpf/verifier.c:561
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:print_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
```
**Symbols:**

```
ffffffff81201f10-ffffffff81201f33: kernel_type_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *kernel_type_name(const struct btf *btf, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206573)
Location: kernel/bpf/verifier.c:609
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:print_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
```
**Symbols:**

```
ffffffff81202fe0-ffffffff81203003: kernel_type_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *kernel_type_name(const struct btf *btf, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81239519)
Location: kernel/bpf/verifier.c:610
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:print_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
```
**Symbols:**

```
ffffffff81235040-ffffffff81235063: kernel_type_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *kernel_type_name(const struct btf *btf, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128505b)
Location: kernel/bpf/verifier.c:631
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:print_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
```
**Symbols:**

```
ffffffff81278c50-ffffffff81278c7a: kernel_type_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *kernel_type_name(const struct btf *btf, u32 id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d72d3)
Location: kernel/bpf/verifier.c:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:print_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
```
**Symbols:**

```
ffffffff812ceff0-ffffffff812cf01a: kernel_type_name (STB_LOCAL)
```
</details>
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
<code>const struct btf *btf</code>
</li>
<li>
<b>Param reordered. </b>
<code>id</code> ➡️ <code>btf, id</code>
</li>
</ul>
</details>
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
</ul>
