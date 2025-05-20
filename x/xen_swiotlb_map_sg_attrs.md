# Function: <code>xen_swiotlb_map_sg_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xen_swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff814d4b50)
Location: drivers/xen/swiotlb-xen.c:539
Inline: False
```
**Symbols:**

```
ffffffff814d4b50-ffffffff814d4e07: xen_swiotlb_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xen_swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81525b40)
Location: drivers/xen/swiotlb-xen.c:539
Inline: False
```
**Symbols:**

```
ffffffff81525b40-ffffffff81525e03: xen_swiotlb_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xen_swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81552050)
Location: drivers/xen/swiotlb-xen.c:546
Inline: False
```
**Symbols:**

```
ffffffff81552050-ffffffff8155231b: xen_swiotlb_map_sg_attrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xen_swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff81566aa0)
Location: drivers/xen/swiotlb-xen.c:561
Inline: True
```
**Symbols:**

```
ffffffff81566aa0-ffffffff81566d6d: xen_swiotlb_map_sg_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xen_swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff815cac50)
Location: drivers/xen/swiotlb-xen.c:561
Inline: True
```
**Symbols:**

```
ffffffff815cac50-ffffffff815caf1d: xen_swiotlb_map_sg_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xen_swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff816034a0)
Location: drivers/xen/swiotlb-xen.c:547
Inline: True
```
**Symbols:**

```
ffffffff816034a0-ffffffff81603776: xen_swiotlb_map_sg_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xen_swiotlb_map_sg_attrs(struct device *hwdev, struct scatterlist *sgl, int nelems, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/swiotlb-xen.c (ffffffff8161e560)
Location: drivers/xen/swiotlb-xen.c:535
Inline: True
```
**Symbols:**

```
ffffffff8161e560-ffffffff8161e86d: xen_swiotlb_map_sg_attrs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
</ul>
