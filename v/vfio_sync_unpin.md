# Function: <code>vfio_sync_unpin</code>

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
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3a60)
Location: drivers/vfio/vfio_iommu_type1.c:661
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff817d3a60-ffffffff817d3b26: vfio_sync_unpin.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e840)
Location: drivers/vfio/vfio_iommu_type1.c:770
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:unmap_unpin_fast
```
**Symbols:**

```
ffffffff8189e840-ffffffff8189e906: vfio_sync_unpin.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ad980)
Location: drivers/vfio/vfio_iommu_type1.c:794
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:unmap_unpin_fast
```
**Symbols:**

```
ffffffff818ad980-ffffffff818ada4f: vfio_sync_unpin.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818909d0)
Location: drivers/vfio/vfio_iommu_type1.c:988
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff818909d0-ffffffff81890a9f: vfio_sync_unpin.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819244b0)
Location: drivers/vfio/vfio_iommu_type1.c:989
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff819244b0-ffffffff81924588: vfio_sync_unpin.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79db0)
Location: drivers/vfio/vfio_iommu_type1.c:987
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff81a79db0-ffffffff81a79e9c: vfio_sync_unpin.isra.0 (STB_LOCAL)
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
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177db10)
Location: drivers/vfio/vfio_iommu_type1.c:661
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff8177db10-ffffffff8177dbd6: vfio_sync_unpin.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c88e0)
Location: drivers/vfio/vfio_iommu_type1.c:661
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff817c88e0-ffffffff817c89a6: vfio_sync_unpin.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2b80)
Location: drivers/vfio/vfio_iommu_type1.c:661
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
  - drivers/vfio/vfio_iommu_type1.c:vfio_unmap_unpin
```
**Symbols:**

```
ffffffff817e2b80-ffffffff817e2c41: vfio_sync_unpin.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
