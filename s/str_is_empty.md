# Function: <code>str_is_empty</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b88e4)
Location: include/linux/btf.h:180
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
```
In tools/lib/bpf/relo_core.c (ffffffff812cb777)
Location: include/linux/btf.h:180
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
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
In kernel/bpf/verifier.c (ffffffff812cf682)
Location: include/linux/btf.h:257
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_kfunc_arg_scalar_with_name
  - kernel/bpf/verifier.c:__kfunc_param_match_suffix
```
```
In kernel/bpf/btf.c (ffffffff81311908)
Location: include/linux/btf.h:257
Inline: True
```
```
In tools/lib/bpf/relo_core.c (ffffffff813302b6)
Location: include/linux/btf.h:257
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
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
In kernel/bpf/verifier.c (ffffffff812f8392)
Location: include/linux/btf.h:278
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_kfunc_arg_scalar_with_name
  - kernel/bpf/verifier.c:__kfunc_param_match_suffix
```
```
In kernel/bpf/btf.c (ffffffff813411af)
Location: include/linux/btf.h:278
Inline: True
```
```
In tools/lib/bpf/relo_core.c (ffffffff81360f56)
Location: include/linux/btf.h:278
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
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
In kernel/bpf/verifier.c (ffffffff813172c2)
Location: include/linux/btf.h:289
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_kfunc_arg_scalar_with_name
  - kernel/bpf/verifier.c:__kfunc_param_match_suffix
```
```
In kernel/bpf/btf.c (ffffffff8136660b)
Location: include/linux/btf.h:289
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
```
```
In tools/lib/bpf/relo_core.c (ffffffff81389e06)
Location: include/linux/btf.h:289
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_names_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
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
