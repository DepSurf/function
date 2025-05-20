# Function: <code>btf_type_is_func</code>

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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:327
Inline: True
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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:339
Inline: True
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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:339
Inline: True
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
In kernel/bpf/verifier.c (ffffffff81206341)
Location: include/linux/btf.h:100
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
  - kernel/bpf/verifier.c:check_attach_btf_id
```
```
In kernel/bpf/btf.c (ffffffff81225a1a)
Location: include/linux/btf.h:100
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/verifier.c (ffffffff81213ea2)
Location: include/linux/btf.h:145
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
```
In kernel/bpf/btf.c (ffffffff8122c341)
Location: include/linux/btf.h:145
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/verifier.c (ffffffff812166d0)
Location: include/linux/btf.h:155
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81231060)
Location: include/linux/btf.h:155
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/verifier.c (ffffffff8124ce0d)
Location: include/linux/btf.h:156
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81269f9a)
Location: include/linux/btf.h:156
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/verifier.c (ffffffff81293e3d)
Location: include/linux/btf.h:237
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff812b392d)
Location: include/linux/btf.h:237
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_decl_tag_resolve
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
In kernel/bpf/verifier.c (ffffffff812ee908)
Location: include/linux/btf.h:329
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81313e0c)
Location: include/linux/btf.h:329
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_decl_tag_resolve
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
In kernel/trace/trace_probe.c (ffffffff812d7753)
Location: include/linux/btf.h:345
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:find_btf_func_proto
```
```
In kernel/bpf/verifier.c (ffffffff8131b1f9)
Location: include/linux/btf.h:345
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81343c20)
Location: include/linux/btf.h:345
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_decl_tag_resolve
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
In kernel/trace/trace_btf.c (ffffffff812f840b)
Location: include/linux/btf.h:356
Inline: True
Inline callers:
  - kernel/trace/trace_btf.c:btf_find_func_proto
```
```
In kernel/bpf/verifier.c (ffffffff8133d5a0)
Location: include/linux/btf.h:356
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:bpf_check_attach_target
  - kernel/bpf/verifier.c:check_pseudo_btf_id
  - kernel/bpf/verifier.c:add_kfunc_call
```
```
In kernel/bpf/btf.c (ffffffff81369bb0)
Location: include/linux/btf.h:356
Inline: True
Inline callers:
  - kernel/bpf/btf.c:register_btf_id_dtor_kfuncs
  - kernel/bpf/btf.c:__register_btf_kfunc_id_set
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_type_match
  - kernel/bpf/btf.c:btf_decl_tag_resolve
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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:339
Inline: True
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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:339
Inline: True
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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:339
Inline: True
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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:339
Inline: True
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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:339
Inline: True
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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:339
Inline: True
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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:339
Inline: True
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
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:339
Inline: True
```
</details>
</li>
</ul>

## Differences
