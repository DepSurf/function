# Function: <code>set_memory_ro</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f330)
Location: arch/x86/mm/pageattr.c:1703
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:set_real_mode_permissions
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
**Symbols:**

```
ffffffff8106f330-ffffffff8106f361: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f196)
Location: arch/x86/mm/pageattr.c:1711
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
**Symbols:**

```
ffffffff8106f090-ffffffff8106f0c1: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072e06)
Location: arch/x86/mm/pageattr.c:1711
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
**Symbols:**

```
ffffffff81072d00-ffffffff81072d31: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072376)
Location: arch/x86/mm/pageattr.c:1757
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
**Symbols:**

```
ffffffff810722b0-ffffffff810722db: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81077be6)
Location: arch/x86/mm/pageattr.c:1757
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
**Symbols:**

```
ffffffff81077b20-ffffffff81077b4b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a6f5)
Location: arch/x86/mm/pageattr.c:1787
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff8107a560-ffffffff8107a58b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080ea5)
Location: arch/x86/mm/pageattr.c:1980
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81080d10-ffffffff81080d3b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084985)
Location: arch/x86/mm/pageattr.c:1991
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff810847f0-ffffffff8108481b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085685)
Location: arch/x86/mm/pageattr.c:1897
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff810854f0-ffffffff8108551b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f3a5)
Location: arch/x86/mm/pat/set_memory.c:1933
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/ftrace.c:set_ftrace_ops_ro
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108f210-ffffffff8108f23b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f195)
Location: arch/x86/mm/pat/set_memory.c:1933
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/ftrace.c:set_ftrace_ops_ro
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108f000-ffffffff8108f02b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fd25)
Location: arch/x86/mm/pat/set_memory.c:1941
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/ftrace.c:set_ftrace_ops_ro
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108fb90-ffffffff8108fbbb: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f805)
Location: arch/x86/mm/pat/set_memory.c:1941
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/ftrace.c:set_ftrace_ops_ro
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8109f670-ffffffff8109f69b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b35f3)
Location: arch/x86/mm/pat/set_memory.c:1978
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/ftrace.c:set_ftrace_ops_ro
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff810b33f0-ffffffff810b342d: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce193)
Location: arch/x86/mm/pat/set_memory.c:2074
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/ftrace.c:set_ftrace_ops_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
```
**Symbols:**

```
ffffffff810cdeb0-ffffffff810cdeed: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d1755)
Location: arch/x86/mm/pat/set_memory.c:2075
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/ftrace.c:set_ftrace_ops_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
```
**Symbols:**

```
ffffffff810d1470-ffffffff810d14ad: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9e85)
Location: arch/x86/mm/pat/set_memory.c:2074
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/ftrace.c:set_ftrace_ops_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
```
**Symbols:**

```
ffffffff810d9b50-ffffffff810d9b8d: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pageattr.c (ffff8000100b0378)
Location: arch/arm64/mm/pageattr.c:111
Inline: False
Direct callers:
  - arch/arm64/kernel/probes/kprobes.c:alloc_insn_page
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffff8000100b0378-ffff8000100b03b4: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/pageattr.c (c031fd94)
Location: arch/arm/mm/pageattr.c:64
Inline: False
Direct callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - arch/arm/plat-omap/sram.c:omap_map_sram
  - arch/arm/plat-omap/sram.c:omap_sram_push
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
  - drivers/misc/sram-exec.c:sram_exec_copy
```
**Symbols:**

```
c031fd94-c031fdb8: set_memory_ro (STB_GLOBAL)
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
In kernel/bpf/core.c (0)
Location: include/linux/set_memory.h:11
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/set_memory.h:11
Inline: True
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
In kernel/bpf/core.c (0)
Location: include/linux/set_memory.h:11
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/set_memory.h:11
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084685)
Location: arch/x86/mm/pageattr.c:1897
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff810844f0-ffffffff8108451b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81073295)
Location: arch/x86/mm/pageattr.c:1897
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff81073100-ffffffff8107312b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084635)
Location: arch/x86/mm/pageattr.c:1897
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff810844a0-ffffffff810844cb: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int set_memory_ro(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086775)
Location: arch/x86/mm/pageattr.c:1897
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_ro
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:set_kernel_text_ro
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/power/snapshot.c:snapshot_write_finalize
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff810865e0-ffffffff8108660b: set_memory_ro (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
