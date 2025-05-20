# Function: <code>vfio_iommu_find_iommu_group</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a0c1f)
Location: drivers/vfio/vfio_iommu_type1.c:1604
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfio_group *vfio_iommu_find_iommu_group(struct vfio_iommu *iommu, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ac7e0)
Location: drivers/vfio/vfio_iommu_type1.c:1631
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff818ac7e0-ffffffff818ac865: vfio_iommu_find_iommu_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct vfio_group *vfio_iommu_find_iommu_group(struct vfio_iommu *iommu, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188fe60)
Location: drivers/vfio/vfio_iommu_type1.c:1891
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff8188fe60-ffffffff8188fee0: vfio_iommu_find_iommu_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct vfio_iommu_group *vfio_iommu_find_iommu_group(struct vfio_iommu *iommu, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923a40)
Location: drivers/vfio/vfio_iommu_type1.c:1893
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff81923a40-ffffffff81923ac0: vfio_iommu_find_iommu_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct vfio_iommu_group *vfio_iommu_find_iommu_group(struct vfio_iommu *iommu, struct iommu_group *iommu_group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a792c0)
Location: drivers/vfio/vfio_iommu_type1.c:1891
Inline: True
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
**Symbols:**

```
ffffffff81a792c0-ffffffff81a79359: vfio_iommu_find_iommu_group (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct vfio_group *</code> ➡️ <code>struct vfio_iommu_group *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
