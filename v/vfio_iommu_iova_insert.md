# Function: <code>vfio_iommu_iova_insert</code>

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
int vfio_iommu_iova_insert(struct list_head *head, dma_addr_t start, dma_addr_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d2b90)
Location: drivers/vfio/vfio_iommu_type1.c:1439
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_aper_resize
```
**Symbols:**

```
ffffffff817d2b90-ffffffff817d2bef: vfio_iommu_iova_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f4db)
Location: drivers/vfio/vfio_iommu_type1.c:1780
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_aper_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae32b)
Location: drivers/vfio/vfio_iommu_type1.c:1807
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_aper_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189170b)
Location: drivers/vfio/vfio_iommu_type1.c:2027
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_aper_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192540b)
Location: drivers/vfio/vfio_iommu_type1.c:2029
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_aper_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7af2b)
Location: drivers/vfio/vfio_iommu_type1.c:2019
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_aper_resize
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
int vfio_iommu_iova_insert(struct list_head *head, dma_addr_t start, dma_addr_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177cc40)
Location: drivers/vfio/vfio_iommu_type1.c:1439
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_aper_resize
```
**Symbols:**

```
ffffffff8177cc40-ffffffff8177cc9f: vfio_iommu_iova_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_iommu_iova_insert(struct list_head *head, dma_addr_t start, dma_addr_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7a10)
Location: drivers/vfio/vfio_iommu_type1.c:1439
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_aper_resize
```
**Symbols:**

```
ffffffff817c7a10-ffffffff817c7a6f: vfio_iommu_iova_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_iommu_iova_insert(struct list_head *head, dma_addr_t start, dma_addr_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e1cb0)
Location: drivers/vfio/vfio_iommu_type1.c:1439
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_iova_get_copy
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_exclude
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_aper_resize
```
**Symbols:**

```
ffffffff817e1cb0-ffffffff817e1d0f: vfio_iommu_iova_insert (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
