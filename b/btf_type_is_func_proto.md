# Function: <code>btf_type_is_func_proto</code>

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
In kernel/bpf/btf.c (ffffffff811dc44c)
Location: kernel/bpf/btf.c:332
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
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
In kernel/bpf/btf.c (ffffffff811f1984)
Location: kernel/bpf/btf.c:344
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811fe094)
Location: kernel/bpf/btf.c:344
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/verifier.c (ffffffff81206371)
Location: include/linux/btf.h:105
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_attach_btf_id
```
```
In kernel/bpf/btf.c (ffffffff81225a94)
Location: include/linux/btf.h:105
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:__btf_resolve_helper_id
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_check
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122f825)
Location: include/linux/btf.h:105
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
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
In kernel/bpf/verifier.c (ffffffff81213eec)
Location: include/linux/btf.h:150
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
```
In kernel/bpf/btf.c (ffffffff8122c3ed)
Location: include/linux/btf.h:150
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_check
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81237d25)
Location: include/linux/btf.h:150
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
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
In kernel/bpf/verifier.c (ffffffff8121671a)
Location: include/linux/btf.h:160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81231109)
Location: include/linux/btf.h:160
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123c53f)
Location: include/linux/btf.h:160
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
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
In kernel/bpf/verifier.c (ffffffff8124ce4a)
Location: include/linux/btf.h:161
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff8126a04d)
Location: include/linux/btf.h:161
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81276efa)
Location: include/linux/btf.h:161
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
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
In kernel/bpf/verifier.c (ffffffff81293e83)
Location: include/linux/btf.h:242
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff812b3978)
Location: include/linux/btf.h:242
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6b2f)
Location: include/linux/btf.h:242
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
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
In kernel/bpf/verifier.c (ffffffff812ee9d3)
Location: include/linux/btf.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81313e57)
Location: include/linux/btf.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c39f)
Location: include/linux/btf.h:334
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
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
In kernel/trace/trace_probe.c (ffffffff812d778a)
Location: include/linux/btf.h:350
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_btf_func_proto
```
```
In kernel/bpf/verifier.c (ffffffff8131b227)
Location: include/linux/btf.h:350
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81343c6e)
Location: include/linux/btf.h:350
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135c95f)
Location: include/linux/btf.h:350
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
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
In kernel/trace/trace_btf.c (ffffffff812f8470)
Location: include/linux/btf.h:361
Inline: True
Inline callers:
  - kernel/trace/trace_btf.c:btf_get_func_param
  - kernel/trace/trace_btf.c:btf_find_func_proto
```
```
In kernel/bpf/verifier.c (ffffffff8133d4f0)
Location: include/linux/btf.h:361
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81369bfe)
Location: include/linux/btf.h:361
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_func_resolve
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81385c8c)
Location: include/linux/btf.h:361
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
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
In kernel/bpf/btf.c (ffff800010285018)
Location: kernel/bpf/btf.c:344
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (c04b5638)
Location: kernel/bpf/btf.c:344
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (c00000000032fb28)
Location: kernel/bpf/btf.c:344
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffe0001ba520)
Location: kernel/bpf/btf.c:344
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811f66b4)
Location: kernel/bpf/btf.c:344
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811e9404)
Location: kernel/bpf/btf.c:344
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811f4484)
Location: kernel/bpf/btf.c:344
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff81202994)
Location: kernel/bpf/btf.c:344
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
  - kernel/bpf/btf.c:btf_check_all_types
```
</details>
</li>
</ul>

## Differences
