# Function: <code>vfio_dma_do_map</code>

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
int vfio_dma_do_map(struct vfio_iommu *iommu, struct vfio_iommu_type1_dma_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d5480)
Location: drivers/vfio/vfio_iommu_type1.c:1071
Inline: False
```
**Symbols:**

```
ffffffff817d5480-ffffffff817d58d6: vfio_dma_do_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_dma_do_map(struct vfio_iommu *iommu, struct vfio_iommu_type1_dma_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a04c0)
Location: drivers/vfio/vfio_iommu_type1.c:1296
Inline: False
```
**Symbols:**

```
ffffffff818a04c0-ffffffff818a080f: vfio_dma_do_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_dma_do_map(struct vfio_iommu *iommu, struct vfio_iommu_type1_dma_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818af460)
Location: drivers/vfio/vfio_iommu_type1.c:1323
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_ioctl
```
**Symbols:**

```
ffffffff818af460-ffffffff818af7af: vfio_dma_do_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_dma_do_map(struct vfio_iommu *iommu, struct vfio_iommu_type1_dma_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81893be0)
Location: drivers/vfio/vfio_iommu_type1.c:1553
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_ioctl
```
**Symbols:**

```
ffffffff81893be0-ffffffff81894034: vfio_dma_do_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_dma_do_map(struct vfio_iommu *iommu, struct vfio_iommu_type1_dma_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:1554
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_ioctl
```
**Symbols:**

```
ffffffff819277a0-ffffffff81927bcd: vfio_dma_do_map (STB_LOCAL)
ffffffff81d11db2-ffffffff81d11e2a: vfio_dma_do_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_dma_do_map(struct vfio_iommu *iommu, struct vfio_iommu_type1_dma_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:1552
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_ioctl
```
**Symbols:**

```
ffffffff81a7caa0-ffffffff81a7cf3e: vfio_dma_do_map (STB_LOCAL)
ffffffff81edc93b-ffffffff81edc9b6: vfio_dma_do_map.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfio_dma_do_map(struct vfio_iommu *iommu, struct vfio_iommu_type1_dma_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177f530)
Location: drivers/vfio/vfio_iommu_type1.c:1071
Inline: False
```
**Symbols:**

```
ffffffff8177f530-ffffffff8177f986: vfio_dma_do_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_dma_do_map(struct vfio_iommu *iommu, struct vfio_iommu_type1_dma_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817ca300)
Location: drivers/vfio/vfio_iommu_type1.c:1071
Inline: False
```
**Symbols:**

```
ffffffff817ca300-ffffffff817ca756: vfio_dma_do_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_dma_do_map(struct vfio_iommu *iommu, struct vfio_iommu_type1_dma_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e45a0)
Location: drivers/vfio/vfio_iommu_type1.c:1071
Inline: False
```
**Symbols:**

```
ffffffff817e45a0-ffffffff817e49f1: vfio_dma_do_map (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
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
