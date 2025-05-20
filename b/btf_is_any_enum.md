# Function: <code>btf_is_any_enum</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e345e)
Location: include/linux/btf.h:244
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff813125a0)
Location: include/linux/btf.h:244
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_type_match
```
```
In tools/lib/bpf/relo_core.c (ffffffff81332d7e)
Location: include/linux/btf.h:244
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
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
In kernel/bpf/verifier.c (ffffffff81305795)
Location: include/linux/btf.h:265
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff813483ec)
Location: include/linux/btf.h:265
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_ctx_access
```
```
In tools/lib/bpf/relo_core.c (ffffffff81363aa3)
Location: include/linux/btf.h:265
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
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
In kernel/bpf/verifier.c (ffffffff81326828)
Location: include/linux/btf.h:276
Inline: True
```
```
In kernel/bpf/btf.c (ffffffff8136e780)
Location: include/linux/btf.h:276
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_prepare_func_args
  - kernel/bpf/btf.c:btf_check_func_type_match
  - kernel/bpf/btf.c:btf_ctx_access
```
```
In tools/lib/bpf/relo_core.c (ffffffff8138c973)
Location: include/linux/btf.h:276
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
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
