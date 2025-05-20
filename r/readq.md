# Function: <code>readq</code>

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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81067466)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff81473d4c)
Location: arch/x86/include/asm/io.h:90
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff81474438)
Location: arch/x86/include/asm/io.h:90
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
```
```
In drivers/acpi/osl.c (ffffffff8147a167)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff81519358)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/iommu/dmar.c (ffffffff81533087)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81535ecb)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel-svm.c (ffffffff8153bb29)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f4ea2)
Location: arch/x86/include/asm/io.h:90
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8156b205)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read
```
```
In drivers/clocksource/numachip.c (ffffffff816d54d6)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9f17a)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff814c225b)
Location: arch/x86/include/asm/io.h:90
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff814c2938)
Location: arch/x86/include/asm/io.h:90
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
```
```
In drivers/acpi/osl.c (ffffffff814c871e)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff8156cc46)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/dmar.c (ffffffff81587edb)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81fd7d64)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff81590669)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592955)
Location: arch/x86/include/asm/io.h:90
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815bfbce)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff81739705)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff817506f3)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fda6dc)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff814e424b)
Location: arch/x86/include/asm/io.h:90
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff814e4928)
Location: arch/x86/include/asm/io.h:90
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
```
```
In drivers/acpi/osl.c (ffffffff814ea662)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525e10)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/char/hpet.c (ffffffff815993b6)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/dmar.c (ffffffff815b559b)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff820159c4)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff815bdef9)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c0212)
Location: arch/x86/include/asm/io.h:90
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815ef00e)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff8176c935)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff8177c0d6)
Location: arch/x86/include/asm/io.h:90
Inline: True
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff820bb4c2)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff814f001f)
Location: arch/x86/include/asm/io.h:90
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff814f0675)
Location: arch/x86/include/asm/io.h:90
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
```
In drivers/acpi/osl.c (ffffffff814f6434)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8153896d)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
```
```
In drivers/char/hpet.c (ffffffff815ad3b1)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/dmar.c (ffffffff815cb418)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f767a)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff815d35d9)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5d41)
Location: arch/x86/include/asm/io.h:90
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8160324e)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff8178acb5)
Location: arch/x86/include/asm/io.h:90
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff8179ac26)
Location: arch/x86/include/asm/io.h:90
Inline: True
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c1ea4)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In drivers/acpi/osl.c (ffffffff81536be4)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff81613d81)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/dmar.c (ffffffff816321e8)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff82700d5b)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff8163a2d9)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163caf1)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8166b61e)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff81801325)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff81810ffa)
Location: arch/x86/include/asm/io.h:97
Inline: True
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff826ec425)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In drivers/acpi/osl.c (ffffffff8156c839)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff8164db37)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/dmar.c (ffffffff8166d59b)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272aa78)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff8167591a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677f33)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816a6ffb)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff8184af32)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff8185ae4a)
Location: arch/x86/include/asm/io.h:97
Inline: True
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a300d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In drivers/acpi/osl.c (ffffffff81584469)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff8166bcb7)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828e181d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
```
```
In drivers/iommu/dmar.c (ffffffff8168b9ab)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e3350)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff81694bfa)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81697013)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c7b3b)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff81877e22)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff8187a2aa)
Location: arch/x86/include/asm/io.h:97
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff8101718c)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bb03d)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap.c (ffffffff81510ea5)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff815b5089)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff816a1852)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1e5e)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
```
```
In drivers/iommu/dmar.c (ffffffff816c3371)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816cbf42)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff816cd5a9)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf98b)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81702deb)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff818bc6a2)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff818bf917)
Location: arch/x86/include/asm/io.h:95
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81017b3c)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd6a8)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c14ff)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c87b3)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81098a35)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca10a)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff81531915)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff815d62b9)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff816c45da)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4d7e)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
```
```
In drivers/iommu/dmar.c (ffffffff816e62ca)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ef804)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff816f13e9)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f37cb)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8172713b)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff818ef172)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff818f2437)
Location: arch/x86/include/asm/io.h:95
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
In arch/x86/events/intel/uncore.c (ffffffff810196ec)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1bb5)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109ce86)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e152)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109eefa)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff81595b21)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff8167ffb7)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff81778c87)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff8179b35c)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd/init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179cdec)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff817a71ae)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a7733)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff817a9699)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aaf62)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817e370b)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff819c2d52)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff819c7ea7)
Location: arch/x86/include/asm/io.h:95
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
In arch/x86/events/intel/uncore.c (ffffffff81019d60)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fcc6a6)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099cee)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109aa7b)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff815b15b1)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff8169ea75)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff81793757)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff817a96dc)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_setup_intcapxt
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd/init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aaabb)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81c0c914)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b35d3)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff817b585a)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b73c2)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f845b)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff819c3172)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff819c7d77)
Location: arch/x86/include/asm/io.h:95
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
In arch/x86/events/intel/uncore.c (ffffffff8101b0e0)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d6f51)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a4de)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b1cd)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff815bc3c1)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff81681727)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff81776457)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff8178b327)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_flags
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd/init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
  - drivers/iommu/amd/init.c:iommu_disable
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d4a6)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_check_fault
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81bfe096)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel/pasid.c (ffffffff81796703)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff81798b6c)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179afa9)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcbeb)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff819a75b2)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff819accb7)
Location: arch/x86/include/asm/io.h:95
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
In arch/x86/events/intel/uncore.c (ffffffff8101da22)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832b9c6f)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810aa55e)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab8b9)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff81623211)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff816f6817)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff817fc1e7)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff81812abc)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
```
```
In drivers/iommu/intel/dmar.c (ffffffff81814ccb)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_check_fault
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81cffdfc)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e693)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff818212b7)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823ad9)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff818685eb)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff81a54ab2)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff81a5b1c7)
Location: arch/x86/include/asm/io.h:95
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff8102043d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346b89e)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810bffe8)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c0f73)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff816f32b8)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b1995)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read64
```
```
In drivers/acpi/osl.c (ffffffff81823659)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff8193ad4c)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_timer_set_irq
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff81953a7d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
```
```
In drivers/iommu/intel/dmar.c (ffffffff81955fa5)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_check_fault
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ec84fb)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195ea63)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff81961417)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962f4c)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b102b)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff81bc40b2)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff81bcb23f)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
In arch/x86/events/intel/uncore.c (ffffffff81024d3d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93015)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810dbf38)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dd553)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff817e51e8)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cb805)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read64
```
```
In drivers/acpi/osl.c (ffffffff819548a9)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff81a9b1d4)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff81ab916d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abcbae)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_check_fault
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac398c)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac64f5)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff81ac9ed7)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbbc2)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/clocksource/numachip.c (ffffffff81d69782)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff81d74a3f)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
In arch/x86/events/intel/uncore.c (ffffffff81024c3d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b7041)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810e7508)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e8b33)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff81825228)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190e875)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read64
```
```
In drivers/acpi/osl.c (ffffffff8199acb9)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff81ae6a63)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff81b055d6)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:enable_iommus_v2
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:amd_iommu_restart_ga_log
  - drivers/iommu/amd/init.c:amd_iommu_restart_ga_log
  - drivers/iommu/amd/init.c:amd_iommu_restart_ga_log
  - drivers/iommu/amd/init.c:amd_iommu_restart_ga_log
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0948d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_check_fault
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b12b99)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b130b3)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff81b16a57)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18742)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1b8fa)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
  - drivers/iommu/intel/perfmon.c:iommu_pmu_start
  - drivers/iommu/intel/perfmon.c:iommu_pmu_event_update
```
```
In drivers/clocksource/numachip.c (ffffffff81dd4c72)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff81de29d0)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
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
In arch/x86/events/intel/uncore.c (ffffffff8102ad9d)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7951)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_mn
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
  - arch/x86/kernel/apic/x2apic_uv_x.c:get_lowmem_redirect
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810ef898)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f0873)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff81876c38)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/gpio/gpio-mmio.c (ffffffff819565e5)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read64
```
```
In drivers/acpi/osl.c (ffffffff819e3139)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff81b39df3)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff81b59626)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:enable_iommus_vapic
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:iommu_init_pci
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5d4ad)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_fault
  - drivers/iommu/intel/dmar.c:qi_check_fault
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:map_iommu
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/intel/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b679d9)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:copy_translation_tables
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c137)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_drain_pasid_prq
  - drivers/iommu/intel/svm.c:intel_drain_pasid_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e082)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_load_old_irte
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b71459)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
  - drivers/iommu/intel/perfmon.c:iommu_pmu_start
  - drivers/iommu/intel/perfmon.c:iommu_pmu_event_update
```
```
In drivers/clocksource/numachip.c (ffffffff81e8cdc2)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff81e9893c)
Location: arch/x86/include/asm/io.h:94
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_send_data
```
</details>
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
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e6580)
Location: arch/powerpc/include/asm/io-defs.h:17
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (c000000000848e98)
Location: arch/powerpc/include/asm/io-defs.h:17
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read64
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0ec0)
Location: arch/powerpc/include/asm/io-defs.h:17
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
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
In arch/x86/events/intel/uncore.c (ffffffff81017b3c)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828ac4d5)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap.c (ffffffff81529ef5)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/gpio/gpio-mmio.c (ffffffff81569a75)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read64
```
```
In drivers/acpi/osl.c (ffffffff815ca019)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff8168a02a)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa85e)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
```
```
In drivers/iommu/dmar.c (ffffffff816abdaa)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b4ff4)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff816b6bd9)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8fbb)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816ecf1b)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff81890542)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff81893767)
Location: arch/x86/include/asm/io.h:95
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81016f8c)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a479c)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap.c (ffffffff8151a1d5)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff815b3099)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/acpi/nfit/core.c (ffffffff815f4a44)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io
```
```
In drivers/char/hpet.c (ffffffff81667a4a)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8168804e)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
```
```
In drivers/iommu/dmar.c (ffffffff8168970a)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff81692c34)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff81694819)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696bfb)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c755b)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff81849802)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff8184bc67)
Location: arch/x86/include/asm/io.h:95
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81017afc)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bf3d4)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap.c (ffffffff81525f85)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff815ca599)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff816b829a)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8a3e)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
```
```
In drivers/iommu/dmar.c (ffffffff816d9f8a)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e34c4)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff816e50a9)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e748b)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8171a5fb)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff818e3fa2)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff818e7267)
Location: arch/x86/include/asm/io.h:95
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff81017d3c)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_mmio_read_counter
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be6d5)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c2521)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c97f0)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:uv_flush_tlb_others
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:read_status
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv2_3_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:uv1_wait_completion
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099f05)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_read_rtc
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb147)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff8153f905)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - lib/iomap.c:ioread64be_hi_lo
  - lib/iomap.c:ioread64be_lo_hi
  - lib/iomap.c:ioread64_hi_lo
  - lib/iomap.c:ioread64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff815e440a)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_read_memory
```
```
In drivers/char/hpet.c (ffffffff816d286a)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_open
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2fee)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:enable_iommus_v2
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:amd_iommu_reset_cmd_buffer
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
  - drivers/iommu/amd_iommu_init.c:iommu_disable
```
```
In drivers/iommu/dmar.c (ffffffff816f453a)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_fault
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:alloc_iommu
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
  - drivers/iommu/dmar.c:dmar_validate_one_drhd
```
```
In drivers/iommu/intel-iommu.c (ffffffff816fdb54)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
```
```
In drivers/iommu/intel-svm.c (ffffffff816ff769)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701b8b)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8173595b)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read64le
```
```
In drivers/clocksource/numachip.c (ffffffff81900c02)
Location: arch/x86/include/asm/io.h:95
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_timer_read
```
```
In drivers/mailbox/pcc.c (ffffffff81903ee7)
Location: arch/x86/include/asm/io.h:95
Inline: True
```
</details>
</li>
</ul>

## Differences
