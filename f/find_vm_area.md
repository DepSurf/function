# Function: <code>find_vm_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cc9fe)
Location: mm/vmalloc.c:1411
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_32_user
Direct callers:
  - drivers/base/dma-mapping.c:dma_common_free_remap
```
**Symbols:**

```
ffffffff811cec50-ffffffff811cec73: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811e9abe)
Location: mm/vmalloc.c:1435
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
Direct callers:
  - drivers/base/dma-mapping.c:dma_common_free_remap
```
**Symbols:**

```
ffffffff811ebdf0-ffffffff811ebe13: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fae1e)
Location: mm/vmalloc.c:1418
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
Direct callers:
  - drivers/base/dma-mapping.c:dma_common_free_remap
```
**Symbols:**

```
ffffffff811fd020-ffffffff811fd043: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81205b24)
Location: mm/vmalloc.c:1469
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
Direct callers:
  - drivers/base/dma-mapping.c:dma_common_free_remap
```
**Symbols:**

```
ffffffff81207d10-ffffffff81207d33: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121f924)
Location: mm/vmalloc.c:1467
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
Direct callers:
  - drivers/base/dma-mapping.c:dma_common_free_remap
```
**Symbols:**

```
ffffffff81220e00-ffffffff81220e23: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8124149f)
Location: mm/vmalloc.c:1454
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
Direct callers:
  - kernel/dma/mapping.c:dma_common_free_remap
```
**Symbols:**

```
ffffffff81242ca0-ffffffff81242cc8: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81255b8f)
Location: mm/vmalloc.c:1456
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
```
**Symbols:**

```
ffffffff81257380-ffffffff812573a3: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81267eef)
Location: mm/vmalloc.c:2121
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:copy_process
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff812686b0-ffffffff812686d3: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81276865)
Location: mm/vmalloc.c:2127
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:copy_process
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff81277000-ffffffff81277019: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812a842b)
Location: mm/vmalloc.c:2172
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
**Symbols:**

```
ffffffff812abc30-ffffffff812abc96: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b3697)
Location: mm/vmalloc.c:2154
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
```
**Symbols:**

```
ffffffff812b7150-ffffffff812b71b6: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bdc3f)
Location: mm/vmalloc.c:2430
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_dump_obj
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff812bca20-ffffffff812bca86: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8130040f)
Location: mm/vmalloc.c:2482
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_dump_obj
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff812ff1b0-ffffffff812ff216: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81367781)
Location: mm/vmalloc.c:2522
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_dump_obj
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/dma/remap.c:dma_common_free_remap
  - kernel/dma/remap.c:dma_common_pages_remap
  - kernel/dma/remap.c:dma_common_find_pages
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - mm/page_alloc.c:alloc_large_system_hash
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff813661c0-ffffffff81366233: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e3701)
Location: mm/vmalloc.c:2584
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_dump_obj
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/dma/remap.c:dma_common_free_remap
  - kernel/dma/remap.c:dma_common_pages_remap
  - kernel/dma/remap.c:dma_common_find_pages
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - mm/page_alloc.c:alloc_large_system_hash
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff813e1db0-ffffffff813e1e23: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814181fc)
Location: mm/vmalloc.c:2664
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
Direct callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/dma/remap.c:dma_common_free_remap
  - kernel/dma/remap.c:dma_common_pages_remap
  - kernel/dma/remap.c:dma_common_find_pages
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_x
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - mm/mm_init.c:alloc_large_system_hash
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff81416af0-ffffffff81416b63: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81444d4c)
Location: mm/vmalloc.c:2664
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
Direct callers:
  - kernel/fork.c:alloc_thread_stack_node
  - kernel/dma/remap.c:dma_common_free_remap
  - kernel/dma/remap.c:dma_common_pages_remap
  - kernel/dma/remap.c:dma_common_find_pages
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_ro
  - kernel/module/strict_rwx.c:module_enable_x
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/trampoline.c:arch_alloc_bpf_trampoline
  - mm/mm_init.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff814435c0-ffffffff81443633: find_vm_area (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030cd18)
Location: mm/vmalloc.c:2127
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/arm64/kernel/probes/kprobes.c:alloc_insn_page
  - arch/arm64/mm/pageattr.c:change_memory_common
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:dup_task_struct
  - kernel/dma/remap.c:dma_common_find_pages
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffff80001030d538-ffff80001030d56c: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0527e98)
Location: mm/vmalloc.c:2127
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - kernel/dma/remap.c:dma_common_free_remap
  - kernel/dma/remap.c:dma_common_find_pages
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c0529078-c052909c: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dd4fc)
Location: mm/vmalloc.c:2127
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
c0000000003ddf70-c0000000003ddfac: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000215d32)
Location: mm/vmalloc.c:2127
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffe0002162e2-ffffffe000216310: find_vm_area (STB_GLOBAL)
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
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126eeb5)
Location: mm/vmalloc.c:2127
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:copy_process
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff8126f650-ffffffff8126f669: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81260e25)
Location: mm/vmalloc.c:2127
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:copy_process
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff812615c0-ffffffff812615d9: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126cc55)
Location: mm/vmalloc.c:2127
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:copy_process
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff8126d3f0-ffffffff8126d409: find_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct vm_struct *find_vm_area(const void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127b875)
Location: mm/vmalloc.c:2127
Inline: True
Inline callers:
  - mm/vmalloc.c:remap_vmalloc_range_partial
  - mm/vmalloc.c:__vunmap
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/fork.c:copy_process
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff8127cd80-ffffffff8127cd99: find_vm_area (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
