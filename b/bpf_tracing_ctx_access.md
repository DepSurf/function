# Function: <code>bpf_tracing_ctx_access</code>

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
In kernel/trace/bpf_trace.c (ffffffff81255da5)
Location: include/linux/bpf.h:1757
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
  - kernel/trace/bpf_trace.c:tracing_prog_is_valid_access
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81cb67f5)
Location: include/linux/bpf.h:1757
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81d62075)
Location: include/linux/bpf.h:1757
Inline: True
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
In kernel/trace/bpf_trace.c (ffffffff812a5385)
Location: include/linux/bpf.h:2134
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
  - kernel/trace/bpf_trace.c:tracing_prog_is_valid_access
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81e74d55)
Location: include/linux/bpf.h:2134
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f2caf5)
Location: include/linux/bpf.h:2134
Inline: True
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
In kernel/trace/bpf_trace.c (ffffffff812c7835)
Location: include/linux/bpf.h:2273
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
  - kernel/trace/bpf_trace.c:tracing_prog_is_valid_access
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81ed0ec5)
Location: include/linux/bpf.h:2273
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff81f8c795)
Location: include/linux/bpf.h:2273
Inline: True
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
In kernel/trace/bpf_trace.c (ffffffff812e41b5)
Location: include/linux/bpf.h:2432
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:raw_tp_writable_prog_is_valid_access
  - kernel/trace/bpf_trace.c:tracing_prog_is_valid_access
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81f94885)
Location: include/linux/bpf.h:2432
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_dummy_ops_is_valid_access
```
```
In net/ipv4/bpf_tcp_ca.c (ffffffff82059f95)
Location: include/linux/bpf.h:2432
Inline: True
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
