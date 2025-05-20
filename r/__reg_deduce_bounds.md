# Function: <code>__reg_deduce_bounds</code>

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
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a12c0)
Location: kernel/bpf/verifier.c:505
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
```
**Symbols:**

```
ffffffff811a12c0-ffffffff811a1337: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b6770)
Location: kernel/bpf/verifier.c:632
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811b6770-ffffffff811b67e7: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c58c0)
Location: kernel/bpf/verifier.c:880
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811c58c0-ffffffff811c5937: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6770)
Location: kernel/bpf/verifier.c:939
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811d6770-ffffffff811d67e7: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e2e50)
Location: kernel/bpf/verifier.c:940
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e2e50-ffffffff811e2ec7: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204076)
Location: kernel/bpf/verifier.c:1202
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
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
In kernel/bpf/verifier.c (ffffffff81204006)
Location: kernel/bpf/verifier.c:1234
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
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
In kernel/bpf/verifier.c (ffffffff81204fde)
Location: kernel/bpf/verifier.c:1328
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
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
In kernel/bpf/verifier.c (ffffffff81237b0e)
Location: kernel/bpf/verifier.c:1342
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__reg_combine_64_into_32
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
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
In kernel/bpf/verifier.c (ffffffff8127bcd4)
Location: kernel/bpf/verifier.c:1546
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_bounds_sync
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
In kernel/bpf/verifier.c (ffffffff812d22b4)
Location: kernel/bpf/verifier.c:1760
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_bounds_sync
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
In kernel/bpf/verifier.c (ffffffff81307773)
Location: kernel/bpf/verifier.c:2157
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_bounds_sync
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
In kernel/bpf/verifier.c (ffffffff81326faf)
Location: kernel/bpf/verifier.c:2156
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:reg_bounds_sync
  - kernel/bpf/verifier.c:reg_bounds_sync
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
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff8000102661e0)
Location: kernel/bpf/verifier.c:940
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffff8000102661e0-ffff800010266264: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0497fd8)
Location: kernel/bpf/verifier.c:940
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
c0497fd8-c0498098: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030aec0)
Location: kernel/bpf/verifier.c:940
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
c00000000030aec0-c00000000030af88: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a167c)
Location: kernel/bpf/verifier.c:940
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffe0001a167c-ffffffe0001a16ea: __reg_deduce_bounds (STB_LOCAL)
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
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db470)
Location: kernel/bpf/verifier.c:940
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811db470-ffffffff811db4e7: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ce230)
Location: kernel/bpf/verifier.c:940
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811ce230-ffffffff811ce2a7: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d9240)
Location: kernel/bpf/verifier.c:940
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811d9240-ffffffff811d92b7: __reg_deduce_bounds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __reg_deduce_bounds(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7650)
Location: kernel/bpf/verifier.c:940
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:__reg_combine_min_max
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e7650-ffffffff811e76c7: __reg_deduce_bounds (STB_LOCAL)
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
