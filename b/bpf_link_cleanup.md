# Function: <code>bpf_link_cleanup</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_cleanup(struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81201191)
Location: kernel/bpf/syscall.c:2292
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
```
**Symbols:**

```
ffffffff81200c70-ffffffff81200cd0: bpf_link_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_cleanup(struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200b63)
Location: kernel/bpf/syscall.c:2308
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81200140-ffffffff812001a0: bpf_link_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_cleanup(struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812015a0)
Location: kernel/bpf/syscall.c:2316
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81200af0-ffffffff81200b50: bpf_link_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_cleanup(struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81233533)
Location: kernel/bpf/syscall.c:2426
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81232860-ffffffff812328c0: bpf_link_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_cleanup(struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8127654c)
Location: kernel/bpf/syscall.c:2674
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff81275c70-ffffffff81275cda: bpf_link_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_cleanup(struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cc6bc)
Location: kernel/bpf/syscall.c:2708
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
```
**Symbols:**

```
ffffffff812cbd70-ffffffff812cbdda: bpf_link_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_cleanup(struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f4064)
Location: kernel/bpf/syscall.c:2821
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
  - net/core/dev.c:bpf_xdp_link_attach
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_attach
```
**Symbols:**

```
ffffffff812f36e0-ffffffff812f374a: bpf_link_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_cleanup(struct bpf_link_primer *primer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81312f93)
Location: kernel/bpf/syscall.c:2885
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/tcx.c:tcx_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
  - drivers/net/netkit.c:netkit_link_attach
  - net/core/dev.c:bpf_xdp_link_attach
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_attach
```
**Symbols:**

```
ffffffff81312570-ffffffff813125da: bpf_link_cleanup (STB_GLOBAL)
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
