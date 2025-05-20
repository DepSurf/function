# Function: <code>tnum_equals_const</code>

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
In kernel/bpf/verifier.c (ffffffff811a53ea)
Location: include/linux/tnum.h:54
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
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:mark_map_reg
  - kernel/bpf/verifier.c:check_stack_boundary
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
In kernel/bpf/verifier.c (ffffffff811bbb8d)
Location: include/linux/tnum.h:56
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
  - kernel/bpf/verifier.c:mark_map_reg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811cbb0c)
Location: include/linux/tnum.h:56
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
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811e27fd)
Location: include/linux/tnum.h:56
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811ef0e0)
Location: include/linux/tnum.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff8120213f)
Location: include/linux/tnum.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_stack_boundary
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
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
In kernel/bpf/verifier.c (ffffffff8120505b)
Location: include/linux/tnum.h:60
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
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
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
In kernel/bpf/verifier.c (ffffffff812059eb)
Location: include/linux/tnum.h:60
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
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
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
In kernel/bpf/verifier.c (ffffffff8123857a)
Location: include/linux/tnum.h:60
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
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
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
In kernel/bpf/verifier.c (ffffffff8127c908)
Location: include/linux/tnum.h:60
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
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
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
In kernel/bpf/verifier.c (ffffffff812d2f38)
Location: include/linux/tnum.h:65
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
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
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
In kernel/bpf/verifier.c (ffffffff8130adc7)
Location: include/linux/tnum.h:65
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
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch64_taken
  - kernel/bpf/verifier.c:is_branch32_taken
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:__reg_combine_32_into_64
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
In kernel/bpf/verifier.c (ffffffff8132e8f7)
Location: include/linux/tnum.h:65
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
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
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
In kernel/bpf/verifier.c (ffff800010272948)
Location: include/linux/tnum.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
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
In kernel/bpf/verifier.c (c04984f0)
Location: include/linux/tnum.h:60
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
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
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
In kernel/bpf/verifier.c (c00000000031a314)
Location: include/linux/tnum.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
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
In kernel/bpf/verifier.c (ffffffe0001ab8ce)
Location: include/linux/tnum.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
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
In kernel/bpf/verifier.c (ffffffff811e7700)
Location: include/linux/tnum.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811da4c0)
Location: include/linux/tnum.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811e54d0)
Location: include/linux/tnum.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811f38a0)
Location: include/linux/tnum.h:60
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
</ul>

## Differences
