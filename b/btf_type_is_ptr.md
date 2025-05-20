# Function: <code>btf_type_is_ptr</code>

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
In kernel/bpf/btf.c (ffffffff811c8654)
Location: kernel/bpf/btf.c:335
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
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
In kernel/bpf/btf.c (ffffffff811dbb0d)
Location: kernel/bpf/btf.c:363
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
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
In kernel/bpf/btf.c (ffffffff811f14cf)
Location: kernel/bpf/btf.c:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/btf.c (ffffffff811fdbdf)
Location: kernel/bpf/btf.c:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/verifier.c (ffffffff812064db)
Location: include/linux/btf.h:75
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
```
In kernel/bpf/btf.c (ffffffff8121fd78)
Location: include/linux/btf.h:75
Inline: True
Inline callers:
  - kernel/bpf/btf.c:__btf_resolve_helper_id
  - kernel/bpf/btf.c:__btf_resolve_helper_id
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/verifier.c (ffffffff8121411b)
Location: include/linux/btf.h:120
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
```
In kernel/bpf/btf.c (ffffffff812286a1)
Location: include/linux/btf.h:120
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/verifier.c (ffffffff81216950)
Location: include/linux/btf.h:125
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
```
In kernel/bpf/btf.c (ffffffff8122d0a0)
Location: include/linux/btf.h:125
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/verifier.c (ffffffff8124d08a)
Location: include/linux/btf.h:126
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81265a30)
Location: include/linux/btf.h:126
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/verifier.c (ffffffff81294060)
Location: include/linux/btf.h:160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff812b3a15)
Location: include/linux/btf.h:160
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:env_stack_push
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
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
In kernel/bpf/verifier.c (ffffffff812eea9f)
Location: include/linux/btf.h:224
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
```
```
In kernel/bpf/btf.c (ffffffff81313ef4)
Location: include/linux/btf.h:224
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:env_stack_push
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
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
In kernel/bpf/verifier.c (ffffffff8131b489)
Location: include/linux/btf.h:235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff8134af6e)
Location: include/linux/btf.h:235
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:env_stack_push
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
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
In kernel/bpf/verifier.c (ffffffff8133d4cd)
Location: include/linux/btf.h:246
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff8137177c)
Location: include/linux/btf.h:246
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_nested_type_is_trusted
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_check_iter_kfuncs
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
  - kernel/bpf/btf.c:env_stack_push
  - kernel/bpf/btf.c:btf_type_resolve_func_ptr
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
In kernel/bpf/btf.c (ffff800010284b1c)
Location: kernel/bpf/btf.c:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/btf.c (c04b51f0)
Location: kernel/bpf/btf.c:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/btf.c (c00000000032f510)
Location: kernel/bpf/btf.c:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/btf.c (ffffffe0001ba118)
Location: kernel/bpf/btf.c:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/btf.c (ffffffff811f61ff)
Location: kernel/bpf/btf.c:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/btf.c (ffffffff811e8f4f)
Location: kernel/bpf/btf.c:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/btf.c (ffffffff811f3fcf)
Location: kernel/bpf/btf.c:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
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
In kernel/bpf/btf.c (ffffffff812024df)
Location: kernel/bpf/btf.c:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ptr_resolve
  - kernel/bpf/btf.c:btf_var_resolve
```
</details>
</li>
</ul>

## Differences
