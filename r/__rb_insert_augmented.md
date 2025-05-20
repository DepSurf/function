# Function: <code>__rb_insert_augmented</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff813efbb0)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - arch/x86/mm/pat_rbtree.c:rbt_memtype_check_insert
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff813efbb0-ffffffff813efdb4: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81436480)
Location: lib/rbtree.c:440
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81436480-ffffffff81436689: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81453470)
Location: lib/rbtree.c:455
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81453470-ffffffff81453679: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff818f36c0)
Location: lib/rbtree.c:457
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff818f36c0-ffffffff818f38e3: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, bool newleft, struct rb_node **leftmost, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81979e80)
Location: lib/rbtree.c:491
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81979e80-ffffffff8197a0c1: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, bool newleft, struct rb_node **leftmost, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d60a0)
Location: lib/rbtree.c:491
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff819d60a0-ffffffff819d625f: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, bool newleft, struct rb_node **leftmost, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0e2d0)
Location: lib/rbtree.c:491
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81a0e2d0-ffffffff81a0e48f: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a7db60)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81a7db60-ffffffff81a7dcf9: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ab4e90)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81ab4e90-ffffffff81ab5029: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815efad0)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff815efad0-ffffffff815efc6a: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81614230)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81614230-ffffffff816143ca: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815f7890)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff815f7890-ffffffff815f7a5e: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81665020)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81665020-ffffffff816651ee: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8177f580)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_link
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff8177f580-ffffffff8177f763: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8203c2a0)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff8203c2a0-ffffffff8203c483: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff820ba830)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff820ba830-ffffffff820ba9d0: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff82195140)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - kernel/sched/fair.c:__enqueue_entity
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
  - drivers/gpu/drm/drm_mm.c:add_hole
  - drivers/gpu/drm/drm_mm.c:drm_mm_interval_tree_add_node
```
**Symbols:**

```
ffffffff82195140-ffffffff821952e0: __rb_insert_augmented (STB_GLOBAL)
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
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffff800010d8f7f0)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffff800010d8f7f0-ffff800010d8f994: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c0e89ff8)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
c0e89ff8-c0e8a1c0: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c000000000ed2510)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
c000000000ed2510-c000000000ed2788: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffe0008b7e34)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffe0008b7e34-ffffffe0008b7f42: __rb_insert_augmented (STB_GLOBAL)
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
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a53ce0)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81a53ce0-ffffffff81a53e79: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a10dc0)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81a10dc0-ffffffff81a10f59: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ac00d0)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81ac00d0-ffffffff81ac0269: __rb_insert_augmented (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __rb_insert_augmented(struct rb_node *node, struct rb_root *root, void (*augment_rotate)(struct rb_node *, struct rb_node *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81acc5a0)
Location: lib/rbtree.c:456
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_insert
  - mm/interval_tree.c:vma_interval_tree_insert_after
  - mm/interval_tree.c:vma_interval_tree_insert
  - mm/mmap.c:__vma_link_rb
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - lib/interval_tree.c:interval_tree_insert
  - lib/interval_tree.c:interval_tree_insert
```
**Symbols:**

```
ffffffff81acc5a0-ffffffff81acc739: __rb_insert_augmented (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool newleft</code>
</li>
<li>
<b>Param added. </b>
<code>struct rb_node **leftmost</code>
</li>
<li>
<b>Param reordered. </b>
<code>node, root, augment_rotate</code> ➡️ <code>node, root, newleft, leftmost, augment_rotate</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool newleft</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rb_node **leftmost</code>
</li>
<li>
<b>Param reordered. </b>
<code>node, root, newleft, leftmost, augment_rotate</code> ➡️ <code>node, root, augment_rotate</code>
</li>
</ul>
</details>
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
