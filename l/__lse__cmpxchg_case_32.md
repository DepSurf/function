# Function: <code>__lse__cmpxchg_case_32</code>

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
In arch/arm64/mm/fault.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In arch/arm64/mm/context.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In arch/arm64/mm/hugetlbpage.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In virt/kvm/arm/mmu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In kernel/fork.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In kernel/sched/core.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In kernel/locking/qspinlock.c (ffff80001016ac04)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:queued_spin_lock_slowpath
```
```
In kernel/locking/rtmutex.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In kernel/locking/qrwlock.c (ffff80001016c934)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
Inline callers:
  - kernel/locking/qrwlock.c:queued_write_lock_slowpath
```
```
In kernel/futex.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In mm/vmstat.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In mm/memory.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In mm/pgtable-generic.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In mm/slub.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In mm/page_idle.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In lib/lockref.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In lib/refcount.c (ffff800010637ae4)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d51ac)
Location: arch/arm64/include/asm/atomic_lse.h:366
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_cmdq_issue_cmdlist
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
