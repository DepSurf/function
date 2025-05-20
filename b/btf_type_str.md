# Function: <code>btf_type_str</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81222c20)
Location: kernel/bpf/btf.c:279
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
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
In kernel/bpf/btf.c (ffffffff81228c99)
Location: kernel/bpf/btf.c:285
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *btf_type_str(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812313db)
Location: kernel/bpf/btf.c:286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
```
**Symbols:**

```
ffffffff8122ca00-ffffffff8122ca1a: btf_type_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *btf_type_str(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8126a32b)
Location: kernel/bpf/btf.c:286
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
```
**Symbols:**

```
ffffffff81265340-ffffffff81265376: btf_type_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *btf_type_str(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b7149)
Location: kernel/bpf/btf.c:314
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
**Symbols:**

```
ffffffff812b1380-ffffffff812b13be: btf_type_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *btf_type_str(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131860d)
Location: kernel/bpf/btf.c:319
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_verifier_log_type
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
**Symbols:**

```
ffffffff81311560-ffffffff8131159e: btf_type_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *btf_type_str(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813485a7)
Location: kernel/bpf/btf.c:335
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_verifier_log_type
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
**Symbols:**

```
ffffffff81340f40-ffffffff81340f7e: btf_type_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *btf_type_str(const struct btf_type *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136eb1d)
Location: kernel/bpf/btf.c:336
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_distill_func_proto
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:btf_ctx_access
  - kernel/bpf/btf.c:__btf_verifier_log_type
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:process_kf_arg_ptr_to_btf_id
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
**Symbols:**

```
ffffffff81367550-ffffffff8136758e: btf_type_str (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
