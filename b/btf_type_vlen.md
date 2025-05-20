# Function: <code>btf_type_vlen</code>

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
In kernel/bpf/btf.c (ffffffff811c6e73)
Location: kernel/bpf/btf.c:393
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
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
In kernel/bpf/btf.c (ffffffff811dc258)
Location: kernel/bpf/btf.c:421
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
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
In kernel/bpf/btf.c (ffffffff811f199a)
Location: kernel/bpf/btf.c:464
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
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
In kernel/bpf/btf.c (ffffffff811fe0aa)
Location: kernel/bpf/btf.c:464
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206071)
Location: include/linux/btf.h:110
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
```
```
In kernel/bpf/btf.c (ffffffff81225470)
Location: include/linux/btf.h:110
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_func_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_seq_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122f79c)
Location: include/linux/btf.h:110
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81205c21)
Location: include/linux/btf.h:170
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff8122bce0)
Location: include/linux/btf.h:170
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_func_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81237c9c)
Location: include/linux/btf.h:170
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207a2f)
Location: include/linux/btf.h:180
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff81230ce3)
Location: include/linux/btf.h:180
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123c4b9)
Location: include/linux/btf.h:180
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123b2bf)
Location: include/linux/btf.h:181
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81269bb3)
Location: include/linux/btf.h:181
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81276e75)
Location: include/linux/btf.h:181
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
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
In kernel/bpf/verifier.c (ffffffff81280ddf)
Location: include/linux/btf.h:267
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff812b24b1)
Location: include/linux/btf.h:267
Inline: True
Inline callers:
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__btf_type_is_scalar_struct
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6a9f)
Location: include/linux/btf.h:267
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In tools/lib/bpf/relo_core.c (ffffffff812c9b6b)
Location: include/linux/btf.h:267
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81cb688b)
Location: include/linux/btf.h:267
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
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
In kernel/bpf/verifier.c (ffffffff812d8b3f)
Location: include/linux/btf.h:369
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff81317bd8)
Location: include/linux/btf.h:369
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c30f)
Location: include/linux/btf.h:369
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In kernel/bpf/bpf_lsm.c (ffffffff8132fff4)
Location: include/linux/btf.h:369
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim
```
```
In tools/lib/bpf/relo_core.c (ffffffff81332ec4)
Location: include/linux/btf.h:369
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81e74dfb)
Location: include/linux/btf.h:369
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
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
In kernel/trace/trace_probe.c (ffffffff812d77fb)
Location: include/linux/btf.h:385
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffff812f7c4f)
Location: include/linux/btf.h:385
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff8134aed3)
Location: include/linux/btf.h:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135bff1)
Location: include/linux/btf.h:385
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_mem_usage
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In kernel/bpf/bpf_lsm.c (ffffffff81360c94)
Location: include/linux/btf.h:385
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim
```
```
In tools/lib/bpf/relo_core.c (ffffffff81363b7f)
Location: include/linux/btf.h:385
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81ed0feb)
Location: include/linux/btf.h:385
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
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
In kernel/trace/trace_btf.c (ffffffff812f856e)
Location: include/linux/btf.h:396
Inline: True
Inline callers:
  - kernel/trace/trace_btf.c:btf_find_struct_member
```
```
In kernel/bpf/verifier.c (ffffffff813160ef)
Location: include/linux/btf.h:396
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_struct_ops_btf_id
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff813716e5)
Location: include/linux/btf.h:396
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81384c81)
Location: include/linux/btf.h:396
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_mem_usage
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_put_progs
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In kernel/bpf/bpf_lsm.c (ffffffff81389b44)
Location: include/linux/btf.h:396
Inline: True
Inline callers:
  - kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim
```
```
In tools/lib/bpf/relo_core.c (ffffffff8138ca4f)
Location: include/linux/btf.h:396
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81f94a0b)
Location: include/linux/btf.h:396
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
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
In kernel/bpf/btf.c (ffff800010285030)
Location: kernel/bpf/btf.c:464
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
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
In kernel/bpf/btf.c (c04b5654)
Location: kernel/bpf/btf.c:464
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_seq_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
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
In kernel/bpf/btf.c (c00000000032fb40)
Location: kernel/bpf/btf.c:464
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
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
In kernel/bpf/btf.c (ffffffe0001ba540)
Location: kernel/bpf/btf.c:464
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
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
In kernel/bpf/btf.c (ffffffff811f66ca)
Location: kernel/bpf/btf.c:464
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
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
In kernel/bpf/btf.c (ffffffff811e941a)
Location: kernel/bpf/btf.c:464
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
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
In kernel/bpf/btf.c (ffffffff811f449a)
Location: kernel/bpf/btf.c:464
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
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
In kernel/bpf/btf.c (ffffffff812029aa)
Location: kernel/bpf/btf.c:464
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_datasec_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
```
</details>
</li>
</ul>

## Differences
