# Function: <code>iommu_dma_flush_iotlb_all</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_dma_flush_iotlb_all(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81791820)
Location: drivers/iommu/dma-iommu.c:276
Inline: False
```
**Symbols:**

```
ffffffff81791820-ffffffff8179183f: iommu_dma_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_dma_flush_iotlb_all(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bda50)
Location: drivers/iommu/dma-iommu.c:298
Inline: False
```
**Symbols:**

```
ffffffff817bda50-ffffffff817bda6f: iommu_dma_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_dma_flush_iotlb_all(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a0c90)
Location: drivers/iommu/dma-iommu.c:304
Inline: False
```
**Symbols:**

```
ffffffff817a0c90-ffffffff817a0caf: iommu_dma_flush_iotlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_dma_flush_iotlb_all(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81829c90)
Location: drivers/iommu/dma-iommu.c:304
Inline: False
```
**Symbols:**

```
ffffffff81829c90-ffffffff81829caf: iommu_dma_flush_iotlb_all (STB_LOCAL)
```
</details>
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
void iommu_dma_flush_iotlb_all(struct iova_domain *iovad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c8a48)
Location: drivers/iommu/dma-iommu.c:275
Inline: False
```
**Symbols:**

```
ffff8000108c8a48-ffff8000108c8a7c: iommu_dma_flush_iotlb_all (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
