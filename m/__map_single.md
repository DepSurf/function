# Function: <code>__map_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
dma_addr_t __map_single(struct device *dev, struct dma_ops_domain *dma_dom, phys_addr_t paddr, size_t size, int dir, bool align, u64 dma_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81530b80)
Location: drivers/iommu/amd_iommu.c:2371
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:map_sg
  - drivers/iommu/amd_iommu.c:map_page
  - drivers/iommu/amd_iommu.c:alloc_coherent
```
**Symbols:**

```
ffffffff81530b80-ffffffff81530fb3: __map_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81583980)
Location: drivers/iommu/amd_iommu.c:2283
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff81583980-ffffffff81583b25: __map_single.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b0c90)
Location: drivers/iommu/amd_iommu.c:2376
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff815b0c90-ffffffff815b0e35: __map_single.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c70e0)
Location: drivers/iommu/amd_iommu.c:2537
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff815c70e0-ffffffff815c729b: __map_single.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162dd70)
Location: drivers/iommu/amd_iommu.c:2319
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff8162dd70-ffffffff8162df2b: __map_single.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81668430)
Location: drivers/iommu/amd_iommu.c:2329
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff81668430-ffffffff816685e1: __map_single.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81686dc0)
Location: drivers/iommu/amd_iommu.c:2405
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff81686dc0-ffffffff81686f71: __map_single.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816be6d0)
Location: drivers/iommu/amd_iommu.c:2386
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff816be6d0-ffffffff816be887: __map_single.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e1a90)
Location: drivers/iommu/amd_iommu.c:2409
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff816e1a90-ffffffff816e1c58: __map_single.isra.0 (STB_LOCAL)
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a74e0)
Location: drivers/iommu/amd_iommu.c:2409
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff816a74e0-ffffffff816a76a8: __map_single.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684ed0)
Location: drivers/iommu/amd_iommu.c:2409
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff81684ed0-ffffffff81685098: __map_single.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d5750)
Location: drivers/iommu/amd_iommu.c:2409
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff816d5750-ffffffff816d5918: __map_single.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816f0080)
Location: drivers/iommu/amd_iommu.c:2409
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_coherent
  - drivers/iommu/amd_iommu.c:map_page
```
**Symbols:**

```
ffffffff816f0080-ffffffff816f0248: __map_single.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
