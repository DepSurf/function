# Function: <code>intel_map_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153abb0)
Location: drivers/iommu/intel-iommu.c:3713
Inline: False
```
**Symbols:**

```
ffffffff8153abb0-ffffffff8153addc: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158f690)
Location: drivers/iommu/intel-iommu.c:3810
Inline: False
```
**Symbols:**

```
ffffffff8158f690-ffffffff8158f8ab: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bced0)
Location: drivers/iommu/intel-iommu.c:3901
Inline: False
```
**Symbols:**

```
ffffffff815bced0-ffffffff815bd0e3: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d2b00)
Location: drivers/iommu/intel-iommu.c:3893
Inline: True
```
**Symbols:**

```
ffffffff815d2b00-ffffffff815d2d07: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81639800)
Location: drivers/iommu/intel-iommu.c:3798
Inline: True
```
**Symbols:**

```
ffffffff81639800-ffffffff81639a10: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81674a30)
Location: drivers/iommu/intel-iommu.c:3846
Inline: True
```
**Symbols:**

```
ffffffff81674a30-ffffffff81674be7: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81693060)
Location: drivers/iommu/intel-iommu.c:3863
Inline: True
```
**Symbols:**

```
ffffffff81693060-ffffffff81693217: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816cb410)
Location: drivers/iommu/intel-iommu.c:3703
Inline: True
```
**Symbols:**

```
ffffffff816cb410-ffffffff816cb5a7: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eee70)
Location: drivers/iommu/intel-iommu.c:3719
Inline: True
```
**Symbols:**

```
ffffffff816eee70-ffffffff816ef09a: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a62c0)
Location: drivers/iommu/intel/iommu.c:3590
Inline: False
```
**Symbols:**

```
ffffffff817a62c0-ffffffff817a64f7: intel_map_sg (STB_LOCAL)
```
</details>
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
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b4660)
Location: drivers/iommu/intel-iommu.c:3719
Inline: True
```
**Symbols:**

```
ffffffff816b4660-ffffffff816b488a: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816922a0)
Location: drivers/iommu/intel-iommu.c:3719
Inline: True
```
**Symbols:**

```
ffffffff816922a0-ffffffff816924ca: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e2b30)
Location: drivers/iommu/intel-iommu.c:3719
Inline: True
```
**Symbols:**

```
ffffffff816e2b30-ffffffff816e2d5a: intel_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int intel_map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fd190)
Location: drivers/iommu/intel-iommu.c:3719
Inline: True
```
**Symbols:**

```
ffffffff816fd190-ffffffff816fd3db: intel_map_sg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs *attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
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
