# Function: <code>__btf_verifier_log_type</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c6bf0)
Location: kernel/bpf/btf.c:493
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff811c6bf0-ffffffff811c6df6: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811d99a0)
Location: kernel/bpf/btf.c:613
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff811d99a0-ffffffff811d9ba6: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ee720)
Location: kernel/bpf/btf.c:688
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff811ee720-ffffffff811ee936: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fae60)
Location: kernel/bpf/btf.c:688
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff811fae60-ffffffff811fb076: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81221080)
Location: kernel/bpf/btf.c:703
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_check
  - kernel/bpf/btf.c:btf_func_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff81221080-ffffffff812212bd: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812242f0)
Location: kernel/bpf/btf.c:1288
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_check
  - kernel/bpf/btf.c:btf_func_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff812242f0-ffffffff812244f2: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81228da0)
Location: kernel/bpf/btf.c:1289
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff81228da0-ffffffff81228fa2: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812610e0)
Location: kernel/bpf/btf.c:1289
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff812610e0-ffffffff812613ae: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ac980)
Location: kernel/bpf/btf.c:1384
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff812ac980-ffffffff812acc81: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130c520)
Location: kernel/bpf/btf.c:1388
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff8130c520-ffffffff8130c813: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133bc30)
Location: kernel/bpf/btf.c:1407
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff8133bc30-ffffffff8133beea: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81361df0)
Location: kernel/bpf/btf.c:1408
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_func_proto_check
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_decl_tag_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_float_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_func_proto_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_fwd_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff81361df0-ffffffff813620aa: __btf_verifier_log_type (STB_LOCAL)
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
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010281048)
Location: kernel/bpf/btf.c:688
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffff800010281048-ffff800010281200: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b24b8)
Location: kernel/bpf/btf.c:688
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
c04b24b8-c04b2650: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032b4f0)
Location: kernel/bpf/btf.c:688
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
c00000000032b4f0-c00000000032b6a8: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b761c)
Location: kernel/bpf/btf.c:688
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffe0001b761c-ffffffe0001b774e: __btf_verifier_log_type (STB_LOCAL)
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
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f3480)
Location: kernel/bpf/btf.c:688
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff811f3480-ffffffff811f3696: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e61d0)
Location: kernel/bpf/btf.c:688
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff811e61d0-ffffffff811e63e6: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f1250)
Location: kernel/bpf/btf.c:688
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff811f1250-ffffffff811f1466: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __btf_verifier_log_type(struct btf_verifier_env *env, const struct btf_type *t, bool log_details, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ff760)
Location: kernel/bpf/btf.c:688
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_var_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_array_check_meta
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_modifier_resolve
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_ref_type_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_int_check_meta
  - kernel/bpf/btf.c:btf_df_resolve
  - kernel/bpf/btf.c:btf_df_check_kflag_member
  - kernel/bpf/btf.c:btf_df_check_member
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
```
**Symbols:**

```
ffffffff811ff760-ffffffff811ff976: __btf_verifier_log_type (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
