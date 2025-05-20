# Function: <code>cpu_architecture</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpu_architecture();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm/kernel/setup.c (c030d7a0)
Location: arch/arm/kernel/setup.c:275
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:c_show
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/setup.c:setup_processor
Direct callers:
  - arch/arm/vfp/vfpmodule.c:vfp_init
  - arch/arm/kernel/setup.c:c_show
  - arch/arm/kernel/setup.c:setup_processor
  - arch/arm/kernel/thumbee.c:thumbee_init
  - arch/arm/kernel/swp_emulate.c:swp_emulation_init
  - arch/arm/mm/fault.c:exceptions_init
  - arch/arm/mm/fault.c:exceptions_init
  - arch/arm/mm/idmap.c:init_static_idmap
  - arch/arm/mm/mmu.c:__create_mapping
  - arch/arm/mm/mmu.c:build_mem_type_table
  - arch/arm/mm/mmu.c:early_cachepolicy
  - arch/arm/mm/alignment.c:alignment_init
  - arch/arm/mm/alignment.c:alignment_init
  - arch/arm/mm/alignment.c:do_alignment
  - arch/arm/mm/alignment.c:alignment_proc_show
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
```
**Symbols:**

```
c030d540-c030d558: cpu_architecture.part.0 (STB_LOCAL)
c030d8b4-c030d8e0: cpu_architecture (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
