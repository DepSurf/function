# Function: <code>mod_memcg_state</code>

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
In kernel/fork.c (ffffffff810812e2)
Location: include/linux/memcontrol.h:513
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/page-writeback.c (ffffffff811c767a)
Location: include/linux/memcontrol.h:513
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/workingset.c (ffffffff811ee55c)
Location: include/linux/memcontrol.h:513
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff8122669f)
Location: include/linux/memcontrol.h:513
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
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
In kernel/fork.c (ffffffff81087bd2)
Location: include/linux/memcontrol.h:516
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
```
```
In mm/page-writeback.c (ffffffff811dc4a9)
Location: include/linux/memcontrol.h:516
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:clear_page_dirty_for_io
```
```
In mm/workingset.c (ffffffff812048ac)
Location: include/linux/memcontrol.h:516
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_refault
```
```
In mm/slub.c (ffffffff812416ec)
Location: include/linux/memcontrol.h:516
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
  - mm/slub.c:new_slab
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
In kernel/fork.c (ffffffff8108af42)
Location: include/linux/memcontrol.h:554
Inline: True
Inline callers:
  - kernel/fork.c:account_kernel_stack
  - kernel/fork.c:account_kernel_stack
```
```
In mm/memcontrol.c (ffffffff812866c5)
Location: include/linux/memcontrol.h:554
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
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
In kernel/fork.c (ffffffff8109360f)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In mm/memcontrol.c (ffffffff8129b635)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
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
In kernel/fork.c (ffffffff810983b4)
Location: include/linux/memcontrol.h:590
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
  - kernel/fork.c:account_kernel_stack
```
```
In mm/memcontrol.c (ffffffff812b6879)
Location: include/linux/memcontrol.h:590
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
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
In kernel/fork.c (ffffffff8109e98a)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/memcontrol.c (ffffffff812c8749)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mod_memcg_obj_state
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
In kernel/fork.c (ffffffff810a43f3)
Location: include/linux/memcontrol.h:603
Inline: True
Inline callers:
  - kernel/fork.c:memcg_charge_kernel_stack
```
```
In mm/memcontrol.c (ffffffff812fe017)
Location: include/linux/memcontrol.h:603
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mod_memcg_obj_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812854c1)
Location: include/linux/memcontrol.h:921
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_memcg_free_hook
```
```
In mm/memcontrol.c (ffffffff8130a4a7)
Location: include/linux/memcontrol.h:921
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8128a221)
Location: include/linux/memcontrol.h:966
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_memcg_free_hook
```
```
In mm/memcontrol.c (ffffffff81310d47)
Location: include/linux/memcontrol.h:966
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c95c6)
Location: include/linux/memcontrol.h:957
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_memcg_free_hook
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8135c021)
Location: include/linux/memcontrol.h:957
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mod_memcg_state(struct mem_cgroup *memcg, int idx, int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff81326040)
Location: include/linux/memcontrol.h:954
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/vmalloc.c (ffffffff81360500)
Location: include/linux/memcontrol.h:954
Inline: True
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
```
In mm/memcontrol.c (ffffffff813cf0b0)
Location: include/linux/memcontrol.h:954
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_charge_zswap
  - mm/memcontrol.c:obj_cgroup_charge_zswap
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff81326040-ffffffff8132607d: mod_memcg_state.constprop.0 (STB_LOCAL)
ffffffff81360500-ffffffff8136053d: mod_memcg_state.constprop.0 (STB_LOCAL)
ffffffff813cf0b0-ffffffff813cf0e6: mod_memcg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mod_memcg_state(struct mem_cgroup *memcg, int idx, int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff8139ae10)
Location: include/linux/memcontrol.h:962
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/vmalloc.c (ffffffff813dc0d0)
Location: include/linux/memcontrol.h:962
Inline: True
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:__vunmap
```
```
In mm/memcontrol.c (ffffffff814542d0)
Location: include/linux/memcontrol.h:962
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_charge_zswap
  - mm/memcontrol.c:obj_cgroup_charge_zswap
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff8139ae10-ffffffff8139ae5f: mod_memcg_state.constprop.0 (STB_LOCAL)
ffffffff813dc0d0-ffffffff813dc11f: mod_memcg_state.constprop.0 (STB_LOCAL)
ffffffff814542d0-ffffffff81454323: mod_memcg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mod_memcg_state(struct mem_cgroup *memcg, int idx, int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff813cded0)
Location: include/linux/memcontrol.h:978
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_memcg_post_alloc_hook
```
```
In mm/vmalloc.c (ffffffff81410af0)
Location: include/linux/memcontrol.h:978
Inline: True
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree
```
```
In mm/memcontrol.c (ffffffff8148a0a0)
Location: include/linux/memcontrol.h:978
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_charge_zswap
  - mm/memcontrol.c:obj_cgroup_charge_zswap
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff813cded0-ffffffff813cdf1f: mod_memcg_state.constprop.0 (STB_LOCAL)
ffffffff81410af0-ffffffff81410b3f: mod_memcg_state.constprop.0 (STB_LOCAL)
ffffffff8148a0a0-ffffffff8148a0f3: mod_memcg_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mod_memcg_state(struct mem_cgroup *memcg, int idx, int val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/percpu.c (ffffffff813f8840)
Location: include/linux/memcontrol.h:997
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143d450)
Location: include/linux/memcontrol.h:997
Inline: True
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/memcontrol.c (ffffffff814b98d0)
Location: include/linux/memcontrol.h:997
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_charge_zswap
  - mm/memcontrol.c:obj_cgroup_charge_zswap
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff813f8840-ffffffff813f888f: mod_memcg_state.constprop.0 (STB_LOCAL)
ffffffff8143d450-ffffffff8143d49f: mod_memcg_state.constprop.0 (STB_LOCAL)
ffffffff814b98d0-ffffffff814b9923: mod_memcg_state (STB_LOCAL)
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
In kernel/fork.c (ffff8000100f30ac)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - kernel/fork.c:dup_task_struct
```
```
In mm/memcontrol.c (ffff80001036b644)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mod_memcg_obj_state
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055cd64)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mod_memcg_obj_state
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045b130)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mod_memcg_obj_state
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000248d1a)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mod_memcg_obj_state
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
In kernel/fork.c (ffffffff810982aa)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/memcontrol.c (ffffffff812c0d29)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mod_memcg_obj_state
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
In kernel/fork.c (ffffffff81086d04)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/memcontrol.c (ffffffff812b1d99)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mod_memcg_obj_state
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
In kernel/fork.c (ffffffff8109825a)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/memcontrol.c (ffffffff812beb39)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mod_memcg_obj_state
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
In kernel/fork.c (ffffffff8109fe51)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:put_task_stack
```
```
In mm/memcontrol.c (ffffffff812cf5b2)
Location: include/linux/memcontrol.h:626
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_skmem
  - mm/memcontrol.c:mem_cgroup_charge_skmem
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mod_memcg_obj_state
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
