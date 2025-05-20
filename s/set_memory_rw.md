# Function: <code>set_memory_rw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f370)
Location: arch/x86/mm/pageattr.c:1708
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
**Symbols:**

```
ffffffff8106f370-ffffffff8106f3a1: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106f206)
Location: arch/x86/mm/pageattr.c:1716
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff8106f0d0-ffffffff8106f101: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072e76)
Location: arch/x86/mm/pageattr.c:1716
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff81072d40-ffffffff81072d71: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810723e6)
Location: arch/x86/mm/pageattr.c:1762
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:arch_copy_kprobe
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff810722e0-ffffffff8107230b: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81077c56)
Location: arch/x86/mm/pageattr.c:1762
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff81077b50-ffffffff81077b7b: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a765)
Location: arch/x86/mm/pageattr.c:1792
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff8107a590-ffffffff8107a5bb: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080f15)
Location: arch/x86/mm/pageattr.c:1985
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffff81080d40-ffffffff81080d6b: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810849f5)
Location: arch/x86/mm/pageattr.c:1996
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff81084820-ffffffff8108484b: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810856f5)
Location: arch/x86/mm/pageattr.c:1902
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff81085520-ffffffff8108554b: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f415)
Location: arch/x86/mm/pat/set_memory.c:1938
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108f240-ffffffff8108f26b: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f205)
Location: arch/x86/mm/pat/set_memory.c:1938
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108f030-ffffffff8108f05b: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fd95)
Location: arch/x86/mm/pat/set_memory.c:1946
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108fbc0-ffffffff8108fbeb: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f875)
Location: arch/x86/mm/pat/set_memory.c:1946
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8109f6a0-ffffffff8109f6cb: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b3673)
Location: arch/x86/mm/pat/set_memory.c:1983
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff810b3430-ffffffff810b346d: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce223)
Location: arch/x86/mm/pat/set_memory.c:2089
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_init_pages
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff810cdf70-ffffffff810cdfad: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d17e5)
Location: arch/x86/mm/pat/set_memory.c:2090
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_initrd_mem
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff810d1530-ffffffff810d156d: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9f15)
Location: arch/x86/mm/pat/set_memory.c:2089
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:set_pages_rw
Direct callers:
  - arch/x86/mm/init.c:free_initrd_mem
  - kernel/power/snapshot.c:swsusp_free
  - kernel/bpf/trampoline.c:arch_unprotect_bpf_trampoline
```
**Symbols:**

```
ffffffff810d9c10-ffffffff810d9c4d: set_memory_rw (STB_GLOBAL)
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
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pageattr.c (ffff8000100b03b8)
Location: arch/arm64/mm/pageattr.c:118
Inline: False
```
**Symbols:**

```
ffff8000100b03b8-ffff8000100b03f4: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/pageattr.c (c031fdb8)
Location: arch/arm/mm/pageattr.c:71
Inline: False
Direct callers:
  - arch/arm/plat-omap/sram.c:omap_sram_push
  - kernel/power/snapshot.c:swsusp_free
  - drivers/misc/sram-exec.c:sram_exec_copy
```
**Symbols:**

```
c031fdb8-c031fddc: set_memory_rw (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810846f5)
Location: arch/x86/mm/pageattr.c:1902
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff81084520-ffffffff8108454b: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81073305)
Location: arch/x86/mm/pageattr.c:1902
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff81073130-ffffffff8107315b: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810846a5)
Location: arch/x86/mm/pageattr.c:1902
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff810844d0-ffffffff810844fb: set_memory_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int set_memory_rw(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810867e5)
Location: arch/x86/mm/pageattr.c:1902
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:set_pages_rw
Direct callers:
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:set_kernel_text_rw
  - kernel/power/snapshot.c:swsusp_free
```
**Symbols:**

```
ffffffff81086610-ffffffff8108663b: set_memory_rw (STB_GLOBAL)
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
