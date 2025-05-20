# Function: <code>__mark_reg_unknown</code>

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
In kernel/bpf/verifier.c (ffffffff811a7c94)
Location: kernel/bpf/verifier.c:557
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
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
In kernel/bpf/verifier.c (ffffffff811b90a1)
Location: kernel/bpf/verifier.c:684
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __mark_reg_unknown(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c5b50)
Location: kernel/bpf/verifier.c:932
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811c5b50-ffffffff811c5bbb: __mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __mark_reg_unknown(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6a00)
Location: kernel/bpf/verifier.c:991
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffffffff811d6a00-ffffffff811d6a73: __mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3ce0)
Location: kernel/bpf/verifier.c:992
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffffffff811e3ce0-ffffffff811e3d66: __mark_reg_unknown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env *env, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202260)
Location: kernel/bpf/verifier.c:1305
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:clean_func_state
  - kernel/bpf/verifier.c:clean_func_state
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:release_reg_references
  - kernel/bpf/verifier.c:__clear_all_pkt_pointers
  - kernel/bpf/verifier.c:check_stack_boundary
```
**Symbols:**

```
ffffffff81202260-ffffffff81202306: __mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env *env, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201f40)
Location: kernel/bpf/verifier.c:1335
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:clean_func_state
  - kernel/bpf/verifier.c:clean_func_state
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:release_reg_references
  - kernel/bpf/verifier.c:__clear_all_pkt_pointers
  - kernel/bpf/verifier.c:check_stack_boundary
```
**Symbols:**

```
ffffffff81201f40-ffffffff81201fe6: __mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env *env, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203010)
Location: kernel/bpf/verifier.c:1427
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:check_stack_range_initialized
```
**Symbols:**

```
ffffffff81203010-ffffffff812030b6: __mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env *env, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1447
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:check_stack_range_initialized
```
**Symbols:**

```
ffffffff81235c20-ffffffff81235cdf: __mark_reg_unknown (STB_LOCAL)
ffffffff81cb7be8-ffffffff81cb7c05: __mark_reg_unknown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env *env, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1650
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:release_reference
  - kernel/bpf/verifier.c:check_stack_range_initialized
```
**Symbols:**

```
ffffffff81279a70-ffffffff81279b3b: __mark_reg_unknown (STB_LOCAL)
ffffffff81e68dba-ffffffff81e68dd7: __mark_reg_unknown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env *env, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1864
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
```
**Symbols:**

```
ffffffff812cf7a0-ffffffff812cf85e: __mark_reg_unknown (STB_LOCAL)
ffffffff8205fa55-ffffffff8205fa6a: __mark_reg_unknown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env *env, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:2261
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:clean_live_states
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:process_spin_lock
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:invalidate_dynptr
  - kernel/bpf/verifier.c:invalidate_dynptr
```
**Symbols:**

```
ffffffff812f8c50-ffffffff812f8d0e: __mark_reg_unknown (STB_LOCAL)
ffffffff820dea93-ffffffff820deaa8: __mark_reg_unknown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env *env, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:2267
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_rbtree_add_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_user_ringbuf_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_find_vma_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_timer_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:set_loop_callback_state
  - kernel/bpf/verifier.c:map_set_for_each_callback_args
  - kernel/bpf/verifier.c:invalidate_non_owning_refs
  - kernel/bpf/verifier.c:invalidate_non_owning_refs
  - kernel/bpf/verifier.c:invalidate_non_owning_refs
  - kernel/bpf/verifier.c:invalidate_non_owning_refs
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:clear_all_pkt_pointers
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:invalidate_dynptr
  - kernel/bpf/verifier.c:invalidate_dynptr
```
**Symbols:**

```
ffffffff81317fe0-ffffffff8131809e: __mark_reg_unknown (STB_LOCAL)
ffffffff821baaf7-ffffffff821bab0c: __mark_reg_unknown.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010266b78)
Location: kernel/bpf/verifier.c:992
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffff800010266b78-ffff800010266c00: __mark_reg_unknown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __mark_reg_unknown(const struct bpf_verifier_env *env, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0498860)
Location: kernel/bpf/verifier.c:992
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
c0498860-c0498900: __mark_reg_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030c090)
Location: kernel/bpf/verifier.c:992
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
c00000000030c090-c00000000030c120: __mark_reg_unknown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a28a6)
Location: kernel/bpf/verifier.c:992
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffffffe0001a28a6-ffffffe0001a2924: __mark_reg_unknown.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dc300)
Location: kernel/bpf/verifier.c:992
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffffffff811dc300-ffffffff811dc386: __mark_reg_unknown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cf0c0)
Location: kernel/bpf/verifier.c:992
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffffffff811cf0c0-ffffffff811cf146: __mark_reg_unknown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da0d0)
Location: kernel/bpf/verifier.c:992
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffffffff811da0d0-ffffffff811da156: __mark_reg_unknown.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e84e0)
Location: kernel/bpf/verifier.c:992
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffffffff811e84e0-ffffffff811e8566: __mark_reg_unknown.isra.0 (STB_LOCAL)
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
</ul>
