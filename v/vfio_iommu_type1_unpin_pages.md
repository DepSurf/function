# Function: <code>vfio_iommu_type1_unpin_pages</code>

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
int vfio_iommu_type1_unpin_pages(void *iommu_data, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3880)
Location: drivers/vfio/vfio_iommu_type1.c:627
Inline: False
```
**Symbols:**

```
ffffffff817d3880-ffffffff817d3988: vfio_iommu_type1_unpin_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_iommu_type1_unpin_pages(void *iommu_data, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189f390)
Location: drivers/vfio/vfio_iommu_type1.c:736
Inline: False
```
**Symbols:**

```
ffffffff8189f390-ffffffff8189f492: vfio_iommu_type1_unpin_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_iommu_type1_unpin_pages(void *iommu_data, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae4d0)
Location: drivers/vfio/vfio_iommu_type1.c:760
Inline: False
```
**Symbols:**

```
ffffffff818ae4d0-ffffffff818ae5d2: vfio_iommu_type1_unpin_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_iommu_type1_unpin_pages(void *iommu_data, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818911b0)
Location: drivers/vfio/vfio_iommu_type1.c:954
Inline: False
```
**Symbols:**

```
ffffffff818911b0-ffffffff8189129f: vfio_iommu_type1_unpin_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_unpin_pages(void *iommu_data, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:955
Inline: False
```
**Symbols:**

```
ffffffff819251a0-ffffffff819252a2: vfio_iommu_type1_unpin_pages (STB_LOCAL)
ffffffff81d11a2c-ffffffff81d11a41: vfio_iommu_type1_unpin_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_iommu_type1_unpin_pages(void *iommu_data, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (0)
Location: drivers/vfio/vfio_iommu_type1.c:953
Inline: False
```
**Symbols:**

```
ffffffff81a7ade0-ffffffff81a7aeec: vfio_iommu_type1_unpin_pages (STB_LOCAL)
ffffffff81edc677-ffffffff81edc68c: vfio_iommu_type1_unpin_pages.cold (STB_LOCAL)
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
int vfio_iommu_type1_unpin_pages(void *iommu_data, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d930)
Location: drivers/vfio/vfio_iommu_type1.c:627
Inline: False
```
**Symbols:**

```
ffffffff8177d930-ffffffff8177da38: vfio_iommu_type1_unpin_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_iommu_type1_unpin_pages(void *iommu_data, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8700)
Location: drivers/vfio/vfio_iommu_type1.c:627
Inline: False
```
**Symbols:**

```
ffffffff817c8700-ffffffff817c8808: vfio_iommu_type1_unpin_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_iommu_type1_unpin_pages(void *iommu_data, long unsigned int *user_pfn, int npage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e29a0)
Location: drivers/vfio/vfio_iommu_type1.c:627
Inline: False
```
**Symbols:**

```
ffffffff817e29a0-ffffffff817e2aa8: vfio_iommu_type1_unpin_pages (STB_LOCAL)
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
