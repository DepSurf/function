# Function: <code>btf_field_type_size</code>

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
In kernel/bpf/verifier.c (ffffffff812d6035)
Location: include/linux/bpf.h:292
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/btf.c (ffffffff81317694)
Location: include/linux/bpf.h:292
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_parse_field_offs
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_parse_fields
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
In kernel/bpf/verifier.c (ffffffff8130965c)
Location: include/linux/bpf.h:306
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/btf.c (ffffffff81347561)
Location: include/linux/bpf.h:306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_parse_fields
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
In kernel/bpf/verifier.c (ffffffff8132da42)
Location: include/linux/bpf.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_map_access
```
```
In kernel/bpf/btf.c (ffffffff8136d9a6)
Location: include/linux/bpf.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_access
  - kernel/bpf/btf.c:btf_parse_fields
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
