# Function: <code>mem_cgroup_from_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811f9960)
Location: mm/memcontrol.c:817
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:task_in_mem_cgroup
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/shmem.c:shmem_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/rmap.c:invalid_page_referenced_vma
  - fs/dax.c:__dax_fault
```
**Symbols:**

```
ffffffff811f9960-ffffffff811f997f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81222d65)
Location: mm/memcontrol.c:710
Inline: True
Inline callers:
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:get_mem_cgroup_from_mm
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
  - fs/dax.c:dax_fault
```
**Symbols:**

```
ffffffff8121d4a0-ffffffff8121d4bf: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236794)
Location: mm/memcontrol.c:712
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:get_mem_cgroup_from_mm
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8122fa10-ffffffff8122fa2f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81242245)
Location: mm/memcontrol.c:682
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:get_mem_cgroup_from_mm
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:oom_kill_process
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8123b260-ffffffff8123b27f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81262039)
Location: mm/memcontrol.c:696
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:get_mem_cgroup_from_mm
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:oom_kill_process
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8125aaf0-ffffffff8125ab0f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81286039)
Location: mm/memcontrol.c:667
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:get_mem_cgroup_from_mm
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:oom_kill_process
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
ffffffff8127e600-ffffffff8127e61f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129af9a)
Location: mm/memcontrol.c:805
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:task_in_mem_cgroup
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_getpage_gfp
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
ffffffff81292d00-ffffffff81292d1f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b626a)
Location: mm/memcontrol.c:922
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
ffffffff812adb40-ffffffff812adb5f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c8147)
Location: mm/memcontrol.c:933
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
ffffffff812bf690-ffffffff812bf6af: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fd9a7)
Location: mm/memcontrol.c:894
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff812f4930-ffffffff812f494f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309dcd)
Location: mm/memcontrol.c:997
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff813001f0-ffffffff8130020f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8131063d)
Location: mm/memcontrol.c:875
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81306f70-ffffffff81306f8f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135b94b)
Location: mm/memcontrol.c:915
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff81350c10-ffffffff81350c2f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d520d)
Location: mm/memcontrol.c:897
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_folio_referenced_vma
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff813c90f0-ffffffff813c911b: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145ac8d)
Location: mm/memcontrol.c:977
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/vmscan.c:lru_gen_migrate_mm
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_folio_referenced_vma
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff8144d970-ffffffff8144d99b: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814908de)
Location: mm/memcontrol.c:1002
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_mm
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/vmscan.c:lru_gen_migrate_mm
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_folio_referenced_vma
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff81483290-ffffffff814832bb: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814c024e)
Location: mm/memcontrol.c:1045
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_can_attach
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:get_mem_cgroup_from_current
  - mm/memcontrol.c:get_mem_cgroup_from_mm
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/vmscan.c:lru_gen_migrate_mm
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_folio_referenced_vma
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - fs/dax.c:dax_iomap_pte_fault
```
**Symbols:**

```
ffffffff814b2640-ffffffff814b266b: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036b058)
Location: mm/memcontrol.c:933
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
ffff800010361418-ffff800010361458: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055c6cc)
Location: mm/memcontrol.c:933
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
c0553924-c0553948: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045a790)
Location: mm/memcontrol.c:933
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
c00000000044cef0-c00000000044cf18: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe00024878a)
Location: mm/memcontrol.c:933
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
ffffffe000240aec-ffffffe000240b24: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0727)
Location: mm/memcontrol.c:933
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
ffffffff812b7c70-ffffffff812b7c8f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b17e7)
Location: mm/memcontrol.c:933
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
ffffffff812a8e40-ffffffff812a8e5f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be537)
Location: mm/memcontrol.c:933
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
ffffffff812b5a80-ffffffff812b5a9f: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_task(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cef58)
Location: mm/memcontrol.c:933
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
Direct callers:
  - mm/filemap.c:filemap_fault
  - mm/oom_kill.c:__oom_kill_process
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/rmap.c:invalid_page_referenced_vma
```
**Symbols:**

```
ffffffff812c5fa0-ffffffff812c5fbf: mem_cgroup_from_task (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
