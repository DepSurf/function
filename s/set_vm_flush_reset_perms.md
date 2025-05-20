# Function: <code>set_vm_flush_reset_perms</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106dc9b)
Location: include/linux/vmalloc.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810725cd)
Location: include/linux/vmalloc.h:156
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81096028)
Location: include/linux/vmalloc.h:156
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffffffff81146655)
Location: include/linux/vmalloc.h:156
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d1ead)
Location: include/linux/vmalloc.h:156
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811dfea9)
Location: include/linux/vmalloc.h:156
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106f2b0)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810735fd)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109c5e8)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffffffff81152235)
Location: include/linux/vmalloc.h:165
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811de44d)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811ec669)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81075ed9)
Location: include/linux/vmalloc.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a70d)
Location: include/linux/vmalloc.h:180
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810a30c2)
Location: include/linux/vmalloc.h:180
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffffffff81162b35)
Location: include/linux/vmalloc.h:180
Inline: True
```
```
In kernel/bpf/trampoline.c (ffffffff8121ef3b)
Location: include/linux/vmalloc.h:180
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122fcfe)
Location: include/linux/vmalloc.h:180
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff810764fe)
Location: include/linux/vmalloc.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a49d)
Location: include/linux/vmalloc.h:176
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109eabe)
Location: include/linux/vmalloc.h:176
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffffffff8115ed75)
Location: include/linux/vmalloc.h:176
Inline: True
```
```
In kernel/bpf/trampoline.c (ffffffff81222751)
Location: include/linux/vmalloc.h:176
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812381ca)
Location: include/linux/vmalloc.h:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81076f8a)
Location: include/linux/vmalloc.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8107b67d)
Location: include/linux/vmalloc.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109f95f)
Location: include/linux/vmalloc.h:217
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffffffff8115f9e5)
Location: include/linux/vmalloc.h:217
Inline: True
```
```
In kernel/bpf/trampoline.c (ffffffff81227649)
Location: include/linux/vmalloc.h:217
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123c9e0)
Location: include/linux/vmalloc.h:217
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8108476a)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810897fd)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810b0deb)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffffffff811873c7)
Location: include/linux/vmalloc.h:236
Inline: True
```
```
In kernel/bpf/trampoline.c (ffffffff8125f7d1)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff81277430)
Location: include/linux/vmalloc.h:236
Inline: True
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
In arch/x86/kernel/ftrace.c (ffffffff81094935)
Location: include/linux/vmalloc.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff81099b7c)
Location: include/linux/vmalloc.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In kernel/module/strict_rwx.c (ffffffff8119064d)
Location: include/linux/vmalloc.h:238
Inline: True
Inline callers:
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
```
```
In kernel/bpf/core.c (ffffffff8126c30a)
Location: include/linux/vmalloc.h:238
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/trampoline.c (ffffffff812a9ee4)
Location: include/linux/vmalloc.h:238
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6fe0)
Location: include/linux/vmalloc.h:238
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81cb6969)
Location: include/linux/vmalloc.h:238
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
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
In kernel/module/strict_rwx.c (ffffffff811cdb3d)
Location: include/linux/vmalloc.h:238
Inline: True
Inline callers:
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
```
```
In kernel/bpf/core.c (ffffffff812c29b9)
Location: include/linux/vmalloc.h:238
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/trampoline.c (ffffffff81309053)
Location: include/linux/vmalloc.h:238
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c850)
Location: include/linux/vmalloc.h:238
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81e74ed9)
Location: include/linux/vmalloc.h:238
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
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
In kernel/module/strict_rwx.c (ffffffff811e1515)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_x
```
```
In kernel/bpf/core.c (ffffffff812e98a7)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/trampoline.c (ffffffff81337fcf)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135c3bd)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81ed10dc)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
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
In kernel/module/strict_rwx.c (ffffffff811f7245)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_x
```
```
In kernel/bpf/core.c (ffffffff81307f07)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
```
```
In kernel/bpf/trampoline.c (ffffffff8135db44)
Location: include/linux/vmalloc.h:236
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:arch_alloc_bpf_trampoline
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/probes/kprobes.c (ffff8000100ac594)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/kprobes.c:alloc_insn_page
```
```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4c0c)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffff8000101c0f18)
Location: include/linux/vmalloc.h:165
Inline: True
```
```
In kernel/bpf/core.c (ffff80001025f6ec)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffff80001026ff04)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/net/bpf_jit_32.c (c032c708)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
```
```
In kernel/module.c (c04085c8)
Location: include/linux/vmalloc.h:165
Inline: True
```
```
In kernel/bpf/core.c (c0492ac8)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (c04a2218)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003046f8)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (c000000000316e14)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d59a)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffe0001a9716)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106e250)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810725fd)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81095f08)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffffffff8114a855)
Location: include/linux/vmalloc.h:165
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d6a6d)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811e4c89)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8105e670)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff8106267d)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81084998)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffffffff8113db05)
Location: include/linux/vmalloc.h:165
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c982d)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811d7a49)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff8106e700)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810725ad)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81095eb8)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffffffff81148705)
Location: include/linux/vmalloc.h:165
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d483d)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811e2a59)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ftrace.c (ffffffff81070980)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
```
```
In arch/x86/kernel/kprobes/core.c (ffffffff810745fd)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109daa4)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/module.c (ffffffff81155375)
Location: include/linux/vmalloc.h:165
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811e2b6d)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811f0e36)
Location: include/linux/vmalloc.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
</ul>

## Differences
