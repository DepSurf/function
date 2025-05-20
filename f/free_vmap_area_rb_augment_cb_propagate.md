# Function: <code>free_vmap_area_rb_augment_cb_propagate</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126b714)
Location: mm/vmalloc.c:401
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
  - mm/vmalloc.c:alloc_vmap_area
```
**Symbols:**

```
ffffffff81266e00-ffffffff81266e5a: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127a699)
Location: mm/vmalloc.c:399
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
**Symbols:**

```
ffffffff81275720-ffffffff8127576c: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812aad1f)
Location: mm/vmalloc.c:481
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
**Symbols:**

```
ffffffff812a75c0-ffffffff812a760e: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b62cd)
Location: mm/vmalloc.c:483
Inline: True
Inline callers:
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
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
**Symbols:**

```
ffffffff812b2840-ffffffff812b288e: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bb9bb)
Location: mm/vmalloc.c:760
Inline: True
Inline callers:
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
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
**Symbols:**

```
ffffffff812b7b70-ffffffff812b7bbe: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fdfe3)
Location: mm/vmalloc.c:788
Inline: True
Inline callers:
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
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
```
**Symbols:**

```
ffffffff812fa2a0-ffffffff812fa2ee: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81364f62)
Location: mm/vmalloc.c:778
Inline: True
Inline callers:
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
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
```
**Symbols:**

```
ffffffff81361120-ffffffff8136117a: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e0ab3)
Location: mm/vmalloc.c:797
Inline: True
Inline callers:
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
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
```
**Symbols:**

```
ffffffff813dc450-ffffffff813dc4aa: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8141585c)
Location: mm/vmalloc.c:790
Inline: True
Inline callers:
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
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
```
**Symbols:**

```
ffffffff81410d70-ffffffff81410dd5: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81442337)
Location: mm/vmalloc.c:790
Inline: True
Inline callers:
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
Direct callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
```
**Symbols:**

```
ffffffff8143d560-ffffffff8143d5c5: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
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
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff8000103119f4)
Location: mm/vmalloc.c:399
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
**Symbols:**

```
ffff80001030bb80-ffff80001030bbe0: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052b3d8)
Location: mm/vmalloc.c:399
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
```
**Symbols:**

```
c0527a94-c0527b08: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e29c0)
Location: mm/vmalloc.c:399
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
**Symbols:**

```
c0000000003db8a0-c0000000003db910: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe0002194e8)
Location: mm/vmalloc.c:399
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__free_vmap_area
  - mm/vmalloc.c:__free_vmap_area
```
**Symbols:**

```
ffffffe000215078-ffffffe0002150bc: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
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
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81272ce9)
Location: mm/vmalloc.c:399
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
**Symbols:**

```
ffffffff8126dd70-ffffffff8126ddbc: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81264c59)
Location: mm/vmalloc.c:399
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
**Symbols:**

```
ffffffff8125fda0-ffffffff8125fdec: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270a89)
Location: mm/vmalloc.c:399
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
**Symbols:**

```
ffffffff8126bb10-ffffffff8126bb5c: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_propagate(struct rb_node *rb, struct rb_node *stop);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8128048a)
Location: mm/vmalloc.c:399
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
**Symbols:**

```
ffffffff8127b4a0-ffffffff8127b4ec: free_vmap_area_rb_augment_cb_propagate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
