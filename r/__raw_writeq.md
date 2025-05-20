# Function: <code>__raw_writeq</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/io.c (ffff800010095cc0)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - arch/arm64/kernel/io.c:__memset_io
  - arch/arm64/kernel/io.c:__memcpy_toio
```
```
In arch/arm64/kernel/smp_spin_table.c (ffff80001009d6f8)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - arch/arm64/kernel/smp_spin_table.c:smp_spin_table_cpu_prepare
```
```
In arch/arm64/kernel/acpi_parking_protocol.c (ffff8000100a96f0)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi_parking_protocol.c:acpi_parking_protocol_cpu_boot
```
```
In lib/iomap_copy.c (ffff80001063d818)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800011473058)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011473fe8)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_irqchip_state
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_irqchip_state
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_inv
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e248)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_unmask_irq
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_mask_irq
```
```
In drivers/bus/fsl-mc/mc-sys.c (ffff800010681368)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cc280)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write64
```
```
In drivers/pci/controller/pci-thunder-pem.c (ffff800010739398)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_write
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_write
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_write
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_read
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_read
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffff800010757dbc)
Location: arch/arm64/include/asm/io.h:43
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffff800010758500)
Location: arch/arm64/include/asm/io.h:43
Inline: True
```
```
In drivers/acpi/osl.c (ffff800010763df8)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107aa9a4)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010890f44)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_outq
  - drivers/tty/serial/8250/8250_dw.c:dw8250_check_lcr
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1a14)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_write_context_bank
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_range_s2
  - drivers/iommu/arm-smmu.c:arm_smmu_tlb_inv_range_s1
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d6c70)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_write_msi_msg
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108da4bc)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
```
```
In drivers/base/regmap/regmap-mmio.c (ffff80001091c410)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffff800010957aa0)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b57eb4)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/mailbox/pcc.c (ffff800010b7b7e8)
Location: arch/arm64/include/asm/io.h:43
Inline: True
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b96d4c)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_write_counter
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b975a4)
Location: arch/arm64/include/asm/io.h:43
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_write_counter
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d5380)
Location: arch/powerpc/include/asm/io.h:332
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_unset_window
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_set_window
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_tce_invalidate_entire
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_tce_invalidate
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_tce_invalidate
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_p7ioc_tce_invalidate
```
```
In lib/iomap_copy.c (c0000000007e74e0)
Location: arch/powerpc/include/asm/io.h:332
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (c0000000008bd45c)
Location: arch/powerpc/include/asm/io.h:332
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (c0000000008bdbe8)
Location: arch/powerpc/include/asm/io.h:332
Inline: True
Inline callers:
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
  - drivers/video/fbdev/core/cfbcopyarea.c:cfb_copyarea
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
In lib/iomap_copy.c (ffffffe00046b3a4)
Location: arch/riscv/include/asm/io.h:52
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad334)
Location: arch/riscv/include/asm/io.h:52
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write64
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059be4e)
Location: arch/riscv/include/asm/io.h:52
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c69c6)
Location: arch/riscv/include/asm/io.h:52
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
</details>
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
