# Function: <code>iommu_dma_get_resv_regions</code>

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
void iommu_dma_get_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81791810)
Location: drivers/iommu/dma-iommu.c:161
Inline: False
```
**Symbols:**

```
ffffffff81791810-ffffffff8179181b: iommu_dma_get_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iommu_dma_get_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817bda40)
Location: drivers/iommu/dma-iommu.c:183
Inline: False
```
**Symbols:**

```
ffffffff817bda40-ffffffff817bda4b: iommu_dma_get_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iommu_dma_get_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff817a0c80)
Location: drivers/iommu/dma-iommu.c:187
Inline: False
```
**Symbols:**

```
ffffffff817a0c80-ffffffff817a0c8b: iommu_dma_get_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iommu_dma_get_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81829c80)
Location: drivers/iommu/dma-iommu.c:187
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
```
**Symbols:**

```
ffffffff81829c80-ffffffff81829c8b: iommu_dma_get_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iommu_dma_get_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81969fb0)
Location: drivers/iommu/dma-iommu.c:384
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
```
**Symbols:**

```
ffffffff81969fb0-ffffffff81969fbf: iommu_dma_get_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_dma_get_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81ad4020)
Location: drivers/iommu/dma-iommu.c:388
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
```
**Symbols:**

```
ffffffff81ad4020-ffffffff81ad402f: iommu_dma_get_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_dma_get_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b227f0)
Location: drivers/iommu/dma-iommu.c:389
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
```
**Symbols:**

```
ffffffff81b227f0-ffffffff81b227ff: iommu_dma_get_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_dma_get_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffffffff81b79370)
Location: drivers/iommu/dma-iommu.c:470
Inline: False
Direct callers:
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
```
**Symbols:**

```
ffffffff81b79370-ffffffff81b7937f: iommu_dma_get_resv_regions (STB_GLOBAL)
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
void iommu_dma_get_resv_regions(struct device *dev, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dma-iommu.c (ffff8000108c8c38)
Location: drivers/iommu/dma-iommu.c:160
Inline: False
Direct callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_get_resv_regions
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_get_resv_regions
  - drivers/iommu/virtio-iommu.c:viommu_get_resv_regions
```
**Symbols:**

```
ffff8000108c8c38-ffff8000108c8c94: iommu_dma_get_resv_regions (STB_GLOBAL)
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
</ul>
