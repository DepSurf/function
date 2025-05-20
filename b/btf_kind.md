# Function: <code>btf_kind</code>

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
In kernel/bpf/btf.c (ffffffff812b8fc6)
Location: include/linux/btf.h:185
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
```
```
In tools/lib/bpf/relo_core.c (ffffffff812ca198)
Location: include/linux/btf.h:185
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
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
In kernel/bpf/btf.c (ffffffff8131afd6)
Location: include/linux/btf.h:262
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
```
```
In tools/lib/bpf/relo_core.c (ffffffff81332cb0)
Location: include/linux/btf.h:262
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
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
In kernel/bpf/btf.c (ffffffff8134a5c6)
Location: include/linux/btf.h:283
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
```
```
In tools/lib/bpf/relo_core.c (ffffffff81363946)
Location: include/linux/btf.h:283
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
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
In kernel/bpf/btf.c (ffffffff81370d76)
Location: include/linux/btf.h:294
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_add_cands
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
  - kernel/bpf/btf.c:btf_validate_prog_ctx_type
```
```
In tools/lib/bpf/relo_core.c (ffffffff8138c816)
Location: include/linux/btf.h:294
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:bpf_core_format_spec
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_field_relo
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_fields_are_compat
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
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
