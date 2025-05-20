# Function: <code>read_cr3_pa</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8209d45a)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff820a6560)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/fault.c (ffffffff8106df83)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff820bca26)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abadf)
Location: arch/x86/include/asm/processor.h:237
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff826a32fa)
Location: arch/x86/include/asm/processor.h:241
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025626)
Location: arch/x86/include/asm/processor.h:241
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/fault.c (ffffffff81072f93)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3473)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate_64.c (ffffffff8182306b)
Location: arch/x86/include/asm/processor.h:241
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81025626-ffffffff8102564d: read_cr3_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff826cc2f2)
Location: arch/x86/include/asm/processor.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026367)
Location: arch/x86/include/asm/processor.h:239
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/fault.c (ffffffff81075948)
Location: arch/x86/include/asm/processor.h:239
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed6e5)
Location: arch/x86/include/asm/processor.h:239
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d366)
Location: arch/x86/include/asm/processor.h:239
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81026367-ffffffff8102638e: read_cr3_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff828822fd)
Location: arch/x86/include/asm/processor.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f17)
Location: arch/x86/include/asm/processor.h:228
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/fault.c (ffffffff8107b73a)
Location: arch/x86/include/asm/processor.h:228
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4277)
Location: arch/x86/include/asm/processor.h:228
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff8188f33f)
Location: arch/x86/include/asm/processor.h:228
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81025f17-ffffffff81025f3e: read_cr3_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289929a)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027c17)
Location: arch/x86/include/asm/processor.h:231
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/fault.c (ffffffff8107f262)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc713)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff818d933f)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81027c17-ffffffff81027c3e: read_cr3_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289c29a)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102854c)
Location: arch/x86/include/asm/processor.h:231
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/fault.c (ffffffff810802f2)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2bba)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff8190b33f)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8102854c-ffffffff81028573: read_cr3_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82cc22af)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a4a3)
Location: arch/x86/include/asm/processor.h:245
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/fault.c (ffffffff81086dc2)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5f4e)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc368)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8102a4a3-ffffffff8102a4ca: read_cr3_pa (STB_LOCAL)
ffffffff81086660-ffffffff81086687: read_cr3_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82fae2ef)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bd2bff)
Location: arch/x86/include/asm/processor.h:245
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/sev-es.c (ffffffff810836a5)
Location: arch/x86/include/asm/processor.h:245
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81087442)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
Direct callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd38d4)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1348)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd2bff-ffffffff81bd2c26: read_cr3_pa (STB_LOCAL)
ffffffff81086ec0-ffffffff81086ee7: read_cr3_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff831b82ef)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4dcb)
Location: arch/x86/include/asm/processor.h:245
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/sev.c (ffffffff81083c15)
Location: arch/x86/include/asm/processor.h:245
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810883d9)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff831de504)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3388)
Location: arch/x86/include/asm/processor.h:245
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bc4dcb-ffffffff81bc4df2: read_cr3_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff832982e7)
Location: arch/x86/include/asm/processor.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c975a7)
Location: arch/x86/include/asm/processor.h:247
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/sev.c (ffffffff81092db7)
Location: arch/x86/include/asm/processor.h:247
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81097769)
Location: arch/x86/include/asm/processor.h:247
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff832c17a5)
Location: arch/x86/include/asm/processor.h:247
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff81c94388)
Location: arch/x86/include/asm/processor.h:247
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81c975a7-ffffffff81c975ce: read_cr3_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff834462e9)
Location: arch/x86/include/asm/processor.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81e46a2f)
Location: arch/x86/include/asm/processor.h:250
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/sev.c (ffffffff810a52ee)
Location: arch/x86/include/asm/processor.h:250
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810aa298)
Location: arch/x86/include/asm/processor.h:250
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83473e55)
Location: arch/x86/include/asm/processor.h:250
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff81e433b6)
Location: arch/x86/include/asm/processor.h:250
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81e46a2f-ffffffff81e46a6d: read_cr3_pa (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff83e5f3c0)
Location: arch/x86/include/asm/processor.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f8f5)
Location: arch/x86/include/asm/processor.h:201
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/sev.c (ffffffff810bda7c)
Location: arch/x86/include/asm/processor.h:201
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810c3cf0)
Location: arch/x86/include/asm/processor.h:201
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9bad0)
Location: arch/x86/include/asm/processor.h:201
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff8201e452)
Location: arch/x86/include/asm/processor.h:201
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff836906b5)
Location: arch/x86/include/asm/processor.h:201
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/head64.c (ffffffff836945f0)
Location: arch/x86/include/asm/processor.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/sev.c (ffffffff810c10ec)
Location: arch/x86/include/asm/processor.h:201
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810c7530)
Location: arch/x86/include/asm/processor.h:201
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff836bf570)
Location: arch/x86/include/asm/processor.h:201
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff8209e452)
Location: arch/x86/include/asm/processor.h:201
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff838c0185)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/head64.c (ffffffff838c44e0)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/sev.c (ffffffff810c854c)
Location: arch/x86/include/asm/processor.h:216
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810cfa00)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff838f0010)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff82176452)
Location: arch/x86/include/asm/processor.h:216
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8288a29a)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810286ac)
Location: arch/x86/include/asm/processor.h:231
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/fault.c (ffffffff8107f2f2)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adb90)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff818ab33f)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810286ac-ffffffff810286d3: read_cr3_pa (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff82888240)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/mm/fault.c (ffffffff8106e2d4)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5e2e)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff81865341)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289d29a)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102850c)
Location: arch/x86/include/asm/processor.h:231
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/fault.c (ffffffff8107f2a2)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0a8f)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff818fc33f)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8102850c-ffffffff81028533: read_cr3_pa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr3_pa();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8289d29a)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102919c)
Location: arch/x86/include/asm/processor.h:231
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/fault.c (ffffffff81081392)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3bda)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/power/hibernate.c (ffffffff8191d33f)
Location: arch/x86/include/asm/processor.h:231
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8102919c-ffffffff810291c3: read_cr3_pa (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
