# Function: <code>btf_verifier_log</code>

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
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c69f0)
Location: kernel/bpf/btf.c:479
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff811c69f0-ffffffff811c6a88: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811d95e0)
Location: kernel/bpf/btf.c:599
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff811d95e0-ffffffff811d9678: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ee310)
Location: kernel/bpf/btf.c:674
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_datasec_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff811ee310-ffffffff811ee3a8: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811faa50)
Location: kernel/bpf/btf.c:674
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_datasec_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff811faa50-ffffffff811faae8: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812205e0)
Location: kernel/bpf/btf.c:689
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_check_sec_info
  - kernel/bpf/btf.c:btf_check_sec_info
  - kernel/bpf/btf.c:btf_check_sec_info
  - kernel/bpf/btf.c:btf_check_sec_info
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff812205e0-ffffffff8122067b: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223650)
Location: kernel/bpf/btf.c:1274
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_check_sec_info
  - kernel/bpf/btf.c:btf_check_sec_info
  - kernel/bpf/btf.c:btf_check_sec_info
  - kernel/bpf/btf.c:btf_check_sec_info
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff81223650-ffffffff812236f5: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812280f0)
Location: kernel/bpf/btf.c:1275
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_float_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff812280f0-ffffffff81228195: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812603c0)
Location: kernel/bpf/btf.c:1275
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_float_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff812603c0-ffffffff81260465: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ab2c0)
Location: kernel/bpf/btf.c:1370
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_decl_tag_log
  - kernel/bpf/btf.c:btf_float_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff812ab2c0-ffffffff812ab393: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130ac30)
Location: kernel/bpf/btf.c:1374
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_decl_tag_log
  - kernel/bpf/btf.c:btf_float_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff8130ac30-ffffffff8130ad03: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81339240)
Location: kernel/bpf/btf.c:1393
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_decl_tag_log
  - kernel/bpf/btf.c:btf_float_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff81339240-ffffffff813392f2: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8135f370)
Location: kernel/bpf/btf.c:1394
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_parse_str_sec
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_check_all_metas
  - kernel/bpf/btf.c:btf_decl_tag_log
  - kernel/bpf/btf.c:btf_float_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum64_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff8135f370-ffffffff8135f422: btf_verifier_log (STB_LOCAL)
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
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010280a60)
Location: kernel/bpf/btf.c:674
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
  - kernel/bpf/btf.c:btf_int_log
  - kernel/bpf/btf.c:btf_int_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffff800010280a60-ffff800010280b2c: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b1778)
Location: kernel/bpf/btf.c:674
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
c04b1778-c04b1810: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032aeb0)
Location: kernel/bpf/btf.c:674
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_datasec_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
c00000000032aeb0-c00000000032af40: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b718c)
Location: kernel/bpf/btf.c:674
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffe0001b718c-ffffffe0001b71f0: btf_verifier_log (STB_LOCAL)
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
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f3070)
Location: kernel/bpf/btf.c:674
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_datasec_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff811f3070-ffffffff811f3108: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e5dc0)
Location: kernel/bpf/btf.c:674
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_datasec_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff811e5dc0-ffffffff811e5e58: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f0e40)
Location: kernel/bpf/btf.c:674
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_datasec_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff811f0e40-ffffffff811f0ed8: btf_verifier_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void btf_verifier_log(struct btf_verifier_env *env, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ff350)
Location: kernel/bpf/btf.c:674
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_datasec_log
  - kernel/bpf/btf.c:btf_var_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_func_proto_log
  - kernel/bpf/btf.c:btf_enum_log
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_enum_check_meta
  - kernel/bpf/btf.c:btf_struct_log
  - kernel/bpf/btf.c:btf_array_log
  - kernel/bpf/btf.c:btf_fwd_type_log
  - kernel/bpf/btf.c:btf_ref_type_log
  - kernel/bpf/btf.c:btf_int_log
```
**Symbols:**

```
ffffffff811ff350-ffffffff811ff3e8: btf_verifier_log (STB_LOCAL)
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
