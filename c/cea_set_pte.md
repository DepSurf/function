# Function: <code>cea_set_pte</code>

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
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff826c3b8b)
Location: arch/x86/mm/cpu_entry_area.c:27
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff8107afd0-ffffffff8107b009: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff8107dd60)
Location: arch/x86/mm/cpu_entry_area.c:27
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff8107dd60-ffffffff8107dddc: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff810848e0)
Location: arch/x86/mm/cpu_entry_area.c:29
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff810848e0-ffffffff8108495c: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff81088570)
Location: arch/x86/mm/cpu_entry_area.c:29
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff81088570-ffffffff810885ee: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff810891e0)
Location: arch/x86/mm/cpu_entry_area.c:29
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff810891e0-ffffffff8108925e: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108bb40)
Location: arch/x86/mm/cpu_entry_area.c:33
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff8108bb40-ffffffff8108bbbc: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108bb60)
Location: arch/x86/mm/cpu_entry_area.c:34
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/sev-es.c:setup_vc_stacks
  - arch/x86/kernel/sev-es.c:setup_vc_stacks
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff8108bb60-ffffffff8108bbdc: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108c770)
Location: arch/x86/mm/cpu_entry_area.c:34
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff8108c770-ffffffff8108c7ef: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff8109bfb0)
Location: arch/x86/mm/cpu_entry_area.c:34
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:release_bts_buffer
  - arch/x86/events/intel/ds.c:release_pebs_buffer
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff8109bfb0-ffffffff8109c02f: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff810af580)
Location: arch/x86/mm/cpu_entry_area.c:34
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff810af580-ffffffff810af613: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff810c9a00)
Location: arch/x86/mm/cpu_entry_area.c:72
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
```
**Symbols:**

```
ffffffff810c9a00-ffffffff810c9a96: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff810cd080)
Location: arch/x86/mm/cpu_entry_area.c:79
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
```
**Symbols:**

```
ffffffff810cd080-ffffffff810cd10d: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff810d5750)
Location: arch/x86/mm/cpu_entry_area.c:79
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/idt.c:idt_setup_apic_and_irq_gates
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
  - arch/x86/mm/cpu_entry_area.c:percpu_setup_exception_stacks
```
**Symbols:**

```
ffffffff810d5750-ffffffff810d57dd: cea_set_pte (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff810881a0)
Location: arch/x86/mm/cpu_entry_area.c:29
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff810881a0-ffffffff8108821e: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff81076e00)
Location: arch/x86/mm/cpu_entry_area.c:29
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff81076e00-ffffffff81076e72: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff81088150)
Location: arch/x86/mm/cpu_entry_area.c:29
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff81088150-ffffffff810881ce: cea_set_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cea_set_pte(void *cea_vaddr, phys_addr_t pa, pgprot_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/cpu_entry_area.c (ffffffff8108a3f0)
Location: arch/x86/mm/cpu_entry_area.c:29
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:ds_clear_cea
  - arch/x86/events/intel/ds.c:ds_update_cea
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:cea_map_percpu_pages
```
**Symbols:**

```
ffffffff8108a3f0-ffffffff8108a46e: cea_set_pte (STB_GLOBAL)
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
