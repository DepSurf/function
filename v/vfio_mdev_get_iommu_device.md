# Function: <code>vfio_mdev_get_iommu_device</code>

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
struct device *vfio_mdev_get_iommu_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d2ec0)
Location: drivers/vfio/vfio_iommu_type1.c:1334
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_iommu_device
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff817d2ec0-ffffffff817d2f04: vfio_mdev_get_iommu_device (STB_LOCAL)
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
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189eec5)
Location: drivers/vfio/vfio_iommu_type1.c:1675
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_iommu_device
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
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
In drivers/vfio/vfio_iommu_type1.c (ffffffff818adf49)
Location: drivers/vfio/vfio_iommu_type1.c:1702
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_iommu_device
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *vfio_mdev_get_iommu_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177cf70)
Location: drivers/vfio/vfio_iommu_type1.c:1334
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_iommu_device
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff8177cf70-ffffffff8177cfb4: vfio_mdev_get_iommu_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *vfio_mdev_get_iommu_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c7d40)
Location: drivers/vfio/vfio_iommu_type1.c:1334
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_iommu_device
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff817c7d40-ffffffff817c7d84: vfio_mdev_get_iommu_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *vfio_mdev_get_iommu_device(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e1fe0)
Location: drivers/vfio/vfio_iommu_type1.c:1334
Inline: False
Direct callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_iommu_device
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_detach_domain
  - drivers/vfio/vfio_iommu_type1.c:vfio_mdev_attach_domain
```
**Symbols:**

```
ffffffff817e1fe0-ffffffff817e2024: vfio_mdev_get_iommu_device (STB_LOCAL)
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
