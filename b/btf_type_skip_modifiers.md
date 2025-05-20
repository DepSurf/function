# Function: <code>btf_type_skip_modifiers</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_skip_modifiers(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81222975)
Location: kernel/bpf/btf.c:404
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
**Symbols:**

```
ffffffff81222e20-ffffffff81222e71: btf_type_skip_modifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_skip_modifiers(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122896c)
Location: kernel/bpf/btf.c:493
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_array_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
**Symbols:**

```
ffffffff81228040-ffffffff812280d1: btf_type_skip_modifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_skip_modifiers(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812307d2)
Location: kernel/bpf/btf.c:494
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_array_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
**Symbols:**

```
ffffffff8122cb40-ffffffff8122cbd3: btf_type_skip_modifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_skip_modifiers(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126954d)
Location: kernel/bpf/btf.c:494
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_array_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
**Symbols:**

```
ffffffff812654a0-ffffffff81265533: btf_type_skip_modifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct btf_type *btf_type_skip_modifiers(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b1530)
Location: kernel/bpf/btf.c:581
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:__btf_type_is_scalar_struct
  - kernel/bpf/btf.c:__btf_type_is_scalar_struct
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_array_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
**Symbols:**

```
ffffffff812b1530-ffffffff812b15db: btf_type_skip_modifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_skip_modifiers(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813165c7)
Location: kernel/bpf/btf.c:576
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
Direct callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_array_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
**Symbols:**

```
ffffffff81311990-ffffffff81311a3b: btf_type_skip_modifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_skip_modifiers(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81346498)
Location: kernel/bpf/btf.c:599
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
Direct callers:
  - kernel/trace/trace_probe.c:type_from_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_array_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
**Symbols:**

```
ffffffff81341220-ffffffff813412d0: btf_type_skip_modifiers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_skip_modifiers(const struct btf *btf, u32 id, u32 *res_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81368223)
Location: kernel/bpf/btf.c:600
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_type_match
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:parse_btf_arg
  - kernel/trace/trace_btf.c:btf_find_struct_member
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_array_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
**Symbols:**

```
ffffffff81367740-ffffffff813677f0: btf_type_skip_modifiers (STB_GLOBAL)
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
