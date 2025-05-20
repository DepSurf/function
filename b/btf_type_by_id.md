# Function: <code>btf_type_by_id</code>

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
In kernel/bpf/btf.c (ffffffff811c9088)
Location: kernel/bpf/btf.c:439
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811dc605)
Location: kernel/bpf/btf.c:518
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811db0e0-ffffffff811db0fe: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f1d65)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_seq_show
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff811f06a0-ffffffff811f06be: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fe475)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_seq_show
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff811fcdb0-ffffffff811fcdce: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225d65)
Location: kernel/bpf/btf.c:607
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:__btf_resolve_helper_id
  - kernel/bpf/btf.c:__btf_resolve_helper_id
  - kernel/bpf/btf.c:__btf_resolve_helper_id
  - kernel/bpf/btf.c:__btf_resolve_helper_id
  - kernel/bpf/btf.c:__btf_resolve_helper_id
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_seq_show
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_resolve_size
  - kernel/bpf/btf.c:btf_resolve_size
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
Direct callers:
  - kernel/bpf/core.c:bpf_prog_ksym_set_name
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff81222f90-ffffffff81222fae: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812250a5)
Location: kernel/bpf/btf.c:707
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_show
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/core.c:bpf_prog_ksym_set_name
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff81229230-ffffffff81229260: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81229b25)
Location: kernel/bpf/btf.c:709
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_show
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff8122dad0-ffffffff8122db00: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81261f25)
Location: kernel/bpf/btf.c:709
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_show
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff81266500-ffffffff81266530: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b8f92)
Location: kernel/bpf/btf.c:804
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_type_show
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_parse_kptrs
  - kernel/bpf/btf.c:btf_parse_kptrs
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_type_skip_modifiers
  - kernel/bpf/btf.c:btf_type_skip_modifiers
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff812b3060-ffffffff812b30a9: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131afa2)
Location: kernel/bpf/btf.c:805
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_type_snprintf_show
  - kernel/bpf/btf.c:btf_type_seq_show_flags
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:get_kern_ctx_btf_id
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_list_node
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff81309d80-ffffffff81309dc9: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8134b025)
Location: kernel/bpf/btf.c:824
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_type_show
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:get_kern_ctx_btf_id
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/trace/trace_probe.c:find_btf_func_proto
  - kernel/trace/trace_probe.c:find_btf_func_proto
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:fetch_kfunc_meta
  - kernel/bpf/verifier.c:fetch_kfunc_meta
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff81338bc0-ffffffff81338c09: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81371805)
Location: kernel/bpf/btf.c:825
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_type_ids_nocast_alias
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_type_show
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_ids_match
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:get_kern_ctx_btf_id
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:btf_parse_kptr
  - kernel/bpf/btf.c:btf_find_decl_tag_value
  - kernel/bpf/btf.c:btf_find_decl_tag_value
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_show
  - kernel/bpf/btf.c:btf_modifier_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:__btf_resolve_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_find_by_name_kind
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/trace/trace_btf.c:btf_find_struct_member
  - kernel/trace/trace_btf.c:btf_find_func_proto
  - kernel/trace/trace_btf.c:btf_find_func_proto
  - kernel/bpf/core.c:bpf_prog_kallsyms_add
  - kernel/bpf/syscall.c:map_check_btf
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:do_check_subprogs
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:fetch_kfunc_meta
  - kernel/bpf/verifier.c:fetch_kfunc_meta
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:__process_kf_arg_ptr_to_graph_node
  - kernel/bpf/verifier.c:check_ptr_to_map_access
  - kernel/bpf/verifier.c:check_ptr_to_btf_access
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:map_kptr_match_type
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:bpf_find_exception_callback_insn_off
  - kernel/bpf/verifier.c:bpf_find_exception_callback_insn_off
  - kernel/bpf/log.c:print_verifier_state
  - kernel/bpf/log.c:print_reg_state
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_type_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_btf_struct_access
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init
```
**Symbols:**

```
ffffffff8135ecf0-ffffffff8135ed39: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff8000102854a0)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffff800010283a20-ffff800010283a6c: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b5a94)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
c04b41d0-c04b41fc: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000033020c)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_seq_show
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
c00000000032e0e0-c00000000032e118: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001ba8ba)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffe0001b9466-ffffffe0001b94ae: btf_type_by_id (STB_GLOBAL)
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
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f6a95)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_seq_show
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff811f53d0-ffffffff811f53ee: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e97e5)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_seq_show
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff811e8120-ffffffff811e813e: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f4865)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_seq_show
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff811f31a0-ffffffff811f31be: btf_type_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct btf_type *btf_type_by_id(const struct btf *btf, u32 type_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81202d75)
Location: kernel/bpf/btf.c:592
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_type_seq_show
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_var_seq_show
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_id_size
Direct callers:
  - kernel/bpf/core.c:bpf_get_prog_name
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/verifier.c:check_btf_info
```
**Symbols:**

```
ffffffff812016b0-ffffffff812016ce: btf_type_by_id (STB_GLOBAL)
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
