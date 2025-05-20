# Function: <code>vfio_iommu_resv_exclude</code>

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
int vfio_iommu_resv_exclude(struct list_head *iova, struct list_head *resv_regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d2d00)
Location: drivers/vfio/vfio_iommu_type1.c:1555
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff817d2d00-ffffffff817d2e41: vfio_iommu_resv_exclude (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head *iova, struct list_head *resv_regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189ef90)
Location: drivers/vfio/vfio_iommu_type1.c:1896
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_refresh
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff8189ef90-ffffffff8189f151: vfio_iommu_resv_exclude (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head *iova, struct list_head *resv_regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae000)
Location: drivers/vfio/vfio_iommu_type1.c:1923
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_refresh
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff818ae000-ffffffff818ae1c1: vfio_iommu_resv_exclude (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head *iova, struct list_head *resv_regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890eb0)
Location: drivers/vfio/vfio_iommu_type1.c:2143
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff81890eb0-ffffffff81891075: vfio_iommu_resv_exclude (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head *iova, struct list_head *resv_regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff819249c0)
Location: drivers/vfio/vfio_iommu_type1.c:2145
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff819249c0-ffffffff81924b85: vfio_iommu_resv_exclude (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head *iova, struct list_head *resv_regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7a6e0)
Location: drivers/vfio/vfio_iommu_type1.c:2135
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff81a7a6e0-ffffffff81a7a8b2: vfio_iommu_resv_exclude (STB_LOCAL)
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
int vfio_iommu_resv_exclude(struct list_head *iova, struct list_head *resv_regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177cdb0)
Location: drivers/vfio/vfio_iommu_type1.c:1555
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff8177cdb0-ffffffff8177cef1: vfio_iommu_resv_exclude (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head *iova, struct list_head *resv_regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7b80)
Location: drivers/vfio/vfio_iommu_type1.c:1555
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff817c7b80-ffffffff817c7cc1: vfio_iommu_resv_exclude (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_iommu_resv_exclude(struct list_head *iova, struct list_head *resv_regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e1e20)
Location: drivers/vfio/vfio_iommu_type1.c:1555
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff817e1e20-ffffffff817e1f61: vfio_iommu_resv_exclude (STB_LOCAL)
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
