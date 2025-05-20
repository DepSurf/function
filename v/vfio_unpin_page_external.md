# Function: <code>vfio_unpin_page_external</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfio_unpin_page_external(struct vfio_dma *dma, dma_addr_t iova, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d37d0)
Location: drivers/vfio/vfio_iommu_type1.c:524
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff817d37d0-ffffffff817d3873: vfio_unpin_page_external (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f280)
Location: drivers/vfio/vfio_iommu_type1.c:614
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff8189f280-ffffffff8189f390: vfio_unpin_page_external.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae3c0)
Location: drivers/vfio/vfio_iommu_type1.c:637
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff818ae3c0-ffffffff818ae4d0: vfio_unpin_page_external.isra.0 (STB_LOCAL)
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
In drivers/vfio/vfio_iommu_type1.c (ffffffff81891110)
Location: drivers/vfio/vfio_iommu_type1.c:815
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff81891110-ffffffff818911a8: vfio_unpin_page_external.isra.0 (STB_LOCAL)
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
In drivers/vfio/vfio_iommu_type1.c (ffffffff81924c20)
Location: drivers/vfio/vfio_iommu_type1.c:816
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff81924c20-ffffffff81924cb8: vfio_unpin_page_external.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7acc0)
Location: drivers/vfio/vfio_iommu_type1.c:814
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff81a7acc0-ffffffff81a7addf: vfio_unpin_page_external.isra.0 (STB_LOCAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfio_unpin_page_external(struct vfio_dma *dma, dma_addr_t iova, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d880)
Location: drivers/vfio/vfio_iommu_type1.c:524
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff8177d880-ffffffff8177d923: vfio_unpin_page_external (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_unpin_page_external(struct vfio_dma *dma, dma_addr_t iova, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8650)
Location: drivers/vfio/vfio_iommu_type1.c:524
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff817c8650-ffffffff817c86f3: vfio_unpin_page_external (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_unpin_page_external(struct vfio_dma *dma, dma_addr_t iova, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e28f0)
Location: drivers/vfio/vfio_iommu_type1.c:524
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unpin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff817e28f0-ffffffff817e2993: vfio_unpin_page_external (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
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
