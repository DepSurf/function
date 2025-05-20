# Function: <code>set_dma_ops</code>

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
In drivers/acpi/scan.c (ffffffff8158c62d)
Location: include/linux/dma-mapping.h:273
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure
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
In drivers/acpi/scan.c (ffffffff815bd40d)
Location: include/linux/dma-mapping.h:275
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure
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
In drivers/acpi/scan.c (ffffffff815de6cd)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure
```
```
In drivers/iommu/intel-iommu.c (ffffffff816eaa40)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f48f6)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In drivers/acpi/scan.c (ffffffff8168907d)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179f6b0)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819caa2a)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In drivers/acpi/scan.c (ffffffff816a6c0d)
Location: include/linux/dma-map-ops.h:84
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/iommu/intel/iommu.c (ffffffff817ad1ad)
Location: include/linux/dma-map-ops.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9f83)
Location: include/linux/dma-map-ops.h:84
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In drivers/acpi/scan.c (ffffffff8168989d)
Location: include/linux/dma-map-ops.h:84
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/iommu/amd/iommu.c (ffffffff81786568)
Location: include/linux/dma-map-ops.h:84
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff8178fc8d)
Location: include/linux/dma-map-ops.h:84
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aef93)
Location: include/linux/dma-map-ops.h:84
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In drivers/acpi/scan.c (ffffffff816ffd62)
Location: include/linux/dma-map-ops.h:85
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180ceb5)
Location: include/linux/dma-map-ops.h:85
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize
```
```
In drivers/iommu/intel/iommu.c (ffffffff818176b5)
Location: include/linux/dma-map-ops.h:85
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182e495)
Location: include/linux/dma-map-ops.h:85
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_finalize
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d58e)
Location: include/linux/dma-map-ops.h:85
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In drivers/acpi/scan.c (ffffffff8182d8c1)
Location: include/linux/dma-map-ops.h:85
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194d845)
Location: include/linux/dma-map-ops.h:85
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize
```
```
In drivers/iommu/intel/iommu.c (ffffffff81958755)
Location: include/linux/dma-map-ops.h:85
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8196f865)
Location: include/linux/dma-map-ops.h:85
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_finalize
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd6be)
Location: include/linux/dma-map-ops.h:85
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In drivers/acpi/scan.c (ffffffff81960691)
Location: include/linux/dma-map-ops.h:96
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab1d55)
Location: include/linux/dma-map-ops.h:96
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abf845)
Location: include/linux/dma-map-ops.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81ad9f85)
Location: include/linux/dma-map-ops.h:96
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_finalize
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7c101)
Location: include/linux/dma-map-ops.h:96
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In drivers/acpi/scan.c (ffffffff819a6e31)
Location: include/linux/dma-map-ops.h:97
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/iommu/amd/iommu.c (ffffffff81afde05)
Location: include/linux/dma-map-ops.h:97
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0c0a5)
Location: include/linux/dma-map-ops.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b28105)
Location: include/linux/dma-map-ops.h:97
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_finalize
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81dea2c1)
Location: include/linux/dma-map-ops.h:97
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In drivers/acpi/scan.c (ffffffff819ef853)
Location: include/linux/dma-map-ops.h:98
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure_id
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b51575)
Location: include/linux/dma-map-ops.h:98
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_finalize
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b60595)
Location: include/linux/dma-map-ops.h:98
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_finalize
  - drivers/iommu/intel/iommu.c:intel_iommu_release_device
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b7efc5)
Location: include/linux/dma-map-ops.h:98
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_finalize
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81ea052d)
Location: include/linux/dma-map-ops.h:98
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In drivers/acpi/scan.c (ffff80001076b140)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80a50)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In arch/arm/mm/dma-mapping.c (c031e810)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arch_teardown_dma_ops
  - arch/arm/mm/dma-mapping.c:arch_setup_dma_ops
  - arch/arm/mm/dma-mapping.c:arm_iommu_attach_device
```
```
In arch/arm/mach-highbank/highbank.c (c032eff0)
Location: include/linux/dma-mapping.h:268
Inline: True
```
```
In arch/arm/mach-mvebu/coherency.c (c0330adc)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/coherency.c:mvebu_hwcc_notifier
```
```
In drivers/remoteproc/remoteproc_core.c (c0c6406c)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In arch/powerpc/kernel/pci-common.c (c00000000006bee0)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
```
```
In arch/powerpc/platforms/pseries/vio.c (c000000000101824)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5d310)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d0bad)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b0520)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895c26)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
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
In drivers/acpi/scan.c (ffffffff815ba76d)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168de70)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
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
In drivers/acpi/scan.c (ffffffff815d29ad)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure
```
```
In drivers/iommu/intel-iommu.c (ffffffff816de700)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
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
In drivers/acpi/scan.c (ffffffff815ec86d)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dma_configure
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f8e20)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_remove_device
  - drivers/iommu/intel-iommu.c:intel_iommu_add_device
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81906386)
Location: include/linux/dma-mapping.h:268
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
</details>
</li>
</ul>

## Differences
