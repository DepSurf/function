# Function: <code>vfio_group_nb_add_dev</code>

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
In drivers/vfio/vfio.c (ffffffff817d2005)
Location: drivers/vfio/vfio.c:689
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
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
In drivers/vfio/vfio.c (ffffffff8189c630)
Location: drivers/vfio/vfio.c:692
Inline: True
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
ffffffff8189c630-ffffffff8189c6b5: vfio_group_nb_add_dev.isra.0 (STB_LOCAL)
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
In drivers/vfio/vfio.c (ffffffff818ab240)
Location: drivers/vfio/vfio.c:693
Inline: True
Direct callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
**Symbols:**

```
ffffffff818ab240-ffffffff818ab2c5: vfio_group_nb_add_dev.isra.0 (STB_LOCAL)
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
In drivers/vfio/vfio.c (ffffffff8188f161)
Location: drivers/vfio/vfio.c:632
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
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
In drivers/vfio/vfio.c (ffffffff81922731)
Location: drivers/vfio/vfio.c:705
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
</details>
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/vfio.c (c000000000ab0b60)
Location: drivers/vfio/vfio.c:689
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
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
In drivers/vfio/vfio.c (ffffffff8177c0b5)
Location: drivers/vfio/vfio.c:689
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
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
In drivers/vfio/vfio.c (ffffffff817c6e85)
Location: drivers/vfio/vfio.c:689
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
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
In drivers/vfio/vfio.c (ffffffff817e1125)
Location: drivers/vfio/vfio.c:689
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
</details>
</li>
</ul>

## Differences
