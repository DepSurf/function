# Function: <code>btf_name_by_offset</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c767d)
Location: kernel/bpf/btf.c:429
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_seq_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811db0c0)
Location: kernel/bpf/btf.c:510
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
ffffffff811db0c0-ffffffff811db0db: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f0680)
Location: kernel/bpf/btf.c:584
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
ffffffff811f0680-ffffffff811f069b: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fcd90)
Location: kernel/bpf/btf.c:584
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
ffffffff811fcd90-ffffffff811fcdab: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225a37)
Location: kernel/bpf/btf.c:599
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/core.c:bpf_prog_ksym_set_name
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff81222f70-ffffffff81222f88: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122c355)
Location: kernel/bpf/btf.c:702
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/core.c:bpf_prog_ksym_set_name
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff81229200-ffffffff8122922c: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812313b3)
Location: kernel/bpf/btf.c:704
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff8122daa0-ffffffff8122dacc: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126a303)
Location: kernel/bpf/btf.c:704
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
**Symbols:**

```
ffffffff812664d0-ffffffff812664fc: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b8ffd)
Location: kernel/bpf/btf.c:799
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
```
**Symbols:**

```
ffffffff812b3020-ffffffff812b305d: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131b00d)
Location: kernel/bpf/btf.c:800
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:is_kfunc_arg_scalar_with_name
  - kernel/bpf/verifier.c:__kfunc_param_match_suffix
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
```
**Symbols:**

```
ffffffff81313480-ffffffff813134bd: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8134b0ac)
Location: kernel/bpf/btf.c:819
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/trace/trace_probe.c:sprint_nth_btf_arg
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:fetch_kfunc_meta
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:is_kfunc_arg_scalar_with_name
  - kernel/bpf/verifier.c:__kfunc_param_match_suffix
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
```
**Symbols:**

```
ffffffff81343150-ffffffff8134318d: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8137188c)
Location: kernel/bpf/btf.c:820
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/trace/trace_probe.c:sprint_nth_btf_arg
  - kernel/trace/trace_probe.c:parse_btf_arg
  - kernel/trace/trace_btf.c:btf_find_struct_member
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:do_check_subprogs
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_btf_line
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:fetch_kfunc_meta
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:is_kfunc_arg_scalar_with_name
  - kernel/bpf/verifier.c:__kfunc_param_match_suffix
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/log.c:print_verifier_state
  - kernel/bpf/log.c:print_reg_state
  - kernel/bpf/log.c:verbose_linfo
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
```
**Symbols:**

```
ffffffff81369080-ffffffff813690bd: btf_name_by_offset (STB_GLOBAL)
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
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff8000102839d0)
Location: kernel/bpf/btf.c:584
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
ffff8000102839d0-ffff800010283a1c: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b41a4)
Location: kernel/bpf/btf.c:584
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
c04b41a4-c04b41d0: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032e0b0)
Location: kernel/bpf/btf.c:584
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
c00000000032e0b0-c00000000032e0d8: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b942c)
Location: kernel/bpf/btf.c:584
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
ffffffe0001b942c-ffffffe0001b9466: btf_name_by_offset (STB_GLOBAL)
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
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f53b0)
Location: kernel/bpf/btf.c:584
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
ffffffff811f53b0-ffffffff811f53cb: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e8100)
Location: kernel/bpf/btf.c:584
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
ffffffff811e8100-ffffffff811e811b: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f3180)
Location: kernel/bpf/btf.c:584
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
ffffffff811f3180-ffffffff811f319b: btf_name_by_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *btf_name_by_offset(const struct btf *btf, u32 offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81201690)
Location: kernel/bpf/btf.c:584
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:check_btf_info
  - kernel/bpf/verifier.c:verbose_linfo
```
**Symbols:**

```
ffffffff81201690-ffffffff812016ab: btf_name_by_offset (STB_GLOBAL)
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
