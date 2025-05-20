# Function: <code>btf_type_is_struct</code>

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
In kernel/bpf/btf.c (ffffffff811c91f6)
Location: kernel/bpf/btf.c:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffff811dc20e)
Location: kernel/bpf/btf.c:351
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_parse_type_sec
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff811f1758)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff811fde68)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff81222ae6)
Location: kernel/bpf/btf.c:358
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:__btf_resolve_helper_id
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/verifier.c (ffffffff81205e34)
Location: include/linux/btf.h:163
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_helper_call
```
```
In kernel/bpf/btf.c (ffffffff81228a77)
Location: include/linux/btf.h:163
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:env_stack_push
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
In kernel/bpf/verifier.c (ffffffff81207d92)
Location: include/linux/btf.h:173
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff812308f4)
Location: include/linux/btf.h:173
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:env_stack_push
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
In kernel/bpf/verifier.c (ffffffff8123b62b)
Location: include/linux/btf.h:174
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
```
```
In kernel/bpf/btf.c (ffffffff8126967a)
Location: include/linux/btf.h:174
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:env_stack_push
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
In kernel/bpf/verifier.c (ffffffff812811c9)
Location: include/linux/btf.h:260
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
```
```
In kernel/bpf/btf.c (ffffffff812b83c6)
Location: include/linux/btf.h:260
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:__btf_type_is_scalar_struct
  - kernel/bpf/btf.c:__btf_type_is_scalar_struct
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:env_stack_push
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
In kernel/bpf/verifier.c (ffffffff812d8f39)
Location: include/linux/btf.h:352
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:check_helper_call
```
```
In kernel/bpf/btf.c (ffffffff81312467)
Location: include/linux/btf.h:352
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:get_kern_ctx_btf_id
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:env_stack_push
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
In kernel/bpf/verifier.c (ffffffff812f7fef)
Location: include/linux/btf.h:368
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:check_helper_call
```
```
In kernel/bpf/btf.c (ffffffff81341dd0)
Location: include/linux/btf.h:368
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:get_kern_ctx_btf_id
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:env_stack_push
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
In kernel/trace/trace_btf.c (ffffffff812f8547)
Location: include/linux/btf.h:379
Inline: True
Inline callers:
  - kernel/trace/trace_btf.c:btf_find_struct_member
```
```
In kernel/bpf/verifier.c (ffffffff8131648f)
Location: include/linux/btf.h:379
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff8136e998)
Location: include/linux/btf.h:379
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:get_kern_ctx_btf_id
  - kernel/bpf/btf.c:btf_get_prog_ctx_type
  - kernel/bpf/btf.c:btf_resolve_valid
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:btf_decl_tag_resolve
  - kernel/bpf/btf.c:env_stack_push
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
In kernel/bpf/btf.c (ffff800010284d98)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (c04b53f4)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (c00000000032f878)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffe0001ba30c)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff811f6488)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff811e91d8)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff811f4258)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff81202768)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
  - kernel/bpf/btf.c:btf_type_needs_resolve
```
</details>
</li>
</ul>

## Differences
