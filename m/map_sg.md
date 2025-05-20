# Function: <code>map_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81530fc0)
Location: drivers/iommu/amd_iommu.c:2555
Inline: False
```
**Symbols:**

```
ffffffff81530fc0-ffffffff81531149: map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81584990)
Location: drivers/iommu/amd_iommu.c:2445
Inline: False
```
**Symbols:**

```
ffffffff81584990-ffffffff81584c1d: map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b1a70)
Location: drivers/iommu/amd_iommu.c:2538
Inline: False
```
**Symbols:**

```
ffffffff815b1a70-ffffffff815b1d01: map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c7700)
Location: drivers/iommu/amd_iommu.c:2699
Inline: False
```
**Symbols:**

```
ffffffff815c7700-ffffffff815c799c: map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162e3d0)
Location: drivers/iommu/amd_iommu.c:2480
Inline: False
```
**Symbols:**

```
ffffffff8162e3d0-ffffffff8162e66c: map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:2490
Inline: False
```
**Symbols:**

```
ffffffff81669140-ffffffff81669334: map_sg (STB_LOCAL)
ffffffff8166b511-ffffffff8166b5c5: map_sg.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:2566
Inline: False
```
**Symbols:**

```
ffffffff816879a0-ffffffff81687b9b: map_sg (STB_LOCAL)
ffffffff81689c52-ffffffff81689d29: map_sg.cold.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:2544
Inline: False
```
**Symbols:**

```
ffffffff816bf130-ffffffff816bf349: map_sg (STB_LOCAL)
ffffffff816c126b-ffffffff816c132f: map_sg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:2574
Inline: False
```
**Symbols:**

```
ffffffff816e24d0-ffffffff816e26df: map_sg (STB_LOCAL)
ffffffff816e428e-ffffffff816e4352: map_sg.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:2574
Inline: False
```
**Symbols:**

```
ffffffff816a7f20-ffffffff816a812f: map_sg (STB_LOCAL)
ffffffff816a9d6e-ffffffff816a9e32: map_sg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:2574
Inline: False
```
**Symbols:**

```
ffffffff81685910-ffffffff81685b1f: map_sg (STB_LOCAL)
ffffffff816876ce-ffffffff81687792: map_sg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:2574
Inline: False
```
**Symbols:**

```
ffffffff816d6190-ffffffff816d639f: map_sg (STB_LOCAL)
ffffffff816d7f4e-ffffffff816d8012: map_sg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int map_sg(struct device *dev, struct scatterlist *sglist, int nelems, enum dma_data_direction direction, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:2574
Inline: False
```
**Symbols:**

```
ffffffff816f0740-ffffffff816f094f: map_sg (STB_LOCAL)
ffffffff816f24fe-ffffffff816f25c2: map_sg.cold (STB_LOCAL)
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
<b>Param added. </b>
<code>enum dma_data_direction direction</code>
</li>
<li>
<b>Param removed. </b>
<code>enum dma_data_direction dir</code>
</li>
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
