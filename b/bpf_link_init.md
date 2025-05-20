# Function: <code>bpf_link_init</code>

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
void bpf_link_init(struct bpf_link *link, enum bpf_link_type type, const struct bpf_link_ops *ops, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8120102d)
Location: kernel/bpf/syscall.c:2265
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
```
**Symbols:**

```
ffffffff81200c40-ffffffff81200c64: bpf_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_init(struct bpf_link *link, enum bpf_link_type type, const struct bpf_link_ops *ops, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200a1d)
Location: kernel/bpf/syscall.c:2281
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
ffffffff81200110-ffffffff81200134: bpf_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_init(struct bpf_link *link, enum bpf_link_type type, const struct bpf_link_ops *ops, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8120143d)
Location: kernel/bpf/syscall.c:2289
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
ffffffff81200ac0-ffffffff81200ae4: bpf_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_init(struct bpf_link *link, enum bpf_link_type type, const struct bpf_link_ops *ops, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812333e8)
Location: kernel/bpf/syscall.c:2399
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
ffffffff81232830-ffffffff81232854: bpf_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_init(struct bpf_link *link, enum bpf_link_type type, const struct bpf_link_ops *ops, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8127643e)
Location: kernel/bpf/syscall.c:2647
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
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/core/dev.c:bpf_xdp_link_attach
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff81275c40-ffffffff81275c70: bpf_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_init(struct bpf_link *link, enum bpf_link_type type, const struct bpf_link_ops *ops, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cc5ae)
Location: kernel/bpf/syscall.c:2681
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/core/dev.c:bpf_xdp_link_attach
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812cbd30-ffffffff812cbd60: bpf_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_init(struct bpf_link *link, enum bpf_link_type type, const struct bpf_link_ops *ops, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f3f4e)
Location: kernel/bpf/syscall.c:2794
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - net/core/dev.c:bpf_xdp_link_attach
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_attach
```
**Symbols:**

```
ffffffff812f36a0-ffffffff812f36d0: bpf_link_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_init(struct bpf_link *link, enum bpf_link_type type, const struct bpf_link_ops *ops, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81312e7d)
Location: kernel/bpf/syscall.c:2856
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/tcx.c:tcx_link_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - drivers/net/netkit.c:netkit_link_attach
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - net/core/dev.c:bpf_xdp_link_attach
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_attach
```
**Symbols:**

```
ffffffff81312530-ffffffff81312560: bpf_link_init (STB_GLOBAL)
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
