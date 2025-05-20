# Function: <code>map_vm_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ce1f0)
Location: mm/vmalloc.c:1294
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff811ce1f0-ffffffff811ce232: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ead90)
Location: mm/vmalloc.c:1318
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff811ead90-ffffffff811eadd2: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fbff0)
Location: mm/vmalloc.c:1301
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff811fbff0-ffffffff811fc032: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81206cd0)
Location: mm/vmalloc.c:1352
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff81206cd0-ffffffff81206d12: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8121fd50)
Location: mm/vmalloc.c:1350
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
  - drivers/base/dma-mapping.c:dma_common_contiguous_remap
  - drivers/base/dma-mapping.c:dma_common_pages_remap
```
**Symbols:**

```
ffffffff8121fd50-ffffffff8121fd92: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81240de0)
Location: mm/vmalloc.c:1337
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_contiguous_remap
  - kernel/dma/mapping.c:dma_common_pages_remap
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff81240de0-ffffffff81240e22: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812556a0)
Location: mm/vmalloc.c:1338
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff812556a0-ffffffff812556e2: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81267a00)
Location: mm/vmalloc.c:1999
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff81267a00-ffffffff81267a41: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81276350)
Location: mm/vmalloc.c:2006
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff81276350-ffffffff81276391: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030c498)
Location: mm/vmalloc.c:2006
Inline: False
Direct callers:
  - kernel/dma/remap.c:__dma_common_pages_remap
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffff80001030c498-ffff80001030c4f8: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c05288fc)
Location: mm/vmalloc.c:2006
Inline: False
Direct callers:
  - kernel/dma/remap.c:__dma_common_pages_remap
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
c05288fc-c0528968: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dc7e0)
Location: mm/vmalloc.c:2006
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
c0000000003dc7e0-c0000000003dc84c: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000215954)
Location: mm/vmalloc.c:2006
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
```
**Symbols:**

```
ffffffe000215954-ffffffe0002159aa: map_vm_area (STB_GLOBAL)
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
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126e9a0)
Location: mm/vmalloc.c:2006
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff8126e9a0-ffffffff8126e9e1: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81260a70)
Location: mm/vmalloc.c:2006
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff81260a70-ffffffff81260ab1: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126c740)
Location: mm/vmalloc.c:2006
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff8126c740-ffffffff8126c781: map_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int map_vm_area(struct vm_struct *area, pgprot_t prot, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127c280)
Location: mm/vmalloc.c:2006
Inline: False
Direct callers:
  - mm/vmalloc.c:vmap
  - mm/zsmalloc.c:zs_map_object
```
**Symbols:**

```
ffffffff8127c280-ffffffff8127c2c1: map_vm_area (STB_GLOBAL)
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
