# Function: <code>__raw_readq</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 __raw_readq(const volatile void *addr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/io.c (ffff800010095d68)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - arch/arm64/kernel/io.c:__memcpy_fromio
```
```
In arch/arm64/kernel/acpi_parking_protocol.c (ffff8000100a97ac)
Location: arch/arm64/include/asm/io.h:83
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066e228)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:__gic_update_rdist_properties
  - drivers/irqchip/irq-gic-v3.c:__gic_populate_rdist
  - drivers/irqchip/irq-gic-v3.c:gic_iterate_rdists
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010674ac4)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_restore_enable
  - drivers/irqchip/irq-gic-v3-its.c:its_save_disable
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_irqchip_state
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_send_inv
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_set_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
  - drivers/irqchip/irq-gic-v3-its.c:its_clear_vpend_valid
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e428)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_handler
```
```
In drivers/bus/fsl-mc/mc-sys.c (ffff8000106813a4)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
  - drivers/bus/fsl-mc/mc-sys.c:mc_send_command
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cc2a8)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read64
```
```
In drivers/pci/controller/pci-thunder-pem.c (ffff80001073939c)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_write
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_write
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_read
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_config_read
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffff800010757db8)
Location: arch/arm64/include/asm/io.h:83
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffff8000107584f8)
Location: arch/arm64/include/asm/io.h:83
Inline: True
```
```
In drivers/acpi/osl.c (ffff800010763afc)
Location: arch/arm64/include/asm/io.h:83
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a9a40)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010890f58)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_outq
  - drivers/tty/serial/8250/8250_dw.c:dw8250_serial_inq
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d1994)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_context_fault
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108db17c)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_fault
```
```
In drivers/base/regmap/regmap-mmio.c (ffff80001091c52c)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b57f4c)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/mailbox/pcc.c (ffff800010b7b6bc)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:read_register
```
```
In drivers/perf/arm-ccn.c (ffff800010b93048)
Location: arch/arm64/include/asm/io.h:83
Inline: True
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b96db8)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_read_counter
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b97610)
Location: arch/arm64/include/asm/io.h:83
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_read_counter
```
**Symbols:**

```
ffff80001066fdd8-ffff80001066fde0: __raw_readq (STB_LOCAL)
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
In drivers/video/fbdev/core/cfbfillrect.c (c0000000008bd44c)
Location: arch/powerpc/include/asm/io.h:328
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (c0000000008bdbd4)
Location: arch/powerpc/include/asm/io.h:328
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
In drivers/gpio/gpio-mmio.c (ffffffe0004ad380)
Location: arch/riscv/include/asm/io.h:87
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read64
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059c004)
Location: arch/riscv/include/asm/io.h:87
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
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
<b>Arch</b>
<ul>
</ul>
