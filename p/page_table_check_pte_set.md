# Function: <code>page_table_check_pte_set</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
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
In arch/x86/xen/grant-table.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
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
In arch/x86/xen/grant-table.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/migrate_device.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/page_table_check.h:141
Inline: True
```
</details>
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
