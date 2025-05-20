# Function: <code>__xchg_case_64</code>

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
In arch/arm64/mm/context.c (ffff8000100aff18)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1318)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_get_and_clear
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In kernel/fork.c (ffff8000100f3060)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In kernel/locking/qspinlock.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: False
```
```
In mm/vmstat.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: False
```
```
In mm/memory.c (ffff8000102fa044)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
```
```
In mm/mprotect.c (ffff80001030524c)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff80001030618c)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffff800010308464)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/rmap.c (0)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: False
```
```
In mm/vmalloc.c (ffff80001030c7c0)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
```
```
In mm/madvise.c (ffff80001031ec38)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/huge_memory.c (ffff800010357f90)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffff800010367ee0)
Location: arch/arm64/include/asm/cmpxchg.h:48
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
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
