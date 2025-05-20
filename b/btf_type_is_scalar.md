# Function: <code>btf_type_is_scalar</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
Location: include/linux/btf.h:145
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8123083f)
Location: include/linux/btf.h:145
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
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
Location: include/linux/btf.h:146
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff812695ba)
Location: include/linux/btf.h:146
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
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
Location: include/linux/btf.h:227
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff812b8792)
Location: include/linux/btf.h:227
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:__btf_type_is_scalar_struct
  - kernel/bpf/btf.c:__btf_type_is_scalar_struct
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
Location: include/linux/btf.h:314
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff8131660b)
Location: include/linux/btf.h:314
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
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
Location: include/linux/btf.h:330
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
```
In kernel/bpf/btf.c (ffffffff813464e6)
Location: include/linux/btf.h:330
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
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
In kernel/bpf/verifier.c (ffffffff81338aac)
Location: include/linux/btf.h:341
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
  - kernel/bpf/verifier.c:__btf_type_is_scalar_struct
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
