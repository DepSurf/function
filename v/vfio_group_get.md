# Function: <code>vfio_group_get</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817d1d90)
Location: drivers/vfio/vfio.c:456
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
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
In drivers/vfio/vfio.c (ffffffff8189ceb4)
Location: drivers/vfio/vfio.c:457
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_name
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
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
In drivers/vfio/vfio.c (ffffffff818abae4)
Location: drivers/vfio/vfio.c:457
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_device_get_from_name
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
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
In drivers/vfio/vfio.c (ffffffff8188ea64)
Location: drivers/vfio/vfio.c:447
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
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
In drivers/vfio/vfio.c (ffffffff819220b4)
Location: drivers/vfio/vfio.c:520
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
  - drivers/vfio/vfio.c:vfio_create_group
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
In drivers/vfio/vfio.c (ffffffff81a77d0e)
Location: drivers/vfio/vfio.c:442
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:__vfio_group_get_from_iommu
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000aaedfc)
Location: drivers/vfio/vfio.c:456
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
```
</details>
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff8177be40)
Location: drivers/vfio/vfio.c:456
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817c6c10)
Location: drivers/vfio/vfio.c:456
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (ffffffff817e0eb0)
Location: drivers/vfio/vfio.c:456
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_external_user
  - drivers/vfio/vfio.c:vfio_group_fops_open
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
  - drivers/vfio/vfio.c:vfio_group_get_device
  - drivers/vfio/vfio.c:vfio_group_get_from_iommu
```
</details>
</li>
</ul>

## Differences
