# Function: <code>__btf_member_bit_offset</code>

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
In kernel/bpf/btf.c (ffffffff812b1932)
Location: include/linux/btf.h:287
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_find_field
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6ac5)
Location: include/linux/btf.h:287
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
```
```
In tools/lib/bpf/relo_core.c (ffffffff812c9706)
Location: include/linux/btf.h:287
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81d61d45)
Location: include/linux/btf.h:287
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
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
In kernel/bpf/btf.c (ffffffff81311caa)
Location: include/linux/btf.h:389
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_parse_fields
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c335)
Location: include/linux/btf.h:389
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
```
```
In tools/lib/bpf/relo_core.c (ffffffff81330716)
Location: include/linux/btf.h:389
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f2c755)
Location: include/linux/btf.h:389
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
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
In kernel/bpf/btf.c (ffffffff8134155b)
Location: include/linux/btf.h:405
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135c8fa)
Location: include/linux/btf.h:405
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
```
```
In tools/lib/bpf/relo_core.c (ffffffff813613e9)
Location: include/linux/btf.h:405
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81ed0f35)
Location: include/linux/btf.h:405
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_check_member
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f8c3e5)
Location: include/linux/btf.h:405
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
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
In kernel/bpf/btf.c (ffffffff81367aac)
Location: include/linux/btf.h:416
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_walk
  - kernel/bpf/btf.c:btf_struct_check_meta
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81385c27)
Location: include/linux/btf.h:416
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:check_zero_holes
```
```
In tools/lib/bpf/relo_core.c (ffffffff8138a299)
Location: include/linux/btf.h:416
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_match_member
  - tools/lib/bpf/relo_core.c:bpf_core_parse_spec
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81f948f5)
Location: include/linux/btf.h:416
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_check_member
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff82059b15)
Location: include/linux/btf.h:416
Inline: True
Inline callers:
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_check_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_init_member
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
  - net/ipv4/bpf_tcp_ca.c:bpf_tcp_ca_get_func_proto
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
