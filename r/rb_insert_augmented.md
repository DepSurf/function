# Function: <code>rb_insert_augmented</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81071f6c)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
```
```
In mm/interval_tree.c (ffffffff811b877e)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:anon_vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff811c4ba1)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In lib/interval_tree.c (ffffffff81404bb2)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81072be9)
Location: include/linux/rbtree_augmented.h:57
Inline: True
```
```
In mm/interval_tree.c (ffffffff811d2e18)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff811e09c1)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In lib/interval_tree.c (ffffffff8144c762)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81076799)
Location: include/linux/rbtree_augmented.h:57
Inline: True
```
```
In mm/interval_tree.c (ffffffff811e2cd8)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff811f08f1)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In lib/interval_tree.c (ffffffff8146b122)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81074e97)
Location: include/linux/rbtree_augmented.h:57
Inline: True
```
```
In mm/interval_tree.c (ffffffff811ed146)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff811fb746)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In lib/interval_tree.c (ffffffff81470811)
Location: include/linux/rbtree_augmented.h:57
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107b0c7)
Location: include/linux/rbtree_augmented.h:59
Inline: True
```
```
In mm/interval_tree.c (ffffffff8120348a)
Location: include/linux/rbtree_augmented.h:59
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_insert_after
```
```
In mm/mmap.c (ffffffff81213c76)
Location: include/linux/rbtree_augmented.h:59
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107deaa)
Location: include/linux/rbtree_augmented.h:60
Inline: True
```
```
In mm/interval_tree.c (ffffffff81224158)
Location: include/linux/rbtree_augmented.h:60
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_insert_after
```
```
In mm/mmap.c (ffffffff81234bab)
Location: include/linux/rbtree_augmented.h:60
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
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
In arch/x86/mm/pat_rbtree.c (ffffffff81084a2a)
Location: include/linux/rbtree_augmented.h:60
Inline: True
```
```
In mm/interval_tree.c (ffffffff81237198)
Location: include/linux/rbtree_augmented.h:60
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_insert_after
```
```
In mm/mmap.c (ffffffff8124832b)
Location: include/linux/rbtree_augmented.h:60
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
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
In arch/x86/mm/pat_rbtree.c (ffffffff810886b8)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff812487ce)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff8125a576)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff8126812c)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81513401)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff81089328)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff81256c1e)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff81268b77)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff81277848)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81533e41)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090d52)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff812855aa)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff81299ba2)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/vmalloc.c (ffffffff812ab1cc)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81598264)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090712)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff8128f88a)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff812a4d36)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/vmalloc.c (ffffffff812b6679)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815b3c84)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810911b2)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff81294eea)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff812aa497)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/vmalloc.c (ffffffff812bbd67)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815beaf1)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a0d32)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff812d554a)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff812ebab5)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/vmalloc.c (ffffffff812fe1a3)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81625e21)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b4d92)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff8133474e)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff8134e6f1)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
```
```
In mm/vmalloc.c (ffffffff81365404)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff816f6921)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810cfbc2)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff813ab418)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/vmalloc.c (ffffffff813e0cea)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff817e8ed1)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d3202)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff813df7be)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/vmalloc.c (ffffffff81415a8d)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81828eb1)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810db992)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81160337)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - kernel/sched/fair.c:__enqueue_entity
```
```
In mm/interval_tree.c (ffffffff81409ece)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/vmalloc.c (ffffffff81442568)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff8187a8c1)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca1111)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:add_hole
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_add_node
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
In mm/interval_tree.c (ffff8000102ee4dc)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffff8000103000f0)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffff80001030dd6c)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffff80001064075c)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In mm/interval_tree.c (c051232c)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (c051ebb0)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (c05297ac)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (c07e610c)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In mm/interval_tree.c (c0000000003b25b4)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (c0000000003cbf30)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (c0000000003de9c8)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (c0000000007eabb0)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In mm/interval_tree.c (ffffffe00020265e)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffe00020dabc)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffe000215ef0)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffe00046d084)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff810882e8)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff8124f26e)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff812611c7)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff8126fe98)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffff8152c421)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff81076f48)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff8124220e)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff812535e7)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff81261e08)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffff8151c701)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff81088298)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff8124d00e)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff8125ef67)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff8126dc38)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815284b1)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108a538)
Location: include/linux/rbtree_augmented.h:47
Inline: True
```
```
In mm/interval_tree.c (ffffffff8125c9ce)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
```
```
In mm/mmap.c (ffffffff8126e937)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_rb
```
```
In mm/vmalloc.c (ffffffff8127d5f8)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81541e91)
Location: include/linux/rbtree_augmented.h:47
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_insert
```
</details>
</li>
</ul>

## Differences
