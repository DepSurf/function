# Function: <code>rb_set_parent</code>

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
In arch/x86/mm/pat_rbtree.c (ffffffff810720c1)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811b87dc)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811c472c)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - mm/mmap.c:vma_rb_erase
  - mm/mmap.c:vma_rb_erase
```
```
In lib/rbtree.c (ffffffff813ef608)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
```
```
In lib/interval_tree.c (ffffffff81404bfe)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
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
In arch/x86/mm/pat_rbtree.c (ffffffff81072e94)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811d2e7c)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811e067c)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - mm/mmap.c:vma_rb_erase
  - mm/mmap.c:vma_rb_erase
```
```
In lib/rbtree.c (ffffffff8143676a)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
```
```
In lib/interval_tree.c (ffffffff8144c7ae)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
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
In arch/x86/mm/pat_rbtree.c (ffffffff81076a44)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811e2d3c)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811f05ac)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/rbtree.c (ffffffff8145375a)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
```
```
In lib/interval_tree.c (ffffffff8146b16e)
Location: include/linux/rbtree_augmented.h:109
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
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
In arch/x86/mm/pat_rbtree.c (ffffffff810751d4)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811ed1af)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811fb446)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff81470861)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff818f39ca)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107b414)
Location: include/linux/rbtree_augmented.h:122
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff812035bc)
Location: include/linux/rbtree_augmented.h:122
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81213976)
Location: include/linux/rbtree_augmented.h:122
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff8149cfa1)
Location: include/linux/rbtree_augmented.h:122
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81979a9a)
Location: include/linux/rbtree_augmented.h:122
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107e177)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81224287)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812348c5)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff814d225c)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff819d634a)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff81084cf7)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff812372c7)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81248045)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff814e6b8c)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a0e57a)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
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
In arch/x86/mm/pat_rbtree.c (ffffffff810888fe)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81248880)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8125a27b)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff8126b700)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff815134a5)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a7d976)
Location: include/linux/rbtree_augmented.h:111
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108956e)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81256cd0)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81268718)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff8127a685)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81533ee5)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81ab4ca6)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090e0c)
Location: include/linux/rbtree_augmented.h:157
Inline: True
```
```
In mm/interval_tree.c (ffffffff81284df8)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81298fa8)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812aad0a)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81598303)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff815ef8f9)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810907cc)
Location: include/linux/rbtree_augmented.h:157
Inline: True
```
```
In mm/interval_tree.c (ffffffff8128f0d8)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812a4168)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812b63df)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815b3d23)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81614059)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff8109126c)
Location: include/linux/rbtree_augmented.h:157
Inline: True
```
```
In mm/interval_tree.c (ffffffff81294749)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812a98d8)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812bbacd)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815beb93)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff815f76bc)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a0dec)
Location: include/linux/rbtree_augmented.h:157
Inline: True
```
```
In mm/interval_tree.c (ffffffff812d4da9)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812eaed8)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812fe4b0)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81625ec3)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81664e4c)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b4e5c)
Location: include/linux/rbtree_augmented.h:157
Inline: True
```
```
In mm/interval_tree.c (ffffffff81333e9b)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8134dc58)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff813650ea)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff816f69f5)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8177f315)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810cfc9c)
Location: include/linux/rbtree_augmented.h:157
Inline: True
```
```
In mm/interval_tree.c (ffffffff813aab1b)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff813e0edc)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff817e8fb5)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8203bff5)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d32dc)
Location: include/linux/rbtree_augmented.h:157
Inline: True
```
```
In mm/interval_tree.c (ffffffff813deeeb)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff81415c91)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81828f95)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff820ba565)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810dba6c)
Location: include/linux/rbtree_augmented.h:183
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81160c90)
Location: include/linux/rbtree_augmented.h:183
Inline: True
Inline callers:
  - kernel/sched/fair.c:__dequeue_entity
  - kernel/sched/fair.c:__dequeue_entity
```
```
In mm/interval_tree.c (ffffffff814095fb)
Location: include/linux/rbtree_augmented.h:183
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff81442769)
Location: include/linux/rbtree_augmented.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff8187a9a5)
Location: include/linux/rbtree_augmented.h:183
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca160f)
Location: include/linux/rbtree_augmented.h:183
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:rm_hole
  - drivers/gpu/drm/drm_mm.c:rm_hole
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_remove
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_remove
```
```
In lib/rbtree.c (ffffffff82194e75)
Location: include/linux/rbtree_augmented.h:183
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (ffff8000102ee598)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffff8000102ff968)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffff8000103119d4)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffff8000106407f4)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffff800010d8f5d0)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (c05123e0)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (c051e724)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (c052b3c0)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (c07e61b4)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (c0e89d9c)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (c0000000003b26ac)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (c0000000003cb96c)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (c0000000003e29a8)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (c0000000007eac8c)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (c000000000ed2228)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (ffffffe0002026e0)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffe00020d79e)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffe0002194d2)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffe00046d0fc)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffe0008b7ca8)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108852e)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8124f320)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81260d68)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81272cd5)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff8152c4c5)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a53af6)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107718e)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff812422c0)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81253188)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81264c45)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff8151c7a5)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a10bd6)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff810884de)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8124d0c0)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8125eb08)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81270a75)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81528555)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81abfee6)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108a77e)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8125ca80)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8126e4d8)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81280475)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81541f35)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81acc3b6)
Location: include/linux/rbtree_augmented.h:157
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node_rcu
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_erase_color
```
</details>
</li>
</ul>

## Differences
