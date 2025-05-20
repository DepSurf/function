# Function: <code>dev_to_virtio</code>

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
In drivers/virtio/virtio.c (ffffffff814bea14)
Location: include/linux/virtio.h:111
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/linux/virtio.h:111
Inline: True
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
In drivers/virtio/virtio.c (ffffffff8150e724)
Location: include/linux/virtio.h:130
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:status_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81512866)
Location: include/linux/virtio.h:130
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8153a884)
Location: include/linux/virtio.h:130
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:status_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8153ec06)
Location: include/linux/virtio.h:130
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8154e0e4)
Location: include/linux/virtio.h:139
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:status_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81552986)
Location: include/linux/virtio.h:139
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff815b17c4)
Location: include/linux/virtio.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:status_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815b62e6)
Location: include/linux/virtio.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff815e9be5)
Location: include/linux/virtio.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815ee6a5)
Location: include/linux/virtio.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff816040f5)
Location: include/linux/virtio.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81608da5)
Location: include/linux/virtio.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81636b35)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8163cbf5)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81658895)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8165f0d5)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff818f7385)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81709465)
Location: include/linux/virtio.h:122
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170e1a5)
Location: include/linux/virtio.h:122
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819cd4f5)
Location: include/linux/virtio.h:122
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81726415)
Location: include/linux/virtio.h:122
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8172af95)
Location: include/linux/virtio.h:122
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819ccd45)
Location: include/linux/virtio.h:122
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8170a065)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170ed15)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff819b1ef5)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81785a45)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8178b645)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182f539)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81a60655)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff818bc735)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:status_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff818c31b5)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/virtio.h:123
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81bd0b95)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81a0b405)
Location: include/linux/virtio.h:130
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:status_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a13775)
Location: include/linux/virtio.h:130
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/virtio.h:130
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7b785)
Location: include/linux/virtio.h:130
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffff8000108217b8)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffff800010827ef0)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbefc)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_add_device
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffff800010b83740)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (c093eb10)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (c0945de0)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/remoteproc/remoteproc_virtio.c (c0c669b0)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (c0000000008ca548)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (c0000000008d405c)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/remoteproc/remoteproc_virtio.c (c000000000c60c1c)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffe000517cc6)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051e50a)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8161e735)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81624f45)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff818986b5)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81612e25)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff816195c5)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8164c6d5)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81652f15)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81666d65)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_dev_remove
  - drivers/virtio/virtio.c:virtio_dev_probe
  - drivers/virtio/virtio.c:virtio_uevent
  - drivers/virtio/virtio.c:virtio_dev_match
  - drivers/virtio/virtio.c:features_show
  - drivers/virtio/virtio.c:modalias_show
  - drivers/virtio/virtio.c:status_show
  - drivers/virtio/virtio.c:vendor_show
  - drivers/virtio/virtio.c:device_show
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8166d5a5)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_release_dev
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81908e15)
Location: include/linux/virtio.h:123
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_remove_virtio_dev
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
</details>
</li>
</ul>

## Differences
