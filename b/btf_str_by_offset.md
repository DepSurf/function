# Function: <code>btf_str_by_offset</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122c355)
Location: kernel/bpf/btf.c:645
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:__btf_name_valid
  - kernel/bpf/btf.c:btf_find_by_name_kind
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
In kernel/bpf/btf.c (ffffffff812313b3)
Location: kernel/bpf/btf.c:647
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
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:__btf_name_valid
  - kernel/bpf/btf.c:btf_find_by_name_kind
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
In kernel/bpf/btf.c (ffffffff8126a303)
Location: kernel/bpf/btf.c:647
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
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:__btf_name_valid
  - kernel/bpf/btf.c:btf_find_by_name_kind
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
In kernel/bpf/btf.c (ffffffff812b8ffd)
Location: kernel/bpf/btf.c:742
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
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_parse_kptrs
  - kernel/bpf/btf.c:btf_parse_kptrs
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:__btf_name_valid
  - kernel/bpf/btf.c:btf_find_by_name_kind
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
In kernel/bpf/btf.c (ffffffff8131b00d)
Location: kernel/bpf/btf.c:743
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
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:__btf_name_valid
  - kernel/bpf/btf.c:btf_find_by_name_kind
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
In kernel/bpf/btf.c (ffffffff8134b0ac)
Location: kernel/bpf/btf.c:765
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
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
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:__btf_name_valid
  - kernel/bpf/btf.c:btf_find_by_name_kind
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
In kernel/bpf/btf.c (ffffffff8137188c)
Location: kernel/bpf/btf.c:766
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:btf_find_decl_tag_value
  - kernel/bpf/btf.c:btf_find_decl_tag_value
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:__btf_name_valid
  - kernel/bpf/btf.c:btf_find_by_name_kind
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
