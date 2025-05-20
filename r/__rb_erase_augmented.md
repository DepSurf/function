# Function: <code>__rb_erase_augmented</code>

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
In arch/x86/mm/pat_rbtree.c (ffffffff81072076)
Location: include/linux/rbtree_augmented.h:137
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811b879e)
Location: include/linux/rbtree_augmented.h:137
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811c46ee)
Location: include/linux/rbtree_augmented.h:137
Inline: True
Inline callers:
  - mm/mmap.c:vma_rb_erase
```
```
In lib/rbtree.c (ffffffff813ef861)
Location: include/linux/rbtree_augmented.h:137
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
```
```
In lib/interval_tree.c (ffffffff81404bc0)
Location: include/linux/rbtree_augmented.h:137
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
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
In arch/x86/mm/pat_rbtree.c (ffffffff81072e50)
Location: include/linux/rbtree_augmented.h:150
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811d2e3e)
Location: include/linux/rbtree_augmented.h:150
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811e063e)
Location: include/linux/rbtree_augmented.h:150
Inline: True
Inline callers:
  - mm/mmap.c:vma_rb_erase
```
```
In lib/rbtree.c (ffffffff81436131)
Location: include/linux/rbtree_augmented.h:150
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
```
```
In lib/interval_tree.c (ffffffff8144c770)
Location: include/linux/rbtree_augmented.h:150
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
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
In arch/x86/mm/pat_rbtree.c (ffffffff81076a00)
Location: include/linux/rbtree_augmented.h:150
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811e2cfe)
Location: include/linux/rbtree_augmented.h:150
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811f056e)
Location: include/linux/rbtree_augmented.h:150
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/rbtree.c (ffffffff81453121)
Location: include/linux/rbtree_augmented.h:150
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
```
```
In lib/interval_tree.c (ffffffff8146b130)
Location: include/linux/rbtree_augmented.h:150
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107519b)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811ed16e)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811fb3fd)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff81470820)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff818f3341)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107b3db)
Location: include/linux/rbtree_augmented.h:163
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8120356b)
Location: include/linux/rbtree_augmented.h:163
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8121392d)
Location: include/linux/rbtree_augmented.h:163
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff8149cf50)
Location: include/linux/rbtree_augmented.h:163
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8197a121)
Location: include/linux/rbtree_augmented.h:163
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107e13b)
Location: include/linux/rbtree_augmented.h:164
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8122421f)
Location: include/linux/rbtree_augmented.h:164
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8123487d)
Location: include/linux/rbtree_augmented.h:164
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff814d21f0)
Location: include/linux/rbtree_augmented.h:164
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff819d66d0)
Location: include/linux/rbtree_augmented.h:164
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff81084cbb)
Location: include/linux/rbtree_augmented.h:164
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8123725f)
Location: include/linux/rbtree_augmented.h:164
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81247ffd)
Location: include/linux/rbtree_augmented.h:164
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff814e6b20)
Location: include/linux/rbtree_augmented.h:164
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a0e900)
Location: include/linux/rbtree_augmented.h:164
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff810888c0)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81248831)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8125a22d)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff8126b6b4)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81513456)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a7dda0)
Location: include/linux/rbtree_augmented.h:152
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff81089530)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81256c81)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812686c8)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff8127a636)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81533e96)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81ab50d0)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090dc0)
Location: include/linux/rbtree_augmented.h:198
Inline: True
```
```
In mm/interval_tree.c (ffffffff81284dac)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81298f5b)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812aacbc)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815982b7)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff815ef500)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090780)
Location: include/linux/rbtree_augmented.h:198
Inline: True
```
```
In mm/interval_tree.c (ffffffff8128f08c)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812a411b)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812b6393)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815b3cd7)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81613c37)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff81091220)
Location: include/linux/rbtree_augmented.h:198
Inline: True
```
```
In mm/interval_tree.c (ffffffff812946fd)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812a988b)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812bba81)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815beb47)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff815f7297)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a0da0)
Location: include/linux/rbtree_augmented.h:198
Inline: True
```
```
In mm/interval_tree.c (ffffffff812d4d5d)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812eae8b)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812fe464)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81625e77)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81664a27)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b4e10)
Location: include/linux/rbtree_augmented.h:198
Inline: True
```
```
In mm/interval_tree.c (ffffffff81333e4d)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8134dc0b)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff8136509e)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff816f69a7)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8177ed97)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810cfc50)
Location: include/linux/rbtree_augmented.h:198
Inline: True
```
```
In mm/interval_tree.c (ffffffff813aaacd)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff813e0e7e)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff817e8f67)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8203ba37)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d3290)
Location: include/linux/rbtree_augmented.h:198
Inline: True
```
```
In mm/interval_tree.c (ffffffff813dee9d)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff81415c33)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81828f47)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff820b9f17)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810dba20)
Location: include/linux/rbtree_augmented.h:224
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81160c44)
Location: include/linux/rbtree_augmented.h:224
Inline: True
Inline callers:
  - kernel/sched/fair.c:__dequeue_entity
```
```
In mm/interval_tree.c (ffffffff814095ad)
Location: include/linux/rbtree_augmented.h:224
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff8144270b)
Location: include/linux/rbtree_augmented.h:224
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff8187a957)
Location: include/linux/rbtree_augmented.h:224
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca15c7)
Location: include/linux/rbtree_augmented.h:224
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:rm_hole
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_remove
```
```
In lib/rbtree.c (ffffffff82194827)
Location: include/linux/rbtree_augmented.h:224
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In mm/interval_tree.c (ffff8000102ee558)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffff8000102ff928)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffff800010311994)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffff8000106407b4)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffff800010d8f148)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In mm/interval_tree.c (c0512384)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (c051e6cc)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (c052b36c)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (c07e6158)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (c0e898d4)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In mm/interval_tree.c (c0000000003b2650)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (c0000000003cb914)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (c0000000003e294c)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (c0000000007eac30)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (c000000000ed28b0)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In mm/interval_tree.c (ffffffe0002026bc)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffe00020d772)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffe0002194ac)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffe00046d0d8)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffe0008b79c0)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff810884f0)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8124f2d1)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81260d18)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81272c86)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff8152c476)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a53f20)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff81077150)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81242271)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81253138)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81264bf6)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff8151c756)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a11000)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff810884a0)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8124d071)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8125eab8)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81270a26)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81528506)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81ac0310)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108a740)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8125ca31)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8126e488)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81280426)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81541ee6)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81acc7e0)
Location: include/linux/rbtree_augmented.h:198
Inline: True
Inline callers:
  - lib/rbtree.c:rb_erase
```
</details>
</li>
</ul>

## Differences
