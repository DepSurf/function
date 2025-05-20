# Function: <code>btf_verifier_log_member</code>

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
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c7170)
Location: kernel/bpf/btf.c:531
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
```
**Symbols:**

```
ffffffff811c7170-ffffffff811c72b0: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811d9e80)
Location: kernel/bpf/btf.c:651
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff811d9e80-ffffffff811da02c: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811eed20)
Location: kernel/bpf/btf.c:726
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff811eed20-ffffffff811eeed6: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fb460)
Location: kernel/bpf/btf.c:726
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff811fb460-ffffffff811fb616: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81221da0)
Location: kernel/bpf/btf.c:748
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff81221da0-ffffffff81221f73: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225330)
Location: kernel/bpf/btf.c:1333
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff81225330-ffffffff81225539: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81229db0)
Location: kernel/bpf/btf.c:1334
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff81229db0-ffffffff81229fb9: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812624e0)
Location: kernel/bpf/btf.c:1334
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff812624e0-ffffffff812626e9: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812adeb0)
Location: kernel/bpf/btf.c:1429
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff812adeb0-ffffffff812ae0db: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130e0a0)
Location: kernel/bpf/btf.c:1432
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff8130e0a0-ffffffff8130e2cb: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133d710)
Location: kernel/bpf/btf.c:1457
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff8133d710-ffffffff8133d8f8: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81363980)
Location: kernel/bpf/btf.c:1458
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_float_check_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff81363980-ffffffff81363b68: btf_verifier_log_member (STB_LOCAL)
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
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010281728)
Location: kernel/bpf/btf.c:726
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffff800010281728-ffff8000102818fc: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b2b34)
Location: kernel/bpf/btf.c:726
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
c04b2b34-c04b2ce8: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032bb90)
Location: kernel/bpf/btf.c:726
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
c00000000032bb90-c00000000032bd6c: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b7ae8)
Location: kernel/bpf/btf.c:726
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffe0001b7ae8-ffffffe0001b7c34: btf_verifier_log_member (STB_LOCAL)
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
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f3a80)
Location: kernel/bpf/btf.c:726
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff811f3a80-ffffffff811f3c36: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e67d0)
Location: kernel/bpf/btf.c:726
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff811e67d0-ffffffff811e6986: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f1850)
Location: kernel/bpf/btf.c:726
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff811f1850-ffffffff811f1a06: btf_verifier_log_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void btf_verifier_log_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ffd60)
Location: kernel/bpf/btf.c:726
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_kflag_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_enum_check_member
  - kernel/bpf/btf.c:btf_struct_resolve
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_meta
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_struct_check_member
  - kernel/bpf/btf.c:btf_array_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_ptr_check_member
  - kernel/bpf/btf.c:btf_modifier_check_kflag_member
  - kernel/bpf/btf.c:btf_modifier_check_member
  - kernel/bpf/btf.c:btf_int_check_kflag_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_int_check_member
  - kernel/bpf/btf.c:btf_generic_check_kflag_member
```
**Symbols:**

```
ffffffff811ffd60-ffffffff811fff16: btf_verifier_log_member (STB_LOCAL)
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
