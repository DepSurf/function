# Function: <code>__get_vm_area_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cd7e0)
Location: mm/vmalloc.c:1330
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:alloc_vm_area
```
**Symbols:**

```
ffffffff811cd7e0-ffffffff811cd90e: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ea8b0)
Location: mm/vmalloc.c:1354
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff811ea8b0-ffffffff811ea9e1: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fbb30)
Location: mm/vmalloc.c:1337
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff811fbb30-ffffffff811fbc6a: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81206850)
Location: mm/vmalloc.c:1388
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff81206850-ffffffff8120697b: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121f540)
Location: mm/vmalloc.c:1386
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff8121f540-ffffffff8121f671: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81241f90)
Location: mm/vmalloc.c:1373
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff81241f90-ffffffff812420f7: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81256690)
Location: mm/vmalloc.c:1374
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff81256690-ffffffff812567ee: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126a1a0)
Location: mm/vmalloc.c:2035
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff8126a1a0-ffffffff8126a30a: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812790b0)
Location: mm/vmalloc.c:2041
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff812790b0-ffffffff81279214: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812aa080)
Location: mm/vmalloc.c:2091
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
```
**Symbols:**

```
ffffffff812aa080-ffffffff812aa1e4: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b51c0)
Location: mm/vmalloc.c:2073
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
```
**Symbols:**

```
ffffffff812b51c0-ffffffff812b531f: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff812ba5b0)
Location: mm/vmalloc.c:2346
Inline: True
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
```
**Symbols:**

```
ffffffff812ba5b0-ffffffff812ba70a: __get_vm_area_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffff812fcbb0)
Location: mm/vmalloc.c:2398
Inline: True
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
```
**Symbols:**

```
ffffffff812fcbb0-ffffffff812fcd0a: __get_vm_area_node.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int shift, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81363d80)
Location: mm/vmalloc.c:2428
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
```
**Symbols:**

```
ffffffff81363d80-ffffffff81363ee4: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int shift, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813dfe90)
Location: mm/vmalloc.c:2490
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
```
**Symbols:**

```
ffffffff813dfe90-ffffffff813dfff4: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int shift, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81414bd0)
Location: mm/vmalloc.c:2570
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
```
**Symbols:**

```
ffffffff81414bd0-ffffffff81414d38: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int shift, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81441640)
Location: mm/vmalloc.c:2570
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
```
**Symbols:**

```
ffffffff81441640-ffffffff814417d7: __get_vm_area_node (STB_LOCAL)
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
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030f9d8)
Location: mm/vmalloc.c:2041
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffff80001030f9d8-ffff80001030fba8: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052bfd0)
Location: mm/vmalloc.c:2041
Inline: False
Direct callers:
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
c052bfd0-c052c108: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e0c00)
Location: mm/vmalloc.c:2041
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
c0000000003e0c00-c0000000003e0e90: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (ffffffe000217f7a)
Location: mm/vmalloc.c:2041
Inline: True
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffe000217f7a-ffffffe00021816e: __get_vm_area_node.isra.0 (STB_LOCAL)
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
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81271700)
Location: mm/vmalloc.c:2041
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff81271700-ffffffff81271864: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263670)
Location: mm/vmalloc.c:2041
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff81263670-ffffffff812637d4: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126f4a0)
Location: mm/vmalloc.c:2041
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff8126f4a0-ffffffff8126f604: __get_vm_area_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_struct *__get_vm_area_node(long unsigned int size, long unsigned int align, long unsigned int flags, long unsigned int start, long unsigned int end, int node, gfp_t gfp_mask, const void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127eec0)
Location: mm/vmalloc.c:2041
Inline: False
Direct callers:
  - mm/vmalloc.c:alloc_vm_area
  - mm/vmalloc.c:vmap
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:__get_vm_area_caller
  - mm/vmalloc.c:__get_vm_area
```
**Symbols:**

```
ffffffff8127eec0-ffffffff8127f022: __get_vm_area_node (STB_LOCAL)
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
