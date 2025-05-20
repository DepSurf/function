# Function: <code>dev_iommu_fwspec_get</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: include/linux/iommu.h:401
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: include/linux/iommu.h:533
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: include/linux/iommu.h:580
Inline: True
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
In drivers/iommu/iommu.c (ffffffff8178d995)
Location: include/linux/iommu.h:620
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/iommu.h:620
Inline: True
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
In drivers/iommu/iommu.c (ffffffff817b9705)
Location: include/linux/iommu.h:603
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/iommu.h:603
Inline: True
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
In drivers/iommu/iommu.c (ffffffff8179c915)
Location: include/linux/iommu.h:564
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/iommu/iommu.c:iommu_release_device
  - drivers/iommu/iommu.c:__iommu_probe_device
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/iommu.h:564
Inline: True
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
In drivers/acpi/scan.c (ffffffff816ffd75)
Location: include/linux/iommu.h:641
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81825625)
Location: include/linux/iommu.h:641
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/iommu/iommu.c:iommu_fwspec_free
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/iommu.h:641
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182e4c5)
Location: include/linux/iommu.h:641
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
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
In drivers/acpi/scan.c (ffffffff8182d8e0)
Location: include/linux/iommu.h:633
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/iommu/iommu.c (ffffffff81965495)
Location: include/linux/iommu.h:633
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/iommu/iommu.c:iommu_fwspec_init
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/iommu.h:633
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8196f115)
Location: include/linux/iommu.h:633
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
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
In drivers/acpi/scan.c (ffffffff819606b0)
Location: include/linux/iommu.h:676
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/iommu/iommu.c (ffffffff81acec75)
Location: include/linux/iommu.h:676
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/iommu/iommu.c:iommu_fwspec_init
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/iommu.h:676
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adb325)
Location: include/linux/iommu.h:676
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
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
In drivers/acpi/scan.c (ffffffff819a6e50)
Location: include/linux/iommu.h:679
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/iommu/iommu.c (ffffffff81b1d5e5)
Location: include/linux/iommu.h:679
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/iommu/iommu.c:iommu_fwspec_init
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/iommu.h:679
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b28660)
Location: include/linux/iommu.h:679
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
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
In drivers/acpi/scan.c (ffffffff819ef87d)
Location: include/linux/iommu.h:911
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/iommu/iommu.c (ffffffff81b73c85)
Location: include/linux/iommu.h:911
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/iommu/iommu.c:iommu_fwspec_free
  - drivers/iommu/iommu.c:iommu_fwspec_init
  - drivers/iommu/iommu.c:__iommu_probe_device
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/iommu.h:911
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b7f720)
Location: include/linux/iommu.h:911
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_release_device
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
  - drivers/iommu/virtio-iommu.c:viommu_probe_endpoint
```
</details>
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
In drivers/acpi/arm64/iort.c (0)
Location: include/linux/iommu.h:580
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/iommu.h:580
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/iommu.h:580
Inline: True
```
```
In drivers/iommu/of_iommu.c (0)
Location: include/linux/iommu.h:580
Inline: True
```
```
In drivers/iommu/arm-smmu.c (0)
Location: include/linux/iommu.h:580
Inline: True
```
```
In drivers/iommu/arm-smmu-v3.c (0)
Location: include/linux/iommu.h:580
Inline: True
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: include/linux/iommu.h:580
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/linux/iommu.h:580
Inline: True
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
In drivers/iommu/iommu.c (c09bc15c)
Location: include/linux/iommu.h:580
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/iommu/iommu.c:iommu_fwspec_free
```
```
In drivers/iommu/of_iommu.c (c09c15bc)
Location: include/linux/iommu.h:580
Inline: True
Inline callers:
  - drivers/iommu/of_iommu.c:of_iommu_configure
  - drivers/iommu/of_iommu.c:of_iommu_configure
```
```
In drivers/iommu/ipmmu-vmsa.c (c09c17f4)
Location: include/linux/iommu.h:580
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_find_group
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_remove_device
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_add_device
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_of_xlate
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_detach_device
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_attach_device
```
```
In drivers/iommu/tegra-smmu.c (c09c7af8)
Location: include/linux/iommu.h:580
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_device_group
```
```
In drivers/iommu/qcom_iommu.c (c09cb4e0)
Location: include/linux/iommu.h:580
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_of_xlate
  - drivers/iommu/qcom_iommu.c:qcom_iommu_remove_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_add_device
  - drivers/iommu/qcom_iommu.c:qcom_iommu_detach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
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
In drivers/iommu/iommu.c (c00000000096ad28)
Location: include/linux/iommu.h:580
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_add_ids
  - drivers/iommu/iommu.c:iommu_fwspec_free
```
```
In drivers/iommu/of_iommu.c (c00000000097080c)
Location: include/linux/iommu.h:580
Inline: True
Inline callers:
  - drivers/iommu/of_iommu.c:of_iommu_configure
  - drivers/iommu/of_iommu.c:of_iommu_configure
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: include/linux/iommu.h:580
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: include/linux/iommu.h:580
Inline: True
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
In drivers/iommu/iommu.c (0)
Location: include/linux/iommu.h:580
Inline: True
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
In drivers/iommu/iommu.c (0)
Location: include/linux/iommu.h:580
Inline: True
```
</details>
</li>
</ul>

## Differences
