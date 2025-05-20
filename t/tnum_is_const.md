# Function: <code>tnum_is_const</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:50
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:50
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:50
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:54
Inline: True
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
In kernel/bpf/verifier.c (ffffffff8120d3da)
Location: include/linux/tnum.h:54
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:print_verifier_state
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
In kernel/bpf/verifier.c (ffffffff8120bcd8)
Location: include/linux/tnum.h:54
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:__check_stack_boundary
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:print_verifier_state
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
In kernel/bpf/verifier.c (ffffffff8120d873)
Location: include/linux/tnum.h:54
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:print_verifier_state
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
In kernel/bpf/verifier.c (ffffffff81241b78)
Location: include/linux/tnum.h:54
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:print_verifier_state
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
In kernel/bpf/verifier.c (ffffffff81286d26)
Location: include/linux/tnum.h:54
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:print_verifier_state
```
```
In kernel/bpf/btf.c (ffffffff812b8336)
Location: include/linux/tnum.h:54
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
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
In kernel/bpf/verifier.c (ffffffff812e215e)
Location: include/linux/tnum.h:59
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_head
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:check_stack_read
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:dynptr_get_spi
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
In kernel/bpf/verifier.c (ffffffff8130f9a8)
Location: include/linux/tnum.h:59
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:stack_slot_obj_get_spi
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
In kernel/bpf/verifier.c (ffffffff8132e8f7)
Location: include/linux/tnum.h:59
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:try_match_pkt_pointers
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:regs_refine_cond_op
  - kernel/bpf/verifier.c:is_branch_taken
  - kernel/bpf/verifier.c:is_branch_taken
  - kernel/bpf/verifier.c:is_scalar_branch_taken
  - kernel/bpf/verifier.c:is_scalar_branch_taken
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:sanitize_check_bounds
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_reg_const_str
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_stack_access_within_bounds
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:coerce_reg_to_size_sx
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:stack_slot_obj_get_spi
```
```
In kernel/bpf/log.c (ffffffff81345c2a)
Location: include/linux/tnum.h:59
Inline: True
Inline callers:
  - kernel/bpf/log.c:print_reg_state
  - kernel/bpf/log.c:print_reg_state
  - kernel/bpf/log.c:print_reg_state
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:54
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:54
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:54
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:54
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:54
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:54
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:54
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: include/linux/tnum.h:54
Inline: True
```
</details>
</li>
</ul>

## Differences
