# Function: <code>mark_reg_unknown</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a35a0)
Location: kernel/bpf/verifier.c:566
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811a35a0-ffffffff811a368c: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b8490)
Location: kernel/bpf/verifier.c:694
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811b8490-ffffffff811b8586: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c7820)
Location: kernel/bpf/verifier.c:945
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811c6900-ffffffff811c6933: mark_reg_unknown.part.48 (STB_LOCAL)
ffffffff811c7820-ffffffff811c7861: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e550e)
Location: kernel/bpf/verifier.c:1004
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811daef0-ffffffff811daf4d: mark_reg_unknown (STB_LOCAL)
ffffffff811e54e4-ffffffff811e552b: mark_reg_unknown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7620)
Location: kernel/bpf/verifier.c:1008
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811e7620-ffffffff811e769d: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812069d0)
Location: kernel/bpf/verifier.c:1320
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:release_reg_references
  - kernel/bpf/verifier.c:__clear_all_pkt_pointers
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff812069d0-ffffffff81206a3c: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812067a0)
Location: kernel/bpf/verifier.c:1350
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:release_reg_references
  - kernel/bpf/verifier.c:__clear_all_pkt_pointers
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff812067a0-ffffffff8120680c: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81208700)
Location: kernel/bpf/verifier.c:1442
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff81208700-ffffffff8120876c: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8124b92e)
Location: kernel/bpf/verifier.c:1462
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__check_func_call
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff8123c100-ffffffff8123c16c: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128b8c4)
Location: kernel/bpf/verifier.c:1665
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__check_func_call
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:release_reference
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff81281c50-ffffffff81281cc3: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e4138)
Location: kernel/bpf/verifier.c:1879
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__check_func_call
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff812d7690-ffffffff812d7703: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8130eea7)
Location: kernel/bpf/verifier.c:2278
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:mark_reg_stack_read
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff812faea0-ffffffff812faf13: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8132f0e8)
Location: kernel/bpf/verifier.c:2284
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:sanitize_speculative_path
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:__check_reg_arg
```
**Symbols:**

```
ffffffff8131a650-ffffffff8131a6c3: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026afc0)
Location: kernel/bpf/verifier.c:1008
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffff8000102680a0-ffff8000102680fc: mark_reg_unknown.part.0 (STB_LOCAL)
ffff80001026afc0-ffff80001026b048: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049d0d4)
Location: kernel/bpf/verifier.c:1008
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
c049d0d4-c049d15c: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000310e90)
Location: kernel/bpf/verifier.c:1008
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
c000000000310e90-c000000000310f64: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a5694)
Location: kernel/bpf/verifier.c:1008
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffe0001a33e8-ffffffe0001a3440: mark_reg_unknown.part.0 (STB_LOCAL)
ffffffe0001a5694-ffffffe0001a571a: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dfc40)
Location: kernel/bpf/verifier.c:1008
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811dfc40-ffffffff811dfcbd: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d2a00)
Location: kernel/bpf/verifier.c:1008
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811d2a00-ffffffff811d2a7d: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dda10)
Location: kernel/bpf/verifier.c:1008
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811dda10-ffffffff811dda8d: mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_unknown(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ebe20)
Location: kernel/bpf/verifier.c:1008
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_reg_arg
```
**Symbols:**

```
ffffffff811ebe20-ffffffff811ebe9d: mark_reg_unknown (STB_LOCAL)
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
