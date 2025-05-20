# Function: <code>bpf_prog_is_offloaded</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812eacba)
Location: include/linux/bpf.h:2677
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/syscall.c (ffffffff812ef6c4)
Location: include/linux/bpf.h:2677
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_get
```
```
In kernel/bpf/verifier.c (ffffffff8131c74d)
Location: include/linux/bpf.h:2677
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/offload.c (ffffffff81352e2c)
Location: include/linux/bpf.h:2677
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_dev_bound_kfunc_check
  - kernel/bpf/offload.c:bpf_prog_dev_bound_match
  - kernel/bpf/offload.c:bpf_prog_dev_bound_match
  - kernel/bpf/offload.c:bpf_prog_dev_bound_inherit
  - kernel/bpf/offload.c:__bpf_prog_dev_bound_init
```
```
In net/core/dev.c (ffffffff81e35056)
Location: include/linux/bpf.h:2677
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/filter.c (ffffffff81e68f49)
Location: include/linux/bpf.h:2677
Inline: True
Inline callers:
  - net/core/filter.c:xdp_is_valid_access
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
In kernel/bpf/core.c (ffffffff813091da)
Location: include/linux/bpf.h:2848
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/syscall.c (ffffffff8130e4a4)
Location: include/linux/bpf.h:2848
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:__bpf_prog_get
```
```
In kernel/bpf/verifier.c (ffffffff8133e76b)
Location: include/linux/bpf.h:2848
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
  - kernel/bpf/verifier.c:verifier_remove_insns
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:do_check
```
```
In kernel/bpf/offload.c (ffffffff8137a30c)
Location: include/linux/bpf.h:2848
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_dev_bound_kfunc_check
  - kernel/bpf/offload.c:bpf_prog_dev_bound_match
  - kernel/bpf/offload.c:bpf_prog_dev_bound_match
  - kernel/bpf/offload.c:bpf_prog_dev_bound_inherit
  - kernel/bpf/offload.c:__bpf_prog_dev_bound_init
```
```
In net/core/dev.c (ffffffff81ef30f3)
Location: include/linux/bpf.h:2848
Inline: True
Inline callers:
  - net/core/dev.c:dev_xdp_attach
```
```
In net/core/filter.c (ffffffff81f28529)
Location: include/linux/bpf.h:2848
Inline: True
Inline callers:
  - net/core/filter.c:xdp_is_valid_access
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
