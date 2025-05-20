# Function: <code>mtree_load</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *mtree_load(struct maple_tree *mt, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8202ad30)
Location: lib/maple_tree.c:6152
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:find_active_uprobe
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:do_mincore
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:vma_to_resize
  - mm/madvise.c:madvise_populate
  - mm/mempolicy.c:do_get_mempolicy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff8202ad30-ffffffff8202b08a: mtree_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *mtree_load(struct maple_tree *mt, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820ab160)
Location: lib/maple_tree.c:6202
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:do_mincore
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:vma_to_resize
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
  - mm/mempolicy.c:do_get_mempolicy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff820ab160-ffffffff820ab4b6: mtree_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *mtree_load(struct maple_tree *mt, long unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82183f60)
Location: lib/maple_tree.c:6269
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:kstat_irqs_cpu
  - kernel/irq/irqdesc.c:kstat_incr_irq_this_cpu
  - kernel/irq/irqdesc.c:irq_get_percpu_devid_partition
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:__irq_get_desc_lock
  - kernel/irq/irqdesc.c:generic_handle_irq_safe
  - kernel/irq/irqdesc.c:generic_handle_irq
  - kernel/irq/irqdesc.c:free_desc
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/irq/irqdesc.c:irq_sysfs_init
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__access_remote_vm
  - mm/mincore.c:do_mincore
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:vma_merge
  - mm/mmap.c:vma_merge
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:vma_to_resize
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
  - mm/mempolicy.c:do_get_mempolicy
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff82183f60-ffffffff8218422d: mtree_load (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
