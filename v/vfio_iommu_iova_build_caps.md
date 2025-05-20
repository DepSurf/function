# Function: <code>vfio_iommu_iova_build_caps</code>

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
int vfio_iommu_iova_build_caps(struct vfio_iommu *iommu, struct vfio_info_cap *caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d3600)
Location: drivers/vfio/vfio_iommu_type1.c:2168
Inline: False
```
**Symbols:**

```
ffffffff817d3600-ffffffff817d371b: vfio_iommu_iova_build_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_iommu_iova_build_caps(struct vfio_iommu *iommu, struct vfio_info_cap *caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e360)
Location: drivers/vfio/vfio_iommu_type1.c:2538
Inline: False
```
**Symbols:**

```
ffffffff8189e360-ffffffff8189e467: vfio_iommu_iova_build_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_iommu_iova_build_caps(struct vfio_iommu *iommu, struct vfio_info_cap *caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818acf60)
Location: drivers/vfio/vfio_iommu_type1.c:2562
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
```
**Symbols:**

```
ffffffff818acf60-ffffffff818ad067: vfio_iommu_iova_build_caps (STB_LOCAL)
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
In drivers/vfio/vfio_iommu_type1.c (ffffffff81890013)
Location: drivers/vfio/vfio_iommu_type1.c:2779
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
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
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923bfd)
Location: drivers/vfio/vfio_iommu_type1.c:2781
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_iommu_iova_build_caps(struct vfio_iommu *iommu, struct vfio_info_cap *caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7a330)
Location: drivers/vfio/vfio_iommu_type1.c:2773
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_get_info
```
**Symbols:**

```
ffffffff81a7a330-ffffffff81a7a45f: vfio_iommu_iova_build_caps (STB_LOCAL)
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
int vfio_iommu_iova_build_caps(struct vfio_iommu *iommu, struct vfio_info_cap *caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177d6b0)
Location: drivers/vfio/vfio_iommu_type1.c:2168
Inline: False
```
**Symbols:**

```
ffffffff8177d6b0-ffffffff8177d7cb: vfio_iommu_iova_build_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_iommu_iova_build_caps(struct vfio_iommu *iommu, struct vfio_info_cap *caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c8480)
Location: drivers/vfio/vfio_iommu_type1.c:2168
Inline: False
```
**Symbols:**

```
ffffffff817c8480-ffffffff817c859b: vfio_iommu_iova_build_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_iommu_iova_build_caps(struct vfio_iommu *iommu, struct vfio_info_cap *caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e2720)
Location: drivers/vfio/vfio_iommu_type1.c:2168
Inline: False
```
**Symbols:**

```
ffffffff817e2720-ffffffff817e283b: vfio_iommu_iova_build_caps (STB_LOCAL)
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
