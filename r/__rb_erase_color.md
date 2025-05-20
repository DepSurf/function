# Function: <code>__rb_erase_color</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff813ef470)
Location: lib/rbtree.c:396
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/mmap.c:vma_rb_erase
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff813ef470-ffffffff813ef6cb: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81435d40)
Location: lib/rbtree.c:396
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:vma_rb_erase
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff81435d40-ffffffff81435f9b: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81452d30)
Location: lib/rbtree.c:411
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff81452d30-ffffffff81452f8b: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff818f2f40)
Location: lib/rbtree.c:411
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff818f2f40-ffffffff818f31aa: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819793a0)
Location: lib/rbtree.c:426
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff819793a0-ffffffff81979614: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d6400)
Location: lib/rbtree.c:426
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff819d6400-ffffffff819d6671: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0e630)
Location: lib/rbtree.c:426
Inline: True
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff81a0e630-ffffffff81a0e8a1: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a7d630)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff81a7d630-ffffffff81a7d8a5: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ab4960)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff81ab4960-ffffffff81ab4bd5: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815ef2c0)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff815ef2c0-ffffffff815ef4fe: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff816139f0)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff816139f0-ffffffff81613c30: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815f7050)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff815f7050-ffffffff815f7290: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff816647e0)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff816647e0-ffffffff81664a20: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8177eb20)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff8177eb20-ffffffff8177ed84: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8203b7b0)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff8203b7b0-ffffffff8203ba14: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff820b9c90)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff820b9c90-ffffffff820b9ef9: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff821945a0)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - kernel/sched/fair.c:__dequeue_entity
  - mm/interval_tree.c:__anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_remove
  - drivers/gpu/drm/drm_mm.c:rm_hole
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_remove
```
**Symbols:**

```
ffffffff821945a0-ffffffff82194809: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffff800010d8eec0)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffff800010d8eec0-ffff800010d8f148: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c0e8964c)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
c0e8964c-c0e898c8: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c000000000ed1cf0)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
c000000000ed1cf0-c000000000ed20f0: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffe0008b77ca)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffe0008b77ca-ffffffe0008b79c0: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a537b0)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff81a537b0-ffffffff81a53a25: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a10890)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff81a10890-ffffffff81a10b05: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81abfba0)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff81abfba0-ffffffff81abfe15: __rb_erase_color (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __rb_erase_color(struct rb_node *parent, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81acc070)
Location: lib/rbtree.c:410
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_erase
  - mm/interval_tree.c:anon_vma_interval_tree_remove
  - mm/interval_tree.c:vma_interval_tree_remove
  - mm/mmap.c:__vma_rb_erase
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - lib/interval_tree.c:interval_tree_remove
```
**Symbols:**

```
ffffffff81acc070-ffffffff81acc2e5: __rb_erase_color (STB_GLOBAL)
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
