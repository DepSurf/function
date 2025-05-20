# Function: <code>check_ptr_off_reg</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int check_ptr_off_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128b854)
Location: kernel/bpf/verifier.c:3647
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81290160-ffffffff8129017e: check_ptr_off_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int check_ptr_off_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e40c8)
Location: kernel/bpf/verifier.c:4089
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812e9130-ffffffff812e914e: check_ptr_off_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int check_ptr_off_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8130ee37)
Location: kernel/bpf/verifier.c:4974
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81315380-ffffffff8131539e: check_ptr_off_reg (STB_GLOBAL)
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
In kernel/bpf/verifier.c (ffffffff8132f067)
Location: kernel/bpf/verifier.c:5132
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_mem_access
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
</ul>
