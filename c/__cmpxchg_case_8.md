# Function: <code>__cmpxchg_case_8</code>

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
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In arch/arm64/mm/context.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In arch/arm64/mm/hugetlbpage.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In virt/kvm/arm/mmu.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In kernel/fork.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In kernel/sched/core.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In kernel/locking/rtmutex.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In kernel/locking/qrwlock.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In kernel/futex.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In mm/vmstat.c (ffff8000102db42c)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: True
Inline callers:
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:dec_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_page_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:inc_node_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:mod_node_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:dec_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:inc_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
  - mm/vmstat.c:mod_zone_page_state
```
```
In mm/memory.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In mm/pgtable-generic.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In mm/rmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In mm/slub.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In mm/huge_memory.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In mm/page_idle.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In fs/proc/task_mmu.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In lib/lockref.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In lib/refcount.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
```
```
In drivers/iommu/arm-smmu-v3.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:115
Inline: False
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
