# Function: <code>free_vmap_area_rb_augment_cb_copy</code>

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
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126b70c)
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
ffffffff81266e60-ffffffff81266e69: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127a691)
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
ffffffff81275770-ffffffff81275779: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812aad16)
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
ffffffff812a6c10-ffffffff812a6c19: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b63eb)
Location: mm/vmalloc.c:483
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
ffffffff812b20b0-ffffffff812b20b9: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bbad9)
Location: mm/vmalloc.c:760
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
ffffffff812b7780-ffffffff812b7789: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fe4bc)
Location: mm/vmalloc.c:788
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
ffffffff812f9e90-ffffffff812f9e99: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813650f6)
Location: mm/vmalloc.c:778
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
ffffffff81360180-ffffffff81360193: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e0eed)
Location: mm/vmalloc.c:797
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
ffffffff813db290-ffffffff813db2a3: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81415ca2)
Location: mm/vmalloc.c:790
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
ffffffff8140fa60-ffffffff8140fa73: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8144277a)
Location: mm/vmalloc.c:790
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
ffffffff8143c3c0-ffffffff8143c3d3: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
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
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff8000103119ec)
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
ffff80001030bbe0-ffff80001030bbec: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052b3d0)
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
c0527b08-c0527b20: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e29b8)
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
c0000000003db910-c0000000003db91c: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe0002194e2)
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
ffffffe0002150bc-ffffffe0002150cc: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
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
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81272ce1)
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
ffffffff8126ddc0-ffffffff8126ddc9: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81264c51)
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
ffffffff8125fdf0-ffffffff8125fdf9: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270a81)
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
ffffffff8126bb60-ffffffff8126bb69: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_vmap_area_rb_augment_cb_copy(struct rb_node *rb_old, struct rb_node *rb_new);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81280482)
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
ffffffff8127b4f0-ffffffff8127b4f9: free_vmap_area_rb_augment_cb_copy (STB_LOCAL)
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
