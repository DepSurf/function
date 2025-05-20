# Function: <code>rb_set_parent_color</code>

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
In arch/x86/mm/pat_rbtree.c (ffffffff8107216c)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811b8898)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811c47e4)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - mm/mmap.c:vma_rb_erase
```
```
In lib/rbtree.c (ffffffff813ef499)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
```
```
In lib/interval_tree.c (ffffffff81404ca8)
Location: include/linux/rbtree_augmented.h:114
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
In arch/x86/mm/pat_rbtree.c (ffffffff81072efb)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811d2f3a)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811e0730)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - mm/mmap.c:vma_rb_erase
```
```
In lib/rbtree.c (ffffffff814364be)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
```
```
In lib/interval_tree.c (ffffffff8144c854)
Location: include/linux/rbtree_augmented.h:114
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
In arch/x86/mm/pat_rbtree.c (ffffffff81076aab)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811e2dfa)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811f0660)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/rbtree.c (ffffffff814534ae)
Location: include/linux/rbtree_augmented.h:114
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
```
```
In lib/interval_tree.c (ffffffff8146b214)
Location: include/linux/rbtree_augmented.h:114
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
In arch/x86/mm/pat_rbtree.c (ffffffff81075274)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff811ed2e4)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff811fb5a5)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff81470979)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff818f371b)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107b4b4)
Location: include/linux/rbtree_augmented.h:127
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff812036f5)
Location: include/linux/rbtree_augmented.h:127
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81213ad5)
Location: include/linux/rbtree_augmented.h:127
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff8149d0c3)
Location: include/linux/rbtree_augmented.h:127
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81979ee9)
Location: include/linux/rbtree_augmented.h:127
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8107e481)
Location: include/linux/rbtree_augmented.h:128
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff812243ea)
Location: include/linux/rbtree_augmented.h:128
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812349b5)
Location: include/linux/rbtree_augmented.h:128
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff814d238e)
Location: include/linux/rbtree_augmented.h:128
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff819d6105)
Location: include/linux/rbtree_augmented.h:128
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff81085001)
Location: include/linux/rbtree_augmented.h:128
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8123742a)
Location: include/linux/rbtree_augmented.h:128
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81248135)
Location: include/linux/rbtree_augmented.h:128
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In lib/interval_tree.c (ffffffff814e6cbe)
Location: include/linux/rbtree_augmented.h:128
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a0e335)
Location: include/linux/rbtree_augmented.h:128
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_erase_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_insert_color_cached
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff81088c0b)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff812489d8)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8125a36f)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff8126b904)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff815135c7)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a7dbbc)
Location: include/linux/rbtree_augmented.h:116
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff81089882)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81256e28)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812688dc)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff8127a8df)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81534005)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81ab4eec)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090eac)
Location: include/linux/rbtree_augmented.h:162
Inline: True
```
```
In mm/interval_tree.c (ffffffff81284eaf)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8129907c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812aadb1)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff8159839e)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff815efb12)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff8109086c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
```
```
In mm/interval_tree.c (ffffffff8128f18f)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812a423c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812b6483)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815b3dbe)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81614272)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff8109130c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
```
```
In mm/interval_tree.c (ffffffff81294800)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812a99ac)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812bbb71)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff815bec2e)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff815f79d3)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a0e8c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
```
```
In mm/interval_tree.c (ffffffff812d4e60)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff812eafac)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff812fe554)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff81625f5e)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81665163)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b4f04)
Location: include/linux/rbtree_augmented.h:162
Inline: True
```
```
In mm/interval_tree.c (ffffffff81333f59)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8134dd30)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81365192)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff816f6a9b)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8177f6cd)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810cfd44)
Location: include/linux/rbtree_augmented.h:162
Inline: True
```
```
In mm/interval_tree.c (ffffffff813aabd6)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff813e0f56)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff817e905b)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8203c3ed)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d3384)
Location: include/linux/rbtree_augmented.h:162
Inline: True
```
```
In mm/interval_tree.c (ffffffff813defa9)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff81415d0e)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff8182903b)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff820ba88b)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810dbb14)
Location: include/linux/rbtree_augmented.h:188
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81160d4d)
Location: include/linux/rbtree_augmented.h:188
Inline: True
Inline callers:
  - kernel/sched/fair.c:__dequeue_entity
```
```
In mm/interval_tree.c (ffffffff814096b9)
Location: include/linux/rbtree_augmented.h:188
Inline: True
Inline callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/vmalloc.c (ffffffff814427e6)
Location: include/linux/rbtree_augmented.h:188
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
```
```
In lib/interval_tree.c (ffffffff8187aa4b)
Location: include/linux/rbtree_augmented.h:188
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In drivers/gpu/drm/drm_mm.c (ffffffff81ca16b9)
Location: include/linux/rbtree_augmented.h:188
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mm.c:rm_hole
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_remove
```
```
In lib/rbtree.c (ffffffff8219519b)
Location: include/linux/rbtree_augmented.h:188
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (ffff8000102ee700)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffff8000102ffb40)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffff800010311bac)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffff800010640920)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffff800010d8f84c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (c0512564)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (c051e914)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (c052b5a4)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (c07e6300)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (c0e8a064)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (c0000000003b28b0)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (c0000000003cbbd0)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (c0000000003e2b9c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (c0000000007eae0c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (c000000000ed2594)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In mm/interval_tree.c (ffffffe0002027dc)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffe00020d8ea)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffe000219632)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
```
```
In lib/interval_tree.c (ffffffe00046d1ca)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffe0008b7e74)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff81088842)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8124f478)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff81260f2c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81272f2f)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff8152c5e5)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a53d3c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff810774a2)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff81242418)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8125334c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81264e9f)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff8151c8c5)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81a10e1c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff810887f2)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8124d218)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8125eccc)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81270ccf)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81528675)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81ac012c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
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
In arch/x86/mm/pat_rbtree.c (ffffffff8108aa92)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
```
```
In mm/interval_tree.c (ffffffff8125cbd8)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
```
```
In mm/mmap.c (ffffffff8126e69c)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__vma_rb_erase
```
```
In mm/vmalloc.c (ffffffff81280680)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
```
In lib/interval_tree.c (ffffffff81542055)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/interval_tree.c:interval_tree_remove
```
```
In lib/rbtree.c (ffffffff81acc5fc)
Location: include/linux/rbtree_augmented.h:162
Inline: True
Inline callers:
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:__rb_insert_augmented
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_erase
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:rb_insert_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
  - lib/rbtree.c:__rb_erase_color
```
</details>
</li>
</ul>

## Differences
