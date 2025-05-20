# Function: <code>tnum_subreg</code>

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
struct tnum tnum_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215540)
Location: kernel/bpf/tnum.c:198
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:scalar32_min_max_or
  - kernel/bpf/verifier.c:scalar32_min_max_or
  - kernel/bpf/verifier.c:scalar32_min_max_or
  - kernel/bpf/verifier.c:scalar32_min_max_and
  - kernel/bpf/verifier.c:scalar32_min_max_and
  - kernel/bpf/verifier.c:scalar32_min_max_and
  - kernel/bpf/verifier.c:__reg_bound_offset
  - kernel/bpf/verifier.c:__update_reg32_bounds
```
**Symbols:**

```
ffffffff81215540-ffffffff8121554f: tnum_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tnum tnum_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812171e0)
Location: kernel/bpf/tnum.c:198
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:scalar32_min_max_xor
  - kernel/bpf/verifier.c:scalar32_min_max_xor
  - kernel/bpf/verifier.c:scalar32_min_max_xor
  - kernel/bpf/verifier.c:scalar32_min_max_or
  - kernel/bpf/verifier.c:scalar32_min_max_or
  - kernel/bpf/verifier.c:scalar32_min_max_or
  - kernel/bpf/verifier.c:scalar32_min_max_and
  - kernel/bpf/verifier.c:scalar32_min_max_and
  - kernel/bpf/verifier.c:scalar32_min_max_and
  - kernel/bpf/verifier.c:__reg_bound_offset
  - kernel/bpf/verifier.c:__update_reg32_bounds
```
**Symbols:**

```
ffffffff812171e0-ffffffff812171ef: tnum_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tnum tnum_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a630)
Location: kernel/bpf/tnum.c:198
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:__reg_bound_offset
  - kernel/bpf/verifier.c:__update_reg32_bounds
```
**Symbols:**

```
ffffffff8121a630-ffffffff8121a63f: tnum_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tnum tnum_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81251430)
Location: kernel/bpf/tnum.c:201
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:__reg_bound_offset
  - kernel/bpf/verifier.c:__update_reg32_bounds
```
**Symbols:**

```
ffffffff81251430-ffffffff8125143f: tnum_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tnum tnum_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298f10)
Location: kernel/bpf/tnum.c:201
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:__update_reg32_bounds
```
**Symbols:**

```
ffffffff81298f10-ffffffff81298f27: tnum_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tnum tnum_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4c20)
Location: kernel/bpf/tnum.c:201
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:__update_reg32_bounds
```
**Symbols:**

```
ffffffff812f4c20-ffffffff812f4c37: tnum_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tnum tnum_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff813220b0)
Location: kernel/bpf/tnum.c:201
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:__update_reg32_bounds
```
**Symbols:**

```
ffffffff813220b0-ffffffff813220c7: tnum_subreg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_subreg(struct tnum a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81344a35)
Location: kernel/bpf/tnum.c:195
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_with_subreg
Direct callers:
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:is_branch_taken
  - kernel/bpf/verifier.c:is_branch_taken
  - kernel/bpf/verifier.c:is_branch_taken
  - kernel/bpf/verifier.c:is_scalar_branch_taken
  - kernel/bpf/verifier.c:is_scalar_branch_taken
  - kernel/bpf/verifier.c:is_scalar_branch_taken
  - kernel/bpf/verifier.c:is_scalar_branch_taken
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sanity_check
  - kernel/bpf/verifier.c:reg_bounds_sanity_check
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:__update_reg32_bounds
```
**Symbols:**

```
ffffffff813449c0-ffffffff813449d7: tnum_subreg (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
