# Function: <code>count_memcg_event_mm</code>

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
In mm/filemap.c (ffffffff811ba8bc)
Location: include/linux/memcontrol.h:642
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff811bd476)
Location: include/linux/memcontrol.h:642
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/shmem.c (ffffffff811d9dc9)
Location: include/linux/memcontrol.h:642
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff811f495b)
Location: include/linux/memcontrol.h:642
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff812ab908)
Location: include/linux/memcontrol.h:642
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ce077)
Location: include/linux/memcontrol.h:646
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff811d209b)
Location: include/linux/memcontrol.h:646
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/shmem.c (ffffffff811efaae)
Location: include/linux/memcontrol.h:646
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff8120c7b8)
Location: include/linux/memcontrol.h:646
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff812cf255)
Location: include/linux/memcontrol.h:646
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811efbff)
Location: include/linux/memcontrol.h:714
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff81211251)
Location: include/linux/memcontrol.h:714
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff812302a1)
Location: include/linux/memcontrol.h:714
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff812f9a99)
Location: include/linux/memcontrol.h:714
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81201e5a)
Location: include/linux/memcontrol.h:754
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8122319e)
Location: include/linux/memcontrol.h:754
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff81242c51)
Location: include/linux/memcontrol.h:754
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff8130da44)
Location: include/linux/memcontrol.h:754
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81217c8a)
Location: include/linux/memcontrol.h:734
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff812331c1)
Location: include/linux/memcontrol.h:734
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff81254af6)
Location: include/linux/memcontrol.h:734
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff81335c71)
Location: include/linux/memcontrol.h:734
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122555e)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff812413e2)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff81263056)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff81349871)
Location: include/linux/memcontrol.h:771
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81253534)
Location: include/linux/memcontrol.h:749
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8126dc3d)
Location: include/linux/memcontrol.h:749
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff81294e32)
Location: include/linux/memcontrol.h:749
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812e9670)
Location: include/linux/memcontrol.h:749
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (ffffffff8138eae6)
Location: include/linux/memcontrol.h:749
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81258820)
Location: include/linux/memcontrol.h:1020
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff81276490)
Location: include/linux/memcontrol.h:1020
Inline: True
Direct callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff8129f6b6)
Location: include/linux/memcontrol.h:1020
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812f4b10)
Location: include/linux/memcontrol.h:1020
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (ffffffff8139df20)
Location: include/linux/memcontrol.h:1020
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff81258820-ffffffff81258874: count_memcg_event_mm.constprop.0 (STB_LOCAL)
ffffffff81276490-ffffffff812764e4: count_memcg_event_mm.constprop.0 (STB_LOCAL)
ffffffff8139df20-ffffffff8139df74: count_memcg_event_mm.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8125ce80)
Location: include/linux/memcontrol.h:1061
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8127d0c0)
Location: include/linux/memcontrol.h:1061
Inline: True
Direct callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff812a46b6)
Location: include/linux/memcontrol.h:1061
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff812fb091)
Location: include/linux/memcontrol.h:1061
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (ffffffff813a6c60)
Location: include/linux/memcontrol.h:1061
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff8125ce80-ffffffff8125cee1: count_memcg_event_mm.constprop.0 (STB_LOCAL)
ffffffff8127d0c0-ffffffff8127d121: count_memcg_event_mm.constprop.0 (STB_LOCAL)
ffffffff813a6c60-ffffffff813a6cc1: count_memcg_event_mm.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81299630)
Location: include/linux/memcontrol.h:1053
Inline: True
Direct callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff812bb210)
Location: include/linux/memcontrol.h:1053
Inline: True
Direct callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff812e5969)
Location: include/linux/memcontrol.h:1053
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff81344efa)
Location: include/linux/memcontrol.h:1053
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (ffffffff813f6b20)
Location: include/linux/memcontrol.h:1053
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff81299630-ffffffff8129968e: count_memcg_event_mm.constprop.0 (STB_LOCAL)
ffffffff812bb210-ffffffff812bb26e: count_memcg_event_mm.constprop.0 (STB_LOCAL)
ffffffff813f6b20-ffffffff813f6b7e: count_memcg_event_mm.constprop.0 (STB_LOCAL)
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
In mm/filemap.c (ffffffff812f48fa)
Location: include/linux/memcontrol.h:1086
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff813187bc)
Location: include/linux/memcontrol.h:1086
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff81347c79)
Location: include/linux/memcontrol.h:1086
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff813ba202)
Location: include/linux/memcontrol.h:1086
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (ffffffff8146a155)
Location: include/linux/memcontrol.h:1086
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/filemap.c (ffffffff8135e8ff)
Location: include/linux/memcontrol.h:1086
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8138c569)
Location: include/linux/memcontrol.h:1086
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff813c0069)
Location: include/linux/memcontrol.h:1086
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff8143c357)
Location: include/linux/memcontrol.h:1086
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (ffffffff814fabf2)
Location: include/linux/memcontrol.h:1086
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/filemap.c (ffffffff813917f7)
Location: include/linux/memcontrol.h:1102
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff813beb95)
Location: include/linux/memcontrol.h:1102
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff813f4d6f)
Location: include/linux/memcontrol.h:1102
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff8147172f)
Location: include/linux/memcontrol.h:1102
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (ffffffff81532045)
Location: include/linux/memcontrol.h:1102
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/filemap.c (ffffffff813bb57e)
Location: include/linux/memcontrol.h:1110
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff813e9b9a)
Location: include/linux/memcontrol.h:1110
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/memory.c (ffffffff814213df)
Location: include/linux/memcontrol.h:1110
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
```
```
In mm/huge_memory.c (ffffffff814a2110)
Location: include/linux/memcontrol.h:1110
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In fs/dax.c (ffffffff81566f35)
Location: include/linux/memcontrol.h:1110
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
</details>
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
In mm/filemap.c (ffff8000102b273c)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffff8000102d3b38)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffff8000102fa33c)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffff80001040a340)
Location: include/linux/memcontrol.h:771
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04df9b8)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (c04fba90)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (c051bc88)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000368d14)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (c000000000392900)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (c0000000003c44a8)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (c0000000005164fc)
Location: include/linux/memcontrol.h:771
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8068)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffe0001ef86a)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffe000209af2)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffe0002b3f14)
Location: include/linux/memcontrol.h:771
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121dbae)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff81239a32)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff8125b6a6)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff81341e51)
Location: include/linux/memcontrol.h:771
Inline: True
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
In mm/filemap.c (ffffffff81210d78)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff8122ca62)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff8124dc86)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff81332809)
Location: include/linux/memcontrol.h:771
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121b94e)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff812377d2)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff81259446)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff8133f921)
Location: include/linux/memcontrol.h:771
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122a9a5)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff81246d13)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/memory.c (ffffffff81268e46)
Location: include/linux/memcontrol.h:771
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff813532ed)
Location: include/linux/memcontrol.h:771
Inline: True
```
</details>
</li>
</ul>

## Differences
