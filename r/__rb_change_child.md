# Function: <code>__rb_change_child</code>

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
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811b8874)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811c47c0)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - mm/mmap.c:vma_rb_erase
  - mm/mmap.c:vma_rb_erase
  - mm/mmap.c:vma_rb_erase
```
```
In lib/rbtree.c (ffffffff813ef4b3)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_replace_node
```
```
In lib/interval_tree.c (ffffffff81404c84)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
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
In arch/x86/mm/pat_rbtree.c (ffffffff81072ed7)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811d2f16)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811e070c)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - mm/mmap.c:vma_rb_erase
  - mm/mmap.c:vma_rb_erase
  - mm/mmap.c:vma_rb_erase
```
```
In lib/rbtree.c (ffffffff8143671b)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
```
```
In lib/interval_tree.c (ffffffff8144c830)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
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
In arch/x86/mm/pat_rbtree.c (ffffffff81076a87)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811e2dd6)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811f063c)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/rbtree.c (ffffffff8145370b)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
```
```
In lib/interval_tree.c (ffffffff8146b1f0)
Location: include/linux/rbtree_augmented.h:121
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
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
In arch/x86/mm/pat_rbtree.c (ffffffff81075257)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811ed249)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811fb4ae)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff814708e3)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff818f397b)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107b497)
Location: include/linux/rbtree_augmented.h:134
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81203659)
Location: include/linux/rbtree_augmented.h:134
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812139de)
Location: include/linux/rbtree_augmented.h:134
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff8149d028)
Location: include/linux/rbtree_augmented.h:134
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81979a2b)
Location: include/linux/rbtree_augmented.h:134
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107e187)
Location: include/linux/rbtree_augmented.h:135
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81224323)
Location: include/linux/rbtree_augmented.h:135
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81234928)
Location: include/linux/rbtree_augmented.h:135
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff814d22e0)
Location: include/linux/rbtree_augmented.h:135
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff819d62e7)
Location: include/linux/rbtree_augmented.h:135
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff81084d07)
Location: include/linux/rbtree_augmented.h:135
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81237363)
Location: include/linux/rbtree_augmented.h:135
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812480a8)
Location: include/linux/rbtree_augmented.h:135
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff814e6c10)
Location: include/linux/rbtree_augmented.h:135
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a0e517)
Location: include/linux/rbtree_augmented.h:135
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108890f)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81248918)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8125a2dd)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff8126b793)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81513524)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a7d937)
Location: include/linux/rbtree_augmented.h:123
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108957f)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81256d68)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812687ea)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff8127a706)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81533f61)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81ab4c67)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090e8c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
```
```
In mm/interval_tree.c (ffffffff81284e8b)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81299058)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812aad8d)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff8159837e)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff815ef8aa)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff8109084c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
```
```
In mm/interval_tree.c (ffffffff8128f16b)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812a4218)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812b645f)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815b3d9e)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8161400a)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810912ec)
Location: include/linux/rbtree_augmented.h:169
Inline: True
```
```
In mm/interval_tree.c (ffffffff812947dc)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812a9988)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812bbb4d)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815bec0e)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff815f766d)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a0e6c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
```
```
In mm/interval_tree.c (ffffffff812d4e3c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812eaf88)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812fe530)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81625f3e)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81664dfd)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b4edc)
Location: include/linux/rbtree_augmented.h:169
Inline: True
```
```
In mm/interval_tree.c (ffffffff81333f31)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8134dd08)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff8136516a)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff816f6a73)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8177f296)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810cfd1c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
```
```
In mm/interval_tree.c (ffffffff813aabae)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff813e0f2e)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff817e9033)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8203bf66)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d335c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
```
```
In mm/interval_tree.c (ffffffff813def81)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff81415ce6)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81829013)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff820ba4d6)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810dbaec)
Location: include/linux/rbtree_augmented.h:195
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81160d25)
Location: include/linux/rbtree_augmented.h:195
Inline: True
Inline callers:
  - kernel/sched/fair.c:__dequeue_entity
  - kernel/sched/fair.c:__dequeue_entity
  - kernel/sched/fair.c:__dequeue_entity
```
```
In mm/interval_tree.c (ffffffff81409691)
Location: include/linux/rbtree_augmented.h:195
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff814427be)
Location: include/linux/rbtree_augmented.h:195
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff8187aa23)
Location: include/linux/rbtree_augmented.h:195
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca1691)
Location: include/linux/rbtree_augmented.h:195
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:rm_hole
  - drivers/gpu/drm/drm_mm.c:rm_hole
  - drivers/gpu/drm/drm_mm.c:rm_hole
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_remove
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_remove
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_remove
```
```
In lib/rbtree.c (ffffffff82194de6)
Location: include/linux/rbtree_augmented.h:195
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (ffff8000102ee640)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffff8000102ffa4c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffff800010311a70)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffff80001064088c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffff800010d8f588)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (c051248c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (c051e810)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (c052b4ac)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (c07e6248)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (c0e89d4c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (c0000000003b2764)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (c0000000003cba6c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (c0000000003e2ad0)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (c0000000007ead2c)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (c000000000ed21c4)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (ffffffe000202762)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffe00020d84e)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffe00021958a)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffe00046d168)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffe0008b7c70)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108853f)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8124f3b8)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81260e3a)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81272d56)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff8152c541)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a53ab7)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107719f)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81242358)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8125325a)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81264cc6)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff8151c821)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a10b97)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff810884ef)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8124d158)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8125ebda)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81270af6)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff815285d1)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81abfea7)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108a78f)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8125cb18)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8126e5aa)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812804f7)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81541fb1)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81acc377)
Location: include/linux/rbtree_augmented.h:169
Inline: True
Inline callers:
  - lib/rbtree.c:rb_replace_node
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
```
</details>
</li>
</ul>

## Differences
