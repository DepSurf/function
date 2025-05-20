# Function: <code>tnum_const</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811a9710)
Location: kernel/bpf/tnum.c:15
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:mark_map_reg
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff811a9710-ffffffff811a9724: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0c10)
Location: kernel/bpf/tnum.c:15
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:mark_map_reg
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811c0c10-ffffffff811c0c20: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d2110)
Location: kernel/bpf/tnum.c:15
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffff811d2110-ffffffff811d2120: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e6870)
Location: kernel/bpf/tnum.c:16
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffff811e6870-ffffffff811e6880: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f2fc0)
Location: kernel/bpf/tnum.c:16
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffff811f2fc0-ffffffff811f2fd0: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215230)
Location: kernel/bpf/tnum.c:16
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81215230-ffffffff81215240: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81216ed0)
Location: kernel/bpf/tnum.c:16
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81216ed0-ffffffff81216ee0: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a320)
Location: kernel/bpf/tnum.c:16
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff8121a320-ffffffff8121a330: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81251080)
Location: kernel/bpf/tnum.c:16
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81251080-ffffffff81251090: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298a80)
Location: kernel/bpf/tnum.c:16
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
```
**Symbols:**

```
ffffffff81298a80-ffffffff81298a96: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4690)
Location: kernel/bpf/tnum.c:16
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffff812f4690-ffffffff812f46a6: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81321b40)
Location: kernel/bpf/tnum.c:16
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffff81321b40-ffffffff81321b56: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81344a85)
Location: kernel/bpf/tnum.c:16
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:coerce_reg_to_size_sx
  - kernel/bpf/verifier.c:coerce_reg_to_size_sx
  - kernel/bpf/verifier.c:coerce_reg_to_size_sx
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffff81344450-ffffffff81344466: tnum_const (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276b60)
Location: kernel/bpf/tnum.c:16
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffff800010276b60-ffff800010276b8c: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a90c4)
Location: kernel/bpf/tnum.c:16
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
c04a90c4-c04a90f4: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f0e0)
Location: kernel/bpf/tnum.c:16
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
c00000000031f0e0-c00000000031f0f0: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001aee52)
Location: kernel/bpf/tnum.c:16
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffe0001aee52-ffffffe0001aee76: tnum_const (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb5e0)
Location: kernel/bpf/tnum.c:16
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffff811eb5e0-ffffffff811eb5f0: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de370)
Location: kernel/bpf/tnum.c:16
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffff811de370-ffffffff811de380: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e93b0)
Location: kernel/bpf/tnum.c:16
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffff811e93b0-ffffffff811e93c0: tnum_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tnum tnum_const(u64 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f7780)
Location: kernel/bpf/tnum.c:16
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:check_ptr_alignment
  - kernel/bpf/verifier.c:__mark_reg_known
```
**Symbols:**

```
ffffffff811f7780-ffffffff811f7790: tnum_const (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
