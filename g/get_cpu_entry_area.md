# Function: <code>get_cpu_entry_area</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff826c3b52)
Location: arch/x86/mm/cpu_entry_area.c:18
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff8107afa0-ffffffff8107afc7: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff826ede13)
Location: arch/x86/mm/cpu_entry_area.c:18
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff8107dd30-ffffffff8107dd57: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828a4b2a)
Location: arch/x86/mm/cpu_entry_area.c:20
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff810848b0-ffffffff810848d2: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828bcfe4)
Location: arch/x86/mm/cpu_entry_area.c:20
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81088540-ffffffff81088562: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828c346e)
Location: arch/x86/mm/cpu_entry_area.c:20
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff810891b0-ffffffff810891d2: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff82ce6726)
Location: arch/x86/mm/cpu_entry_area.c:24
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:alloc_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff8108bb10-ffffffff8108bb32: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff81c385c0)
Location: arch/x86/mm/cpu_entry_area.c:25
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:alloc_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/kernel/sev-es.c:setup_vc_stacks
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81c385c0-ffffffff81c385d8: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff81c2a9d0)
Location: arch/x86/mm/cpu_entry_area.c:25
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81c2a9d0-ffffffff81c2a9e8: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff81d48fb0)
Location: arch/x86/mm/cpu_entry_area.c:25
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81d48fb0-ffffffff81d48fc8: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff81f18380)
Location: arch/x86/mm/cpu_entry_area.c:25
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff81f18380-ffffffff81f183a0: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff820bfb80)
Location: arch/x86/mm/cpu_entry_area.c:63
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff820bfb80-ffffffff820bfbd8: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff82141880)
Location: arch/x86/mm/cpu_entry_area.c:70
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff82141880-ffffffff821418d8: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff82223800)
Location: arch/x86/mm/cpu_entry_area.c:70
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/power/cpu.c:fix_processor_context
```
**Symbols:**

```
ffffffff82223800-ffffffff82223858: get_cpu_entry_area (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828ae444)
Location: arch/x86/mm/cpu_entry_area.c:20
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81088170-ffffffff81088192: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828a6636)
Location: arch/x86/mm/cpu_entry_area.c:20
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81076dd0-ffffffff81076df2: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828c1343)
Location: arch/x86/mm/cpu_entry_area.c:20
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff81088120-ffffffff81088142: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct cpu_entry_area *get_cpu_entry_area(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff828c448e)
Location: arch/x86/mm/cpu_entry_area.c:20
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/kernel/dumpstack.c:in_entry_stack
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:load_fixmap_gdt
  - arch/x86/kernel/paravirt.c:native_load_tr_desc
```
**Symbols:**

```
ffffffff8108a3c0-ffffffff8108a3e2: get_cpu_entry_area (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
