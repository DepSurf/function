# Function: <code>alloc_vmap_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cd260)
Location: mm/vmalloc.c:351
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff811cd260-ffffffff811cd5c3: alloc_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ea2c0)
Location: mm/vmalloc.c:353
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff811ea2c0-ffffffff811ea678: alloc_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fb7c0)
Location: mm/vmalloc.c:353
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff811fb7c0-ffffffff811fbb30: alloc_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812064f0)
Location: mm/vmalloc.c:404
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812064f0-ffffffff81206846: alloc_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121f1e0)
Location: mm/vmalloc.c:402
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8121f1e0-ffffffff8121f536: alloc_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:402
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81241c30-ffffffff81241f89: alloc_vmap_area (STB_LOCAL)
ffffffff81243d30-ffffffff81243d44: alloc_vmap_area.cold.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:402
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81256330-ffffffff81256689: alloc_vmap_area (STB_LOCAL)
ffffffff81258430-ffffffff81258444: alloc_vmap_area.cold.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1052
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81269890-ffffffff8126a197: alloc_vmap_area (STB_LOCAL)
ffffffff8126bb77-ffffffff8126bbc6: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1049
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812787d0-ffffffff812790a2: alloc_vmap_area (STB_LOCAL)
ffffffff8127aa00-ffffffff8127aa1c: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1169
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812a9790-ffffffff812aa071: alloc_vmap_area (STB_LOCAL)
ffffffff812acbce-ffffffff812acbe2: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1160
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812b48d0-ffffffff812b51b7: alloc_vmap_area (STB_LOCAL)
ffffffff81be7b74-ffffffff81be7b88: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1460
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812b9cb0-ffffffff812ba5a4: alloc_vmap_area (STB_LOCAL)
ffffffff81bd9932-ffffffff81bd9946: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1510
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff812fc2b0-ffffffff812fcbaf: alloc_vmap_area (STB_LOCAL)
ffffffff81cbcee8-ffffffff81cbcf11: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1539
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81363480-ffffffff81363d71: alloc_vmap_area (STB_LOCAL)
ffffffff81e6eb93-ffffffff81e6ebc4: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1589
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff813df550-ffffffff813dfe79: alloc_vmap_area (STB_LOCAL)
ffffffff82064aa1-ffffffff82064abd: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask, long unsigned int va_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1582
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff814142b0-ffffffff81414bb3: alloc_vmap_area (STB_LOCAL)
ffffffff820e41a6-ffffffff820e41c3: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask, long unsigned int va_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1582
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81440d20-ffffffff81441623: alloc_vmap_area (STB_LOCAL)
ffffffff821c0dda-ffffffff821c0df7: alloc_vmap_area.cold (STB_LOCAL)
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
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030f168)
Location: mm/vmalloc.c:1049
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffff80001030f168-ffff80001030f9d8: alloc_vmap_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (c052b6e4)
Location: mm/vmalloc.c:1049
Inline: True
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
c052b6e4-c052bfd0: alloc_vmap_area.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e0210)
Location: mm/vmalloc.c:1049
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
c0000000003e0210-c0000000003e0bf8: alloc_vmap_area (STB_LOCAL)
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
In mm/vmalloc.c (ffffffe000217924)
Location: mm/vmalloc.c:1049
Inline: True
Direct callers:
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffe000217924-ffffffe000217f7a: alloc_vmap_area.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1049
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81270e20-ffffffff812716f2: alloc_vmap_area (STB_LOCAL)
ffffffff81273050-ffffffff8127306c: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1049
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff81262d90-ffffffff81263662: alloc_vmap_area (STB_LOCAL)
ffffffff81264fc0-ffffffff81264fdc: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1049
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8126ebc0-ffffffff8126f492: alloc_vmap_area (STB_LOCAL)
ffffffff81270df0-ffffffff81270e0c: alloc_vmap_area.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct vmap_area *alloc_vmap_area(long unsigned int size, long unsigned int align, long unsigned int vstart, long unsigned int vend, int node, gfp_t gfp_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:1049
Inline: False
Direct callers:
  - mm/vmalloc.c:__get_vm_area_node
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_map_ram
```
**Symbols:**

```
ffffffff8127e5a0-ffffffff8127eeb7: alloc_vmap_area (STB_LOCAL)
ffffffff81280860-ffffffff8128087c: alloc_vmap_area.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int va_flags</code>
</li>
</ul>
</details>
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
