# Function: <code>btf_type_kflag</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811da7f6)
Location: kernel/bpf/btf.c:426
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (ffffffff811f02d0)
Location: kernel/bpf/btf.c:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (ffffffff811fc9e0)
Location: kernel/bpf/btf.c:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (ffffffff8122522a)
Location: include/linux/btf.h:120
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122f7bb)
Location: include/linux/btf.h:120
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81b0d275)
Location: include/linux/btf.h:120
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
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
In kernel/bpf/btf.c (ffffffff812282fd)
Location: include/linux/btf.h:180
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81237cbb)
Location: include/linux/btf.h:180
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81b1b575)
Location: include/linux/btf.h:180
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
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
In kernel/bpf/btf.c (ffffffff8122cda7)
Location: include/linux/btf.h:190
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123c4d5)
Location: include/linux/btf.h:190
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81b09225)
Location: include/linux/btf.h:190
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
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
In kernel/bpf/btf.c (ffffffff81265737)
Location: include/linux/btf.h:191
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81276e99)
Location: include/linux/btf.h:191
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81bcc115)
Location: include/linux/btf.h:191
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
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
In kernel/bpf/btf.c (ffffffff812b1932)
Location: include/linux/btf.h:282
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6ac5)
Location: include/linux/btf.h:282
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In tools/lib/bpf/relo_core.c (ffffffff812c9d3b)
Location: include/linux/btf.h:282
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81d61d45)
Location: include/linux/btf.h:282
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
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
In kernel/bpf/btf.c (ffffffff81311caa)
Location: include/linux/btf.h:384
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c335)
Location: include/linux/btf.h:384
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In tools/lib/bpf/relo_core.c (ffffffff81330e6b)
Location: include/linux/btf.h:384
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f2c755)
Location: include/linux/btf.h:384
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
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
In kernel/bpf/btf.c (ffffffff8134155b)
Location: include/linux/btf.h:400
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135c8fa)
Location: include/linux/btf.h:400
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In tools/lib/bpf/relo_core.c (ffffffff81361b0b)
Location: include/linux/btf.h:400
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81ed0f35)
Location: include/linux/btf.h:400
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_check_member
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f8c3e5)
Location: include/linux/btf.h:400
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
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
In kernel/trace/trace_probe.c (ffffffff812f5635)
Location: include/linux/btf.h:411
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8136ec8f)
Location: include/linux/btf.h:411
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum64_show
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_show
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81385c27)
Location: include/linux/btf.h:411
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_init
```
```
In tools/lib/bpf/relo_core.c (ffffffff8138a9bb)
Location: include/linux/btf.h:411
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81f948f5)
Location: include/linux/btf.h:411
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_check_member
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff82059b15)
Location: include/linux/btf.h:411
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
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
In kernel/bpf/btf.c (ffff800010283280)
Location: kernel/bpf/btf.c:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (c04b3c90)
Location: kernel/bpf/btf.c:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (c00000000032dac8)
Location: kernel/bpf/btf.c:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (ffffffe0001b90ae)
Location: kernel/bpf/btf.c:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (ffffffff811f5000)
Location: kernel/bpf/btf.c:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (ffffffff811e7d50)
Location: kernel/bpf/btf.c:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (ffffffff811f2dd0)
Location: kernel/bpf/btf.c:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (ffffffff812012e0)
Location: kernel/bpf/btf.c:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_seq_show
  - kernel/bpf/btf.c:btf_find_spin_lock
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
</details>
</li>
</ul>

## Differences
