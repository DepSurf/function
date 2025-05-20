# Function: <code>resolve_prog_type</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120cb05)
Location: kernel/bpf/verifier.c:2678
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:may_update_sockmap
  - kernel/bpf/verifier.c:may_access_direct_pkt_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120e514)
Location: kernel/bpf/verifier.c:3223
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:may_update_sockmap
  - kernel/bpf/verifier.c:may_access_direct_pkt_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81243086)
Location: kernel/bpf/verifier.c:3298
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:may_update_sockmap
  - kernel/bpf/verifier.c:may_access_direct_pkt_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81288899)
Location: include/linux/bpf_verifier.h:593
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:may_update_sockmap
  - kernel/bpf/verifier.c:may_access_direct_pkt_data
```
```
In kernel/bpf/btf.c (ffffffff812b80b9)
Location: include/linux/bpf_verifier.h:593
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
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
In kernel/trace/bpf_trace.c (ffffffff812a8697)
Location: include/linux/bpf_verifier.h:665
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In kernel/bpf/core.c (ffffffff812c3325)
Location: include/linux/bpf_verifier.h:665
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_map_compatible
```
```
In kernel/bpf/verifier.c (ffffffff812df179)
Location: include/linux/bpf_verifier.h:665
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:may_update_sockmap
  - kernel/bpf/verifier.c:may_access_direct_pkt_data
```
```
In kernel/bpf/trampoline.c (ffffffff81308cfc)
Location: include/linux/bpf_verifier.h:665
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_exit
  - kernel/bpf/trampoline.c:bpf_trampoline_enter
```
```
In kernel/bpf/btf.c (ffffffff81316475)
Location: include/linux/bpf_verifier.h:665
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_func_arg_match
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
In kernel/trace/bpf_trace.c (ffffffff812caff0)
Location: include/linux/bpf_verifier.h:729
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In kernel/bpf/core.c (ffffffff812ea155)
Location: include/linux/bpf_verifier.h:729
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_map_compatible
```
```
In kernel/bpf/verifier.c (ffffffff81301a69)
Location: include/linux/bpf_verifier.h:729
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:may_update_sockmap
  - kernel/bpf/verifier.c:may_access_direct_pkt_data
```
```
In kernel/bpf/trampoline.c (ffffffff81337c1c)
Location: include/linux/bpf_verifier.h:729
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_exit
  - kernel/bpf/trampoline.c:bpf_trampoline_enter
```
```
In kernel/bpf/btf.c (ffffffff8134a305)
Location: include/linux/bpf_verifier.h:729
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
  - kernel/bpf/btf.c:btf_check_func_arg_match
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
In kernel/trace/bpf_trace.c (ffffffff812e8290)
Location: include/linux/bpf_verifier.h:831
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In kernel/bpf/core.c (ffffffff81308465)
Location: include/linux/bpf_verifier.h:831
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_map_compatible
```
```
In kernel/bpf/verifier.c (ffffffff81321aa9)
Location: include/linux/bpf_verifier.h:831
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:check_map_prog_compatibility
  - kernel/bpf/verifier.c:check_return_code
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:get_kfunc_ptr_arg_type
  - kernel/bpf/verifier.c:may_update_sockmap
  - kernel/bpf/verifier.c:may_access_direct_pkt_data
```
```
In kernel/bpf/trampoline.c (ffffffff8135da5c)
Location: include/linux/bpf_verifier.h:831
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_exit
  - kernel/bpf/trampoline.c:bpf_trampoline_enter
```
```
In kernel/bpf/btf.c (ffffffff81370ab5)
Location: include/linux/bpf_verifier.h:831
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_kfunc_id_set_contains
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
