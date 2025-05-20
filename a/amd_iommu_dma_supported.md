# Function: <code>amd_iommu_dma_supported</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152e8b0)
Location: drivers/iommu/amd_iommu.c:2744
Inline: False
```
**Symbols:**

```
ffffffff8152e8b0-ffffffff8152e8e6: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81584830)
Location: drivers/iommu/amd_iommu.c:2633
Inline: False
```
**Symbols:**

```
ffffffff81584830-ffffffff81584843: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b1910)
Location: drivers/iommu/amd_iommu.c:2726
Inline: False
```
**Symbols:**

```
ffffffff815b1910-ffffffff815b1923: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c7c70)
Location: drivers/iommu/amd_iommu.c:2887
Inline: True
```
**Symbols:**

```
ffffffff815c7c70-ffffffff815c7ca5: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162e200)
Location: drivers/iommu/amd_iommu.c:2668
Inline: True
```
**Symbols:**

```
ffffffff8162e200-ffffffff8162e235: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81668f70)
Location: drivers/iommu/amd_iommu.c:2678
Inline: True
```
**Symbols:**

```
ffffffff81668f70-ffffffff81668fa5: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816877d0)
Location: drivers/iommu/amd_iommu.c:2759
Inline: True
```
**Symbols:**

```
ffffffff816877d0-ffffffff81687805: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bef60)
Location: drivers/iommu/amd_iommu.c:2740
Inline: True
```
**Symbols:**

```
ffffffff816bef60-ffffffff816bef98: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e2300)
Location: drivers/iommu/amd_iommu.c:2772
Inline: True
```
**Symbols:**

```
ffffffff816e2300-ffffffff816e2338: amd_iommu_dma_supported (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a7d50)
Location: drivers/iommu/amd_iommu.c:2772
Inline: True
```
**Symbols:**

```
ffffffff816a7d50-ffffffff816a7d88: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685740)
Location: drivers/iommu/amd_iommu.c:2772
Inline: True
```
**Symbols:**

```
ffffffff81685740-ffffffff81685778: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d5fc0)
Location: drivers/iommu/amd_iommu.c:2772
Inline: True
```
**Symbols:**

```
ffffffff816d5fc0-ffffffff816d5ff8: amd_iommu_dma_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int amd_iommu_dma_supported(struct device *dev, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816f0570)
Location: drivers/iommu/amd_iommu.c:2772
Inline: True
```
**Symbols:**

```
ffffffff816f0570-ffffffff816f05a8: amd_iommu_dma_supported (STB_LOCAL)
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
