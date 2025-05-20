# Function: <code>intel_unmap_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8153a380)
Location: drivers/iommu/intel-iommu.c:3692
Inline: False
```
**Symbols:**

```
ffffffff8153a380-ffffffff8153a394: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158ee30)
Location: drivers/iommu/intel-iommu.c:3780
Inline: False
```
**Symbols:**

```
ffffffff8158ee30-ffffffff8158eeb2: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bc950)
Location: drivers/iommu/intel-iommu.c:3871
Inline: False
```
**Symbols:**

```
ffffffff815bc950-ffffffff815bc9d2: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d27c0)
Location: drivers/iommu/intel-iommu.c:3863
Inline: False
```
**Symbols:**

```
ffffffff815d27c0-ffffffff815d2842: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816394c0)
Location: drivers/iommu/intel-iommu.c:3768
Inline: False
```
**Symbols:**

```
ffffffff816394c0-ffffffff81639542: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81674700)
Location: drivers/iommu/intel-iommu.c:3816
Inline: False
```
**Symbols:**

```
ffffffff81674700-ffffffff81674782: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692d30)
Location: drivers/iommu/intel-iommu.c:3833
Inline: False
```
**Symbols:**

```
ffffffff81692d30-ffffffff81692db2: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816cb350)
Location: drivers/iommu/intel-iommu.c:3684
Inline: False
```
**Symbols:**

```
ffffffff816cb350-ffffffff816cb40e: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eed50)
Location: drivers/iommu/intel-iommu.c:3698
Inline: False
```
**Symbols:**

```
ffffffff816eed50-ffffffff816eee68: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a3f60)
Location: drivers/iommu/intel/iommu.c:3572
Inline: False
```
**Symbols:**

```
ffffffff817a3f60-ffffffff817a4038: intel_unmap_sg (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b4540)
Location: drivers/iommu/intel-iommu.c:3698
Inline: False
```
**Symbols:**

```
ffffffff816b4540-ffffffff816b4658: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692180)
Location: drivers/iommu/intel-iommu.c:3698
Inline: False
```
**Symbols:**

```
ffffffff81692180-ffffffff81692298: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e2a10)
Location: drivers/iommu/intel-iommu.c:3698
Inline: False
```
**Symbols:**

```
ffffffff816e2a10-ffffffff816e2b28: intel_unmap_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_unmap_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fd070)
Location: drivers/iommu/intel-iommu.c:3698
Inline: False
```
**Symbols:**

```
ffffffff816fd070-ffffffff816fd190: intel_unmap_sg (STB_LOCAL)
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
