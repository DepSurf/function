# Function: <code>iommu_dma_alloc_pages</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81792187)
Location: drivers/iommu/dma-iommu.c:985
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817be959)
Location: drivers/iommu/dma-iommu.c:1129
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a17f9)
Location: drivers/iommu/dma-iommu.c:1149
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8182ae69)
Location: drivers/iommu/dma-iommu.c:1166
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff8196c267)
Location: drivers/iommu/dma-iommu.c:1325
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad47e0)
Location: drivers/iommu/dma-iommu.c:1402
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff81ad47e0-ffffffff81ad48f7: iommu_dma_alloc_pages.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b22fb0)
Location: drivers/iommu/dma-iommu.c:1446
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff81b22fb0-ffffffff81b230c4: iommu_dma_alloc_pages.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b79920)
Location: drivers/iommu/dma-iommu.c:1567
Inline: True
Direct callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
**Symbols:**

```
ffffffff81b79920-ffffffff81b79a34: iommu_dma_alloc_pages.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108ca390)
Location: drivers/iommu/dma-iommu.c:960
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
</details>
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
