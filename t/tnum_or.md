# Function: <code>tnum_or</code>

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
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811a9850)
Location: kernel/bpf/tnum.c:80
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811a9850-ffffffff811a9871: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811c0d50)
Location: kernel/bpf/tnum.c:90
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811c0d50-ffffffff811c0d6d: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811d2250)
Location: kernel/bpf/tnum.c:90
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811d2250-ffffffff811d226d: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e69b0)
Location: kernel/bpf/tnum.c:91
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e69b0-ffffffff811e69cd: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f3110)
Location: kernel/bpf/tnum.c:96
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811f3110-ffffffff811f312d: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81215575)
Location: kernel/bpf/tnum.c:96
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff81215380-ffffffff8121539d: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81217215)
Location: kernel/bpf/tnum.c:96
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff81217020-ffffffff8121703d: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff8121a665)
Location: kernel/bpf/tnum.c:96
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff8121a470-ffffffff8121a48d: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81251465)
Location: kernel/bpf/tnum.c:96
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:__reg_bound_offset
```
**Symbols:**

```
ffffffff81251260-ffffffff8125127d: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81298f65)
Location: kernel/bpf/tnum.c:96
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff81298cd0-ffffffff81298cf7: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff812f4c95)
Location: kernel/bpf/tnum.c:96
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff812f4960-ffffffff812f4987: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81322125)
Location: kernel/bpf/tnum.c:96
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_const_subreg
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff81321df0-ffffffff81321e17: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff81344a35)
Location: kernel/bpf/tnum.c:96
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_with_subreg
Direct callers:
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:reg_bounds_sync
```
**Symbols:**

```
ffffffff81344700-ffffffff81344727: tnum_or (STB_GLOBAL)
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
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffff800010276df0)
Location: kernel/bpf/tnum.c:96
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffff800010276df0-ffff800010276e34: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c04a94c0)
Location: kernel/bpf/tnum.c:96
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c04a94c0-c04a952c: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (c00000000031f250)
Location: kernel/bpf/tnum.c:96
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c00000000031f250-c00000000031f26c: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffe0001af12a)
Location: kernel/bpf/tnum.c:96
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffe0001af12a-ffffffe0001af16e: tnum_or (STB_GLOBAL)
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
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811eb730)
Location: kernel/bpf/tnum.c:96
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811eb730-ffffffff811eb74d: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811de4c0)
Location: kernel/bpf/tnum.c:96
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811de4c0-ffffffff811de4dd: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811e9500)
Location: kernel/bpf/tnum.c:96
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e9500-ffffffff811e951d: tnum_or (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tnum tnum_or(struct tnum a, struct tnum b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/tnum.c (ffffffff811f78d0)
Location: kernel/bpf/tnum.c:96
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811f78d0-ffffffff811f78ed: tnum_or (STB_GLOBAL)
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
