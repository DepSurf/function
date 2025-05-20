# Function: <code>vfio_unmap_unpin</code>

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
long int vfio_unmap_unpin(struct vfio_iommu *iommu, struct vfio_dma *dma, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3b30)
Location: drivers/vfio/vfio_iommu_type1.c:752
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff817d3b30-ffffffff817d3e4c: vfio_unmap_unpin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int vfio_unmap_unpin(struct vfio_iommu *iommu, struct vfio_dma *dma, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189ea10)
Location: drivers/vfio/vfio_iommu_type1.c:861
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff8189ea10-ffffffff8189ec90: vfio_unmap_unpin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int vfio_unmap_unpin(struct vfio_iommu *iommu, struct vfio_dma *dma, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818adb50)
Location: drivers/vfio/vfio_iommu_type1.c:885
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_unmap_unpin_reaccount
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff818adb50-ffffffff818adde7: vfio_unmap_unpin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int vfio_unmap_unpin(struct vfio_iommu *iommu, struct vfio_dma *dma, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890aa0)
Location: drivers/vfio/vfio_iommu_type1.c:1079
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff81890aa0-ffffffff81890ddc: vfio_unmap_unpin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int vfio_unmap_unpin(struct vfio_iommu *iommu, struct vfio_dma *dma, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:1080
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff81924590-ffffffff819248db: vfio_unmap_unpin (STB_LOCAL)
ffffffff81d11913-ffffffff81d1192e: vfio_unmap_unpin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int vfio_unmap_unpin(struct vfio_iommu *iommu, struct vfio_dma *dma, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79ea0)
Location: drivers/vfio/vfio_iommu_type1.c:1078
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff81a79ea0-ffffffff81a7a244: vfio_unmap_unpin (STB_LOCAL)
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
long int vfio_unmap_unpin(struct vfio_iommu *iommu, struct vfio_dma *dma, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177dbe0)
Location: drivers/vfio/vfio_iommu_type1.c:752
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff8177dbe0-ffffffff8177defc: vfio_unmap_unpin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int vfio_unmap_unpin(struct vfio_iommu *iommu, struct vfio_dma *dma, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c89b0)
Location: drivers/vfio/vfio_iommu_type1.c:752
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff817c89b0-ffffffff817c8ccc: vfio_unmap_unpin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int vfio_unmap_unpin(struct vfio_iommu *iommu, struct vfio_dma *dma, bool do_accounting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2c50)
Location: drivers/vfio/vfio_iommu_type1.c:752
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_remove_dma
```
**Symbols:**

```
ffffffff817e2c50-ffffffff817e2f62: vfio_unmap_unpin (STB_LOCAL)
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
