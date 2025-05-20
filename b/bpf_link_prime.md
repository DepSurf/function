# Function: <code>bpf_link_prime</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_link_prime(struct bpf_link *link, struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200e40)
Location: kernel/bpf/syscall.c:2417
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
```
**Symbols:**

```
ffffffff81200e40-ffffffff81200f4e: bpf_link_prime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_link_prime(struct bpf_link *link, struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200210)
Location: kernel/bpf/syscall.c:2433
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81200210-ffffffff8120031e: bpf_link_prime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_link_prime(struct bpf_link *link, struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200bc0)
Location: kernel/bpf/syscall.c:2441
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81200bc0-ffffffff81200cce: bpf_link_prime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_link_prime(struct bpf_link *link, struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81232930)
Location: kernel/bpf/syscall.c:2551
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81232930-ffffffff81232a3e: bpf_link_prime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_link_prime(struct bpf_link *link, struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81275d00)
Location: kernel/bpf/syscall.c:2800
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81275d00-ffffffff81275e44: bpf_link_prime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_link_prime(struct bpf_link *link, struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cbe20)
Location: kernel/bpf/syscall.c:2834
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff812cbe20-ffffffff812cbf64: bpf_link_prime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_link_prime(struct bpf_link *link, struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f3790)
Location: kernel/bpf/syscall.c:2953
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - net/core/dev.c:bpf_xdp_link_attach
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_attach
```
**Symbols:**

```
ffffffff812f3790-ffffffff812f38d4: bpf_link_prime (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_link_prime(struct bpf_link *link, struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81312620)
Location: kernel/bpf/syscall.c:3017
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/tcx.c:tcx_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
  - drivers/net/netkit.c:netkit_link_attach
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - net/core/dev.c:bpf_xdp_link_attach
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_attach
```
**Symbols:**

```
ffffffff81312620-ffffffff81312764: bpf_link_prime (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
