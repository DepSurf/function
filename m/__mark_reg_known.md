# Function: <code>__mark_reg_known</code>

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
In kernel/bpf/verifier.c (ffffffff811a75ef)
Location: kernel/bpf/verifier.c:434
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:mark_map_reg
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
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
In kernel/bpf/verifier.c (ffffffff811bd870)
Location: kernel/bpf/verifier.c:554
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:mark_map_reg
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c5bc0)
Location: kernel/bpf/verifier.c:801
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811c5bc0-ffffffff811c5c0e: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6a80)
Location: kernel/bpf/verifier.c:860
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811d6a80-ffffffff811d6ad6: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e30e0)
Location: kernel/bpf/verifier.c:861
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e30e0-ffffffff811e3136: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120e299)
Location: kernel/bpf/verifier.c:991
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
Direct callers:
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:reg_set_min_max
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read
```
**Symbols:**

```
ffffffff81202400-ffffffff81202466: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120eaa6)
Location: kernel/bpf/verifier.c:1032
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
Direct callers:
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_read
```
**Symbols:**

```
ffffffff81203160-ffffffff812031c6: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120b4b6)
Location: kernel/bpf/verifier.c:1081
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
Direct callers:
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:mark_reg_stack_read
```
**Symbols:**

```
ffffffff81203f20-ffffffff81203f86: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123f1da)
Location: kernel/bpf/verifier.c:1090
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff81236180-ffffffff812361e6: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127a460)
Location: kernel/bpf/verifier.c:1317
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff8127a460-ffffffff8127a4de: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d0bd0)
Location: kernel/bpf/verifier.c:1518
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
```
**Symbols:**

```
ffffffff812d0bd0-ffffffff812d0c4e: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fc580)
Location: kernel/bpf/verifier.c:1895
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
```
**Symbols:**

```
ffffffff812fc580-ffffffff812fc5fe: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131a790)
Location: kernel/bpf/verifier.c:1745
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:init_reg_state
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
```
**Symbols:**

```
ffffffff8131a790-ffffffff8131a80e: __mark_reg_known (STB_LOCAL)
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
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff8000102663a0)
Location: kernel/bpf/verifier.c:861
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffff8000102663a0-ffff8000102663ec: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0498900)
Location: kernel/bpf/verifier.c:861
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c0498900-c04989ac: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030b0e0)
Location: kernel/bpf/verifier.c:861
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c00000000030b0e0-c00000000030b15c: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a17ec)
Location: kernel/bpf/verifier.c:861
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffe0001a17ec-ffffffe0001a1840: __mark_reg_known (STB_LOCAL)
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
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db700)
Location: kernel/bpf/verifier.c:861
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811db700-ffffffff811db756: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ce4c0)
Location: kernel/bpf/verifier.c:861
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811ce4c0-ffffffff811ce516: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d94d0)
Location: kernel/bpf/verifier.c:861
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811d94d0-ffffffff811d9526: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __mark_reg_known(struct bpf_reg_state *reg, u64 imm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e78e0)
Location: kernel/bpf/verifier.c:861
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:reg_set_min_max_inv
  - kernel/bpf/verifier.c:check_alu_op
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e78e0-ffffffff811e7936: __mark_reg_known (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
