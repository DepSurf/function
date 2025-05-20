# Function: <code>reg_type_str</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *reg_type_str(struct bpf_verifier_env *env, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8129361f)
Location: kernel/bpf/verifier.c:533
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:mark_reg_read
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff81278a20-ffffffff81278c4c: reg_type_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *reg_type_str(struct bpf_verifier_env *env, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812cf030)
Location: kernel/bpf/verifier.c:570
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:mark_reg_read
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff812cf030-ffffffff812cf1da: reg_type_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *reg_type_str(struct bpf_verifier_env *env, enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f7010)
Location: kernel/bpf/verifier.c:594
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:mark_reg_read
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff812f7010-ffffffff812f71b6: reg_type_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *reg_type_str(struct bpf_verifier_env *env, enum bpf_reg_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/log.c (ffffffff81345990)
Location: kernel/bpf/log.c:398
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_reg_sane_offset
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_reg_type
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_atomic
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:__check_ptr_off_reg
  - kernel/bpf/verifier.c:mark_reg_read
  - kernel/bpf/log.c:print_reg_state
  - kernel/bpf/log.c:print_reg_state
```
**Symbols:**

```
ffffffff81345990-ffffffff81345b36: reg_type_str (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
