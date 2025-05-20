# Function: <code>btf_type_is_modifier</code>

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
In kernel/bpf/btf.c (ffffffff811c909b)
Location: kernel/bpf/btf.c:284
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_type_id_size
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
In kernel/bpf/btf.c (ffffffff811dc1f5)
Location: kernel/bpf/btf.c:294
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_type_id_size
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
In kernel/bpf/btf.c (ffffffff811f1797)
Location: kernel/bpf/btf.c:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_needs_resolve
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
In kernel/bpf/btf.c (ffffffff811fdea7)
Location: kernel/bpf/btf.c:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_needs_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225ac9)
Location: kernel/bpf/btf.c:311
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:__btf_resolve_helper_id
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_modifier_seq_show
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122c43f)
Location: kernel/bpf/btf.c:402
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
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
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
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
In kernel/bpf/btf.c (ffffffff812311f3)
Location: kernel/bpf/btf.c:403
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
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
In kernel/bpf/btf.c (ffffffff8126a137)
Location: kernel/bpf/btf.c:403
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
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
In kernel/bpf/btf.c (ffffffff812b6eaa)
Location: kernel/bpf/btf.c:434
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_show_name
  - kernel/bpf/btf.c:btf_type_skip_modifiers
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
In kernel/bpf/btf.c (ffffffff81318442)
Location: kernel/bpf/btf.c:439
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_show_name
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
In kernel/bpf/btf.c (ffffffff813483b8)
Location: kernel/bpf/btf.c:461
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_show_name
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
In kernel/bpf/btf.c (ffffffff8136e755)
Location: kernel/bpf/btf.c:462
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_check_type_tags
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_show_name
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
In kernel/bpf/btf.c (ffff800010284db4)
Location: kernel/bpf/btf.c:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_needs_resolve
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
In kernel/bpf/btf.c (c04b5440)
Location: kernel/bpf/btf.c:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_needs_resolve
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
In kernel/bpf/btf.c (c00000000032f8cc)
Location: kernel/bpf/btf.c:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_needs_resolve
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
In kernel/bpf/btf.c (ffffffe0001ba360)
Location: kernel/bpf/btf.c:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_needs_resolve
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
In kernel/bpf/btf.c (ffffffff811f64c7)
Location: kernel/bpf/btf.c:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_needs_resolve
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
In kernel/bpf/btf.c (ffffffff811e9217)
Location: kernel/bpf/btf.c:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_needs_resolve
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
In kernel/bpf/btf.c (ffffffff811f4297)
Location: kernel/bpf/btf.c:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_needs_resolve
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
In kernel/bpf/btf.c (ffffffff812027a7)
Location: kernel/bpf/btf.c:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:btf_type_id_size
  - kernel/bpf/btf.c:btf_type_needs_resolve
```
</details>
</li>
</ul>

## Differences
