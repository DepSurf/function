# Function: <code>__virtio_cread_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/virtio_blk.c (ffffffff81572001)
Location: include/linux/virtio_config.h:308
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
  - drivers/block/virtio_blk.c:virtblk_probe
```
```
In drivers/net/virtio_net.c (ffffffff815f44ec)
Location: include/linux/virtio_config.h:308
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/virtio_blk.c (ffffffff815c8013)
Location: include/linux/virtio_config.h:321
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_config_changed_work
```
```
In drivers/net/virtio_net.c (ffffffff8165410c)
Location: include/linux/virtio_config.h:321
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
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
In drivers/iommu/virtio-iommu.c (ffffffff8182f595)
Location: include/linux/virtio_config.h:437
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
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
In drivers/iommu/virtio-iommu.c (ffffffff8197079a)
Location: include/linux/virtio_config.h:484
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
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
In drivers/iommu/virtio-iommu.c (ffffffff81adb5ba)
Location: include/linux/virtio_config.h:498
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
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
In drivers/iommu/virtio-iommu.c (ffffffff81b2987a)
Location: include/linux/virtio_config.h:500
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/block/virtio_blk.c (ffffffff81b7f2e2)
Location: include/linux/virtio_config.h:500
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_update_capacity
```
```
In drivers/net/virtio_net.c (ffffffff81c51e02)
Location: include/linux/virtio_config.h:500
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
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
In drivers/iommu/virtio-iommu.c (ffffffff81b8086a)
Location: include/linux/virtio_config.h:504
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/block/virtio_blk.c (ffffffff81bd29f2)
Location: include/linux/virtio_config.h:504
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_update_capacity
```
```
In drivers/net/virtio_net.c (ffffffff81d08081)
Location: include/linux/virtio_config.h:504
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
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
In drivers/iommu/virtio-iommu.c (ffff8000108dc338)
Location: include/linux/virtio_config.h:355
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
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
