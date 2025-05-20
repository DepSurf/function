# Function: <code>bounce_sync_sg_for_cpu</code>

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
void bounce_sync_sg_for_cpu(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816eda00)
Location: drivers/iommu/intel-iommu.c:4008
Inline: False
```
**Symbols:**

```
ffffffff816eda00-ffffffff816eda5b: bounce_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bounce_sync_sg_for_cpu(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a30e0)
Location: drivers/iommu/intel/iommu.c:3885
Inline: False
```
**Symbols:**

```
ffffffff817a30e0-ffffffff817a313b: bounce_sync_sg_for_cpu (STB_LOCAL)
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
void bounce_sync_sg_for_cpu(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b3170)
Location: drivers/iommu/intel-iommu.c:4008
Inline: False
```
**Symbols:**

```
ffffffff816b3170-ffffffff816b31cb: bounce_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bounce_sync_sg_for_cpu(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81690e30)
Location: drivers/iommu/intel-iommu.c:4008
Inline: False
```
**Symbols:**

```
ffffffff81690e30-ffffffff81690e8b: bounce_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bounce_sync_sg_for_cpu(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e16c0)
Location: drivers/iommu/intel-iommu.c:4008
Inline: False
```
**Symbols:**

```
ffffffff816e16c0-ffffffff816e171b: bounce_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bounce_sync_sg_for_cpu(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fbcd0)
Location: drivers/iommu/intel-iommu.c:4008
Inline: False
```
**Symbols:**

```
ffffffff816fbcd0-ffffffff816fbd2b: bounce_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
