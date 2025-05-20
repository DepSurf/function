# Function: <code>__ll_sc__cmpxchg_case_64</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/fault.c (ffff8000100ad2c8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:ptep_set_access_flags
```
```
In arch/arm64/mm/context.c (ffff8000100afe90)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1720)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect
```
```
In virt/kvm/arm/mmu.c (ffff8000100ca454)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
  - virt/kvm/arm/mmu.c:kvm_age_hva_handler
  - virt/kvm/arm/mmu.c:stage2_wp_range
  - virt/kvm/arm/mmu.c:stage2_wp_range
  - virt/kvm/arm/mmu.c:stage2_wp_range
```
```
In kernel/fork.c (ffff8000100f19a0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
```
```
In kernel/sched/core.c (ffff800010137e10)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_q_add_safe
  - kernel/sched/core.c:wake_q_add
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
```
```
In kernel/locking/rtmutex.c (ffff80001016b14c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
```
```
In kernel/locking/qrwlock.c (0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
```
```
In kernel/futex.c (ffff8000101b7db4)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/vmstat.c (0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
```
```
In mm/memory.c (ffff8000102f66a8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/pgtable-generic.c (ffff8000103080fc)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_clear_flush_young
```
```
In mm/rmap.c (ffff800010309f98)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
```
In mm/slub.c (ffff800010347128)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - mm/slub.c:put_cpu_partial
```
```
In mm/huge_memory.c (ffff800010356fc8)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/page_idle.c (ffff80001037966c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/proc/task_mmu.c (ffff80001043abe0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/lockref.c (ffff800010629050)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - lib/lockref.c:lockref_put_return
```
```
In lib/refcount.c (0)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb318)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:arm_lpae_install_table
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d5064)
Location: arch/arm64/include/asm/atomic_ll_sc.h:302
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
```
</details>
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
