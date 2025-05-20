# Function: <code>btf_type_is_int</code>

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
In kernel/bpf/btf.c (ffffffff811c83e0)
Location: kernel/bpf/btf.c:340
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
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
In kernel/bpf/btf.c (ffffffff811db8e9)
Location: kernel/bpf/btf.c:368
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
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
In kernel/bpf/btf.c (ffffffff811f128b)
Location: kernel/bpf/btf.c:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
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
In kernel/bpf/btf.c (ffffffff811fd99b)
Location: kernel/bpf/btf.c:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (ffffffff81224c4d)
Location: include/linux/btf.h:80
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/verifier.c (ffffffff8120f6c1)
Location: include/linux/btf.h:125
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8122b6b1)
Location: include/linux/btf.h:125
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/verifier.c (ffffffff81210a41)
Location: include/linux/btf.h:130
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff812301be)
Location: include/linux/btf.h:130
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/verifier.c (ffffffff81245bf9)
Location: include/linux/btf.h:131
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81268e90)
Location: include/linux/btf.h:131
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/verifier.c (ffffffff8128bc5f)
Location: include/linux/btf.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff812b8792)
Location: include/linux/btf.h:165
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:__btf_type_is_scalar_struct
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/verifier.c (ffffffff812ea7a9)
Location: include/linux/btf.h:229
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff813171ae)
Location: include/linux/btf.h:229
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/verifier.c (ffffffff81316884)
Location: include/linux/btf.h:240
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff813483dc)
Location: include/linux/btf.h:240
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_array_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/verifier.c (ffffffff81338aac)
Location: include/linux/btf.h:251
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff8136e76e)
Location: include/linux/btf.h:251
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_array_show
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_member_is_reg_int
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
In kernel/bpf/btf.c (ffff800010284898)
Location: kernel/bpf/btf.c:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
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
In kernel/bpf/btf.c (c04b4f0c)
Location: kernel/bpf/btf.c:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
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
In kernel/bpf/btf.c (c00000000032f1d4)
Location: kernel/bpf/btf.c:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
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
In kernel/bpf/btf.c (ffffffe0001b9eac)
Location: kernel/bpf/btf.c:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
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
In kernel/bpf/btf.c (ffffffff811f5fbb)
Location: kernel/bpf/btf.c:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
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
In kernel/bpf/btf.c (ffffffff811e8d0b)
Location: kernel/bpf/btf.c:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
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
In kernel/bpf/btf.c (ffffffff811f3d8b)
Location: kernel/bpf/btf.c:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
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
In kernel/bpf/btf.c (ffffffff8120229b)
Location: kernel/bpf/btf.c:385
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_array_resolve
  - kernel/bpf/btf.c:btf_member_is_reg_int
```
</details>
</li>
</ul>

## Differences
