# Function: <code>set_memory_nx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106e6c0)
Location: arch/x86/mm/pageattr.c:1694
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:set_real_mode_permissions
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff8106e6c0-ffffffff8106e704: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106e4a0)
Location: arch/x86/mm/pageattr.c:1702
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff8106e4a0-ffffffff8106e4e4: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072150)
Location: arch/x86/mm/pageattr.c:1702
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff81072150-ffffffff81072194: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810717a0)
Location: arch/x86/mm/pageattr.c:1748
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff810717a0-ffffffff810717df: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81076e40)
Location: arch/x86/mm/pageattr.c:1748
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff81076e40-ffffffff81076e7f: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810798b0)
Location: arch/x86/mm/pageattr.c:1778
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff810798b0-ffffffff810798ef: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810800c0)
Location: arch/x86/mm/pageattr.c:1971
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/kernel/ftrace.c:arch_ftrace_trampoline_free
  - arch/x86/kernel/ftrace.c:arch_ftrace_update_trampoline
  - arch/x86/kernel/kprobes/core.c:free_insn_page
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff810800c0-ffffffff810800ff: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083b60)
Location: arch/x86/mm/pageattr.c:1982
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/pageattr.c:set_pages_nx
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff81083b60-ffffffff81083b9f: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810854b0)
Location: arch/x86/mm/pageattr.c:1889
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff810854b0-ffffffff810854ef: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f1d0)
Location: arch/x86/mm/pat/set_memory.c:1925
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/platform/efi/efi.c:efi_set_executable
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108f1d0-ffffffff8108f20f: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108efc0)
Location: arch/x86/mm/pat/set_memory.c:1925
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108efc0-ffffffff8108efff: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108fb50)
Location: arch/x86/mm/pat/set_memory.c:1933
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8108fb50-ffffffff8108fb8f: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f630)
Location: arch/x86/mm/pat/set_memory.c:1933
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff8109f630-ffffffff8109f66f: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b3380)
Location: arch/x86/mm/pat/set_memory.c:1970
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff810b3380-ffffffff810b33e3: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cde30)
Location: arch/x86/mm/pat/set_memory.c:2066
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff810cde30-ffffffff810cde93: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d13f0)
Location: arch/x86/mm/pat/set_memory.c:2067
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff810d13f0-ffffffff810d1453: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9ad0)
Location: arch/x86/mm/pat/set_memory.c:2066
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - kernel/module/strict_rwx.c:module_enable_nx
  - kernel/bpf/trampoline.c:arch_unprotect_bpf_trampoline
```
**Symbols:**

```
ffffffff810d9ad0-ffffffff810d9b33: set_memory_nx (STB_GLOBAL)
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
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/pageattr.c (ffff8000100b03f8)
Location: arch/arm64/mm/pageattr.c:125
Inline: False
```
**Symbols:**

```
ffff8000100b03f8-ffff8000100b0434: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/pageattr.c (c031fddc)
Location: arch/arm/mm/pageattr.c:78
Inline: False
Direct callers:
  - drivers/misc/sram-exec.c:sram_exec_copy
```
**Symbols:**

```
c031fddc-c031fe00: set_memory_nx (STB_GLOBAL)
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
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810844b0)
Location: arch/x86/mm/pageattr.c:1889
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff810844b0-ffffffff810844ef: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810730c0)
Location: arch/x86/mm/pageattr.c:1889
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff810730c0-ffffffff810730ff: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084460)
Location: arch/x86/mm/pageattr.c:1889
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff81084460-ffffffff8108449f: set_memory_nx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_memory_nx(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810865a0)
Location: arch/x86/mm/pageattr.c:1889
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:init_real_mode
  - arch/x86/mm/init.c:free_init_pages
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/platform/efi/efi.c:efi_set_executable
```
**Symbols:**

```
ffffffff810865a0-ffffffff810865df: set_memory_nx (STB_GLOBAL)
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
