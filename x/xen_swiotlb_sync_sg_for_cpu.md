# Function: <code>xen_swiotlb_sync_sg_for_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *hwdev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff814d5030)
Location: drivers/xen/swiotlb-xen.c:636
Inline: False
```
**Symbols:**

```
ffffffff814d5030-ffffffff814d508a: xen_swiotlb_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *hwdev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81526040)
Location: drivers/xen/swiotlb-xen.c:636
Inline: False
```
**Symbols:**

```
ffffffff81526040-ffffffff8152609a: xen_swiotlb_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *hwdev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81552550)
Location: drivers/xen/swiotlb-xen.c:645
Inline: False
```
**Symbols:**

```
ffffffff81552550-ffffffff815525aa: xen_swiotlb_sync_sg_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *hwdev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81566840)
Location: drivers/xen/swiotlb-xen.c:639
Inline: False
```
**Symbols:**

```
ffffffff81566840-ffffffff8156689b: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *hwdev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815ca9f0)
Location: drivers/xen/swiotlb-xen.c:639
Inline: False
```
**Symbols:**

```
ffffffff815ca9f0-ffffffff815caa4b: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *hwdev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81603250)
Location: drivers/xen/swiotlb-xen.c:625
Inline: False
```
**Symbols:**

```
ffffffff81603250-ffffffff816032aa: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *hwdev, struct scatterlist *sg, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161e2d0)
Location: drivers/xen/swiotlb-xen.c:613
Inline: False
```
**Symbols:**

```
ffffffff8161e2d0-ffffffff8161e32a: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816512f0)
Location: drivers/xen/swiotlb-xen.c:513
Inline: False
```
**Symbols:**

```
ffffffff816512f0-ffffffff81651348: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81673a50)
Location: drivers/xen/swiotlb-xen.c:505
Inline: False
```
**Symbols:**

```
ffffffff81673a50-ffffffff81673aa8: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81724070)
Location: drivers/xen/swiotlb-xen.c:511
Inline: False
```
**Symbols:**

```
ffffffff81724070-ffffffff817241fd: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81740bb0)
Location: drivers/xen/swiotlb-xen.c:529
Inline: False
```
**Symbols:**

```
ffffffff81740bb0-ffffffff81740c08: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81724550)
Location: drivers/xen/swiotlb-xen.c:516
Inline: False
```
**Symbols:**

```
ffffffff81724550-ffffffff817245a8: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff817a33a0)
Location: drivers/xen/swiotlb-xen.c:514
Inline: False
```
**Symbols:**

```
ffffffff817a33a0-ffffffff817a33f8: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff818dd490)
Location: drivers/xen/swiotlb-xen.c:350
Inline: False
```
**Symbols:**

```
ffffffff818dd490-ffffffff818dd503: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a30940)
Location: drivers/xen/swiotlb-xen.c:350
Inline: False
```
**Symbols:**

```
ffffffff81a30940-ffffffff81a309b3: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81a7a150)
Location: drivers/xen/swiotlb-xen.c:350
Inline: False
```
**Symbols:**

```
ffffffff81a7a150-ffffffff81a7a1c3: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81acc610)
Location: drivers/xen/swiotlb-xen.c:350
Inline: False
```
**Symbols:**

```
ffffffff81acc610-ffffffff81acc683: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
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
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffff80001083d9f8)
Location: drivers/xen/swiotlb-xen.c:505
Inline: False
```
**Symbols:**

```
ffff80001083d9f8-ffff80001083da70: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81639740)
Location: drivers/xen/swiotlb-xen.c:505
Inline: False
```
**Symbols:**

```
ffffffff81639740-ffffffff81639798: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81667890)
Location: drivers/xen/swiotlb-xen.c:505
Inline: False
```
**Symbols:**

```
ffffffff81667890-ffffffff816678e8: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_swiotlb_sync_sg_for_cpu(struct device *dev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81681e50)
Location: drivers/xen/swiotlb-xen.c:505
Inline: False
```
**Symbols:**

```
ffffffff81681e50-ffffffff81681ea8: xen_swiotlb_sync_sg_for_cpu (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>struct scatterlist *sgl</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *hwdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct scatterlist *sg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
