# Function: <code>set_memory_x</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106ea50)
Location: arch/x86/mm/pageattr.c:1685
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:set_real_mode_permissions
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff8106ea50-ffffffff8106ea94: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106e810)
Location: arch/x86/mm/pageattr.c:1693
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff8106e810-ffffffff8106e854: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810724c0)
Location: arch/x86/mm/pageattr.c:1693
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff810724c0-ffffffff81072504: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071ab0)
Location: arch/x86/mm/pageattr.c:1739
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff81071ab0-ffffffff81071aef: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81077150)
Location: arch/x86/mm/pageattr.c:1739
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff81077150-ffffffff8107718f: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81079bb0)
Location: arch/x86/mm/pageattr.c:1769
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff81079bb0-ffffffff81079bef: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810803c0)
Location: arch/x86/mm/pageattr.c:1962
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff810803c0-ffffffff810803ff: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083e80)
Location: arch/x86/mm/pageattr.c:1973
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/mm/pageattr.c:set_pages_x
  - arch/x86/platform/efi/efi.c:efi_set_executable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81083e80-ffffffff81083ebf: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085470)
Location: arch/x86/mm/pageattr.c:1881
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/platform/efi/efi.c:efi_set_executable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81085470-ffffffff810854af: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f190)
Location: arch/x86/mm/pat/set_memory.c:1917
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/platform/efi/efi.c:efi_set_executable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108f190-ffffffff8108f1cf: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ef80)
Location: arch/x86/mm/pat/set_memory.c:1917
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108ef80-ffffffff8108efbf: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fb10)
Location: arch/x86/mm/pat/set_memory.c:1925
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108fb10-ffffffff8108fb4f: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f5f0)
Location: arch/x86/mm/pat/set_memory.c:1925
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - kernel/module.c:complete_formation
  - kernel/module.c:complete_formation
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8109f5f0-ffffffff8109f62f: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b3310)
Location: arch/x86/mm/pat/set_memory.c:1962
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:create_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - kernel/module/strict_rwx.c:module_enable_x
  - kernel/module/strict_rwx.c:module_enable_x
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff810b3310-ffffffff810b3373: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cddb0)
Location: arch/x86/mm/pat/set_memory.c:2058
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - kernel/module/strict_rwx.c:module_enable_x
  - kernel/module/strict_rwx.c:module_enable_x
```
**Symbols:**

```
ffffffff810cddb0-ffffffff810cde13: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d1370)
Location: arch/x86/mm/pat/set_memory.c:2059
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - kernel/module/strict_rwx.c:module_enable_x
```
**Symbols:**

```
ffffffff810d1370-ffffffff810d13d3: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9a50)
Location: arch/x86/mm/pat/set_memory.c:2058
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - kernel/module/strict_rwx.c:module_enable_x
```
**Symbols:**

```
ffffffff810d9a50-ffffffff810d9ab3: set_memory_x (STB_GLOBAL)
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
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pageattr.c (ffff8000100b0438)
Location: arch/arm64/mm/pageattr.c:132
Inline: False
Direct callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffff8000100b0438-ffff8000100b0474: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/pageattr.c (c031fe00)
Location: arch/arm/mm/pageattr.c:85
Inline: False
Direct callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - arch/arm/plat-omap/sram.c:omap_map_sram
  - arch/arm/plat-omap/sram.c:omap_sram_push
  - drivers/misc/sram-exec.c:sram_exec_copy
```
**Symbols:**

```
c031fe00-c031fe24: set_memory_x (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084470)
Location: arch/x86/mm/pageattr.c:1881
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/platform/efi/efi.c:efi_set_executable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81084470-ffffffff810844af: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81073080)
Location: arch/x86/mm/pageattr.c:1881
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/platform/efi/efi.c:efi_set_executable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81073080-ffffffff810730bf: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084420)
Location: arch/x86/mm/pageattr.c:1881
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/platform/efi/efi.c:efi_set_executable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81084420-ffffffff8108445f: set_memory_x (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_memory_x(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086560)
Location: arch/x86/mm/pageattr.c:1881
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:alloc_insn_page
  - arch/x86/platform/efi/efi.c:efi_set_executable
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81086560-ffffffff8108659f: set_memory_x (STB_GLOBAL)
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
