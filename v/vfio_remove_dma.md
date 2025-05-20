# Function: <code>vfio_remove_dma</code>

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
void vfio_remove_dma(struct vfio_iommu *iommu, struct vfio_dma *dma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3e50)
Location: drivers/vfio/vfio_iommu_type1.c:836
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff817d3e50-ffffffff817d3ea2: vfio_remove_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_remove_dma(struct vfio_iommu *iommu, struct vfio_dma *dma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189ed30)
Location: drivers/vfio/vfio_iommu_type1.c:945
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
```
**Symbols:**

```
ffffffff8189ed30-ffffffff8189edb1: vfio_remove_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_remove_dma(struct vfio_iommu *iommu, struct vfio_dma *dma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818addf0)
Location: drivers/vfio/vfio_iommu_type1.c:969
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
```
**Symbols:**

```
ffffffff818addf0-ffffffff818ade84: vfio_remove_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_remove_dma(struct vfio_iommu *iommu, struct vfio_dma *dma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890de0)
Location: drivers/vfio/vfio_iommu_type1.c:1163
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
```
**Symbols:**

```
ffffffff81890de0-ffffffff81890ea1: vfio_remove_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vfio_remove_dma(struct vfio_iommu *iommu, struct vfio_dma *dma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:1164
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
```
**Symbols:**

```
ffffffff819248e0-ffffffff819249b3: vfio_remove_dma (STB_LOCAL)
ffffffff81d1192e-ffffffff81d11943: vfio_remove_dma.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vfio_remove_dma(struct vfio_iommu *iommu, struct vfio_dma *dma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:1162
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_release
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_map_dma
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_unmap
```
**Symbols:**

```
ffffffff81a7a250-ffffffff81a7a32d: vfio_remove_dma (STB_LOCAL)
ffffffff81edc58b-ffffffff81edc5a0: vfio_remove_dma.cold (STB_LOCAL)
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
void vfio_remove_dma(struct vfio_iommu *iommu, struct vfio_dma *dma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177df00)
Location: drivers/vfio/vfio_iommu_type1.c:836
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff8177df00-ffffffff8177df52: vfio_remove_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_remove_dma(struct vfio_iommu *iommu, struct vfio_dma *dma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8cd0)
Location: drivers/vfio/vfio_iommu_type1.c:836
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff817c8cd0-ffffffff817c8d22: vfio_remove_dma (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_remove_dma(struct vfio_iommu *iommu, struct vfio_dma *dma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2f70)
Location: drivers/vfio/vfio_iommu_type1.c:836
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_all
  - drivers/vfio/vfio_iommu_type1.c:vfio_dma_do_map
```
**Symbols:**

```
ffffffff817e2f70-ffffffff817e2fc2: vfio_remove_dma (STB_LOCAL)
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
