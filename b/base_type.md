# Function: <code>base_type</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812938c6)
Location: include/linux/bpf_verifier.h:581
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:reg_type_mismatch
  - kernel/bpf/verifier.c:reg_type_mismatch
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
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
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
```
In kernel/bpf/btf.c (ffffffff812b85d7)
Location: include/linux/bpf_verifier.h:581
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_ctx_access
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
In kernel/bpf/verifier.c (ffffffff812ee357)
Location: include/linux/bpf_verifier.h:653
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:reg_type_mismatch
  - kernel/bpf/verifier.c:reg_type_mismatch
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
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
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:reg_type_str
  - kernel/bpf/verifier.c:reg_type_str
  - kernel/bpf/verifier.c:reg_btf_record
```
```
In kernel/bpf/btf.c (ffffffff81317141)
Location: include/linux/bpf_verifier.h:653
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f2cb32)
Location: include/linux/bpf_verifier.h:653
Inline: True
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
In kernel/bpf/verifier.c (ffffffff8131ac27)
Location: include/linux/bpf_verifier.h:717
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:save_aux_ptr_type
  - kernel/bpf/verifier.c:save_aux_ptr_type
  - kernel/bpf/verifier.c:save_aux_ptr_type
  - kernel/bpf/verifier.c:save_aux_ptr_type
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:get_dynptr_arg_reg
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:reg_type_str
  - kernel/bpf/verifier.c:reg_type_str
  - kernel/bpf/verifier.c:reg_btf_record
```
```
In kernel/bpf/btf.c (ffffffff81346d99)
Location: include/linux/bpf_verifier.h:717
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f8c7d2)
Location: include/linux/bpf_verifier.h:717
Inline: True
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
In kernel/bpf/verifier.c (ffffffff8133c9cd)
Location: include/linux/bpf_verifier.h:819
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:save_aux_ptr_type
  - kernel/bpf/verifier.c:save_aux_ptr_type
  - kernel/bpf/verifier.c:save_aux_ptr_type
  - kernel/bpf/verifier.c:save_aux_ptr_type
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:is_branch_taken
  - kernel/bpf/verifier.c:is_branch_taken
  - kernel/bpf/verifier.c:is_branch_taken
  - kernel/bpf/verifier.c:is_branch_taken
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:invalidate_non_owning_refs
  - kernel/bpf/verifier.c:invalidate_non_owning_refs
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:get_dynptr_arg_reg
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
```
```
In kernel/bpf/log.c (ffffffff81345c60)
Location: include/linux/bpf_verifier.h:819
Inline: True
Inline callers:
  - kernel/bpf/log.c:print_reg_state
  - kernel/bpf/log.c:print_reg_state
  - kernel/bpf/log.c:print_reg_state
  - kernel/bpf/log.c:print_reg_state
  - kernel/bpf/log.c:print_reg_state
  - kernel/bpf/log.c:reg_type_str
  - kernel/bpf/log.c:reg_type_str
```
```
In kernel/bpf/btf.c (ffffffff8136d18c)
Location: include/linux/bpf_verifier.h:819
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff82059fd2)
Location: include/linux/bpf_verifier.h:819
Inline: True
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
