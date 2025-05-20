# Function: <code>bpf_get_btf_vmlinux</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_get_btf_vmlinux();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8121486b)
Location: kernel/bpf/verifier.c:11947
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/btf.c:btf_parse_module
```
**Symbols:**

```
ffffffff81214750-ffffffff8121479f: bpf_get_btf_vmlinux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_get_btf_vmlinux();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812170c6)
Location: kernel/bpf/verifier.c:13272
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/btf.c:btf_parse_module
```
**Symbols:**

```
ffffffff81216fa0-ffffffff81216fef: bpf_get_btf_vmlinux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_get_btf_vmlinux();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8124d8aa)
Location: kernel/bpf/verifier.c:13716
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/btf.c:bpf_btf_find_by_name_kind
  - kernel/bpf/btf.c:btf_parse_module
```
**Symbols:**

```
ffffffff8124d750-ffffffff8124d79f: bpf_get_btf_vmlinux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_get_btf_vmlinux();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8129481c)
Location: kernel/bpf/verifier.c:14880
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:bpf_find_btf_id
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
```
**Symbols:**

```
ffffffff812946b0-ffffffff8129470b: bpf_get_btf_vmlinux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_get_btf_vmlinux();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812ef3d4)
Location: kernel/bpf/verifier.c:17051
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:bpf_find_btf_id
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
```
**Symbols:**

```
ffffffff812ef250-ffffffff812ef2ab: bpf_get_btf_vmlinux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_get_btf_vmlinux();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131bdbd)
Location: kernel/bpf/verifier.c:19382
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/trace/trace_probe.c:sprint_nth_btf_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
  - kernel/trace/trace_probe.c:find_btf_func_proto
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:bpf_find_btf_id
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
```
**Symbols:**

```
ffffffff8131bc20-ffffffff8131bc7b: bpf_get_btf_vmlinux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_get_btf_vmlinux();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8133e158)
Location: kernel/bpf/verifier.c:20729
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_snprintf_btf
  - kernel/trace/bpf_trace.c:bpf_seq_printf_btf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:bpf_find_btf_id
  - net/core/bpf_sk_storage.c:bpf_sk_storage_tracing_allowed
```
**Symbols:**

```
ffffffff8133dfc0-ffffffff8133e01b: bpf_get_btf_vmlinux (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
