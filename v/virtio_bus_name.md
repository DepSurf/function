# Function: <code>virtio_bus_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f15b0)
Location: include/linux/virtio_config.h:183
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff81650af0)
Location: include/linux/virtio_config.h:196
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff8182f75d)
Location: include/linux/virtio_config.h:238
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
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
In drivers/iommu/virtio-iommu.c (ffffffff81970b9c)
Location: include/linux/virtio_config.h:285
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81adb9bf)
Location: include/linux/virtio_config.h:299
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b29c7f)
Location: include/linux/virtio_config.h:301
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/net/virtio_net.c (ffffffff81c4c67b)
Location: include/linux/virtio_config.h:301
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffffffff81b80c72)
Location: include/linux/virtio_config.h:305
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/net/virtio_net.c (ffffffff81d01d2b)
Location: include/linux/virtio_config.h:305
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_get_drvinfo
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/virtio-iommu.c (ffff8000108dc0e0)
Location: include/linux/virtio_config.h:228
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
</details>
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
