# Function: <code>vma_lookup</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070b8a)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072796)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/events/uprobes.c (ffffffff81291081)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/memory.c (ffffffff812e7005)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/mmap.c (ffffffff812ef121)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
```
```
In mm/mremap.c (ffffffff812f1992)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - mm/mremap.c:vma_to_resize
```
```
In mm/mempolicy.c (ffffffff81327acc)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff8132dfb4)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - mm/ksm.c:find_mergeable_vma
```
```
In mm/migrate.c (ffffffff8133df17)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819241f4)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In net/ipv4/tcp.c (ffffffff81b5df06)
Location: include/linux/mm.h:2742
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107eb0a)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080a77)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_block
```
```
In kernel/events/uprobes.c (ffffffff812e6566)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/memory.c (ffffffff8134826c)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/mmap.c (ffffffff81352503)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
```
```
In mm/mremap.c (ffffffff813573cc)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:vma_to_resize
```
```
In mm/madvise.c (ffffffff81375deb)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - mm/madvise.c:madvise_populate
```
```
In mm/mempolicy.c (ffffffff81396c3b)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff8139e254)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - mm/ksm.c:find_mergeable_vma
```
```
In mm/migrate.c (ffffffff813b146d)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79607)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In net/ipv4/tcp.c (ffffffff81cec8e5)
Location: include/linux/mm.h:2817
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810902e2)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
```
```
In kernel/events/uprobes.c (ffffffff81350052)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
```
```
In mm/memory.c (ffffffff813c0724)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
```
```
In mm/mincore.c (ffffffff813c124e)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/mmap.c (ffffffff813cc509)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
```
```
In mm/mremap.c (ffffffff813d19b7)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:vma_to_resize
```
```
In mm/madvise.c (ffffffff813f364b)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - mm/madvise.c:madvise_populate
```
```
In mm/mempolicy.c (ffffffff814167cc)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff814221d1)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81432151)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81442d4a)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8144bae8)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/proc/base.c (ffffffff81537439)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In net/ipv4/tcp.c (ffffffff81eb07ee)
Location: include/linux/mm.h:2973
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810931ff)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
```
```
In kernel/events/uprobes.c (ffffffff81381224)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff813f5343)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__access_remote_vm
```
```
In mm/mincore.c (ffffffff813f5f9c)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/mmap.c (ffffffff81400e59)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:vma_merge
```
```
In mm/mremap.c (ffffffff814065b6)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:vma_to_resize
```
```
In mm/madvise.c (ffffffff81428edf)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
```
```
In mm/mempolicy.c (ffffffff81449cde)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff81456e8c)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff8146824a)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff81478616)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff8148138c)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/proc/base.c (ffffffff8156f62f)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b2a0ce)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81f0f2e9)
Location: include/linux/mm.h:3279
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a66f)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_zap_enclave_ptes
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_test_and_clear_young
```
```
In kernel/events/uprobes.c (ffffffff813aa5d4)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - kernel/events/uprobes.c:find_active_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff81415954)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:__access_remote_vm
```
```
In mm/mincore.c (ffffffff81421c4c)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/mincore.c:do_mincore
```
```
In mm/mmap.c (ffffffff8142d499)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/mmap.c:__do_sys_remap_file_pages
  - mm/mmap.c:vma_merge
```
```
In mm/mremap.c (ffffffff81432cc6)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:vma_to_resize
```
```
In mm/madvise.c (ffffffff8146270f)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/madvise.c:madvise_vma_behavior
  - mm/madvise.c:madvise_populate
```
```
In mm/mempolicy.c (ffffffff81483766)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/ksm.c (ffffffff8149198a)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:break_cow
```
```
In mm/migrate.c (ffffffff81496eaa)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff814a7d46)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff814b0407)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In fs/proc/base.c (ffffffff815a7fbf)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b8129e)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_handle_iopf
```
```
In net/ipv4/tcp.c (ffffffff81fd34c6)
Location: include/linux/mm.h:3456
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
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
