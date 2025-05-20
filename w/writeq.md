# Function: <code>writeq</code>

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
In arch/x86/kernel/pci-calgary_64.c (ffffffff8106749c)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In lib/iomap_copy.c (ffffffff81402cd9)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff81473d5b)
Location: arch/x86/include/asm/io.h:91
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff81474447)
Location: arch/x86/include/asm/io.h:91
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
```
In drivers/acpi/osl.c (ffffffff8147a21d)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff8151938c)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_interrupt
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
```
```
In drivers/iommu/dmar.c (ffffffff815334ab)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81535e80)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff8153bcf6)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153c903)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8156b329)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gather_write
```
```
In drivers/clocksource/numachip.c (ffffffff816d5537)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip2_set_next_event
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip_timer_init
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81f9f4e4)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap_copy.c (ffffffff8144a989)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff814c2267)
Location: arch/x86/include/asm/io.h:91
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff814c2947)
Location: arch/x86/include/asm/io.h:91
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
```
```
In drivers/acpi/osl.c (ffffffff814c87d4)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff8156cdc9)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/dmar.c (ffffffff81587a3d)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158a58f)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff8159084f)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815914a4)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815bfb50)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff815ef326)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff81fe504a)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff81750730)
Location: arch/x86/include/asm/io.h:91
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff81fdaa46)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap_copy.c (ffffffff81469349)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff814e4257)
Location: arch/x86/include/asm/io.h:91
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff814e4937)
Location: arch/x86/include/asm/io.h:91
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
```
```
In drivers/acpi/osl.c (ffffffff814ea718)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815264ae)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/char/hpet.c (ffffffff81599539)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/dmar.c (ffffffff815b50fd)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815b7bff)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff815be0e0)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bed64)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff815eef90)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff8161c4f6)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff820239df)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff8177c146)
Location: arch/x86/include/asm/io.h:91
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff820bb878)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap_copy.c (ffffffff8146ea49)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - lib/iomap_copy.c:__iowrite64_copy
```
```
In drivers/video/fbdev/core/cfbfillrect.c (ffffffff814f002b)
Location: arch/x86/include/asm/io.h:91
Inline: True
```
```
In drivers/video/fbdev/core/cfbcopyarea.c (ffffffff814f0684)
Location: arch/x86/include/asm/io.h:91
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
```
```
In drivers/acpi/osl.c (ffffffff814f6526)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815392e6)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
```
```
In drivers/char/hpet.c (ffffffff815ad604)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/dmar.c (ffffffff815cafb5)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815cdcba)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff815d372f)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d4974)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816031d0)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff81630509)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff8210671d)
Location: arch/x86/include/asm/io.h:91
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff8179ac96)
Location: arch/x86/include/asm/io.h:91
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff826c225a)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In drivers/acpi/osl.c (ffffffff81536cd6)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff81613fd4)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/dmar.c (ffffffff81631d85)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81634afa)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff8163a3f7)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163b704)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8166b5a0)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff81698d39)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff8270fe76)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff8181107a)
Location: arch/x86/include/asm/io.h:99
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff826ec47b)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In drivers/acpi/osl.c (ffffffff8156c915)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff8164dd8a)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/dmar.c (ffffffff8166d115)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8167043d)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff81675a4b)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81676d00)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816a6f7a)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d5016)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff8273a118)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff8185aeca)
Location: arch/x86/include/asm/io.h:99
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a3063)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In drivers/acpi/osl.c (ffffffff81584545)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff8166bf0a)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a4b9)
Location: arch/x86/include/asm/io.h:99
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
In drivers/iommu/dmar.c (ffffffff8168b526)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168e58d)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff81694da1)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695db0)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c7aba)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f6d16)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff828f40e7)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff8187a32a)
Location: arch/x86/include/asm/io.h:99
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bb397)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap.c (ffffffff81510f12)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff815b5163)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff816a1acd)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1e69)
Location: arch/x86/include/asm/io.h:97
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
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
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
In drivers/iommu/dmar.c (ffffffff816c2f56)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c5bcf)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816cd79a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816ce6f1)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81702d6a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff81732793)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff8290fb16)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff818bf981)
Location: arch/x86/include/asm/io.h:97
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d222)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c1855)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c9aef)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_first
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810987b4)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81098b2b)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca181)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff81531982)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff815d6393)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff816c482d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4d89)
Location: arch/x86/include/asm/io.h:97
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
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
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
In drivers/iommu/dmar.c (ffffffff816e5e46)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816e8bff)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816f15da)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f2531)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817270ba)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff81756643)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff829197f1)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff818f24a1)
Location: arch/x86/include/asm/io.h:97
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8107493c)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff82cebf9f)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:pq_init
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_first
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109df91)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e21f)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109f2b6)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff81595e2c)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff81680093)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff81778eb5)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff8179b367)
Location: arch/x86/include/asm/io.h:97
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
  - drivers/iommu/amd/init.c:iommu_update_intcapxt
  - drivers/iommu/amd/init.c:iommu_update_intcapxt
  - drivers/iommu/amd/init.c:iommu_update_intcapxt
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
In drivers/iommu/intel/dmar.c (ffffffff8179c726)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179fbfc)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a7718)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff817a994b)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aaa81)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817e368a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff81815c22)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff82d2bf0a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff819c7f11)
Location: arch/x86/include/asm/io.h:97
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075294)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099b63)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099dd6)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109adfd)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff815b18bc)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff8169eb6e)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff81c08aaa)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff817a96e8)
Location: arch/x86/include/asm/io.h:97
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
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_activate
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_activate
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_activate
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
In drivers/iommu/intel/dmar.c (ffffffff817aa3f6)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff817ad79c)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b35bc)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5bf8)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b6fe1)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f835d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff81824e12)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff8301a8d2)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff819c7de1)
Location: arch/x86/include/asm/io.h:97
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075d34)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a368)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a5c6)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b539)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff815bc6cc)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff81681820)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff81bfa650)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff8178b331)
Location: arch/x86/include/asm/io.h:97
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
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_activate
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_activate
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_activate
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
In drivers/iommu/intel/dmar.c (ffffffff8178d196)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8179012e)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff817966ec)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff81798d89)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179a2ca)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcaed)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff818081a0)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff83225920)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff819acd21)
Location: arch/x86/include/asm/io.h:97
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810832e9)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa3d8)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_program_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810aa673)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab6e5)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff8162351c)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff816f6910)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff81cfb0c7)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff81812ac7)
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
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
```
```
In drivers/iommu/intel/dmar.c (ffffffff818144f6)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181799e)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e67c)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff818214cb)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8182290a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff818684ed)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff81892946)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff8330fae1)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff81a5b231)
Location: arch/x86/include/asm/io.h:97
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8109317b)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfe48)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_program_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810c00c3)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c1363)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff816f2b4c)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b1975)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write64
```
```
In drivers/acpi/osl.c (ffffffff8182378e)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff81ec3918)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff81953a88)
Location: arch/x86/include/asm/io.h:99
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
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
```
```
In drivers/iommu/intel/dmar.c (ffffffff81955346)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195893d)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195ea4c)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff8196165f)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff819625a9)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0f2d)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff819dcad6)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81b3a23f)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
```
```
In drivers/clocksource/numachip.c (ffffffff834c9904)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff81bcaed5)
Location: arch/x86/include/asm/io.h:99
Inline: True
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a84fb)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810dbd58)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_program_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810dc023)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ddba3)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff817e49ac)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cb7d5)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write64
```
```
In drivers/acpi/osl.c (ffffffff819549ee)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff81a9b3d2)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff81ab9178)
Location: arch/x86/include/asm/io.h:99
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
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
  - drivers/iommu/amd/init.c:amd_iommu_restart_event_logging
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abb946)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81abfa9e)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac64bc)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca0eb)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acb2f9)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b258aa)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b58166)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81ccfc6f)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
```
```
In drivers/clocksource/numachip.c (ffffffff83f0affd)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff81d74695)
Location: arch/x86/include/asm/io.h:99
Inline: True
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab76b)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e7328)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_program_mmr
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810e75f3)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e9252)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff818249ec)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190e845)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write64
```
```
In drivers/acpi/osl.c (ffffffff8199adee)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff81ae6c5e)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff81b055e1)
Location: arch/x86/include/asm/io.h:99
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
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
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
In drivers/iommu/intel/dmar.c (ffffffff81b08226)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b12b6e)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b1309c)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:vcmd_free_pasid
  - drivers/iommu/intel/pasid.c:vcmd_alloc_pasid
```
```
In drivers/iommu/intel/svm.c (ffffffff81b16c63)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b17f69)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1b07e)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_assign_event
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b75a24)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bab6d6)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff837311cd)
Location: arch/x86/include/asm/io.h:99
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff81de2600)
Location: arch/x86/include/asm/io.h:99
Inline: True
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b25d2)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef6b9)
Location: arch/x86/include/asm/io.h:96
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810ef982)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f15a7)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
```
In lib/iomap.c (ffffffff818763fc)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/gpio/gpio-mmio.c (ffffffff819565b5)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write64
```
```
In drivers/acpi/osl.c (ffffffff819e326e)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff81b39fee)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:__hpet_calibrate
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_common
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_ioctl_ieon
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd/init.c (ffffffff81b59631)
Location: arch/x86/include/asm/io.h:96
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
  - drivers/iommu/amd/init.c:intcapxt_mask_irq
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/amd/init.c:iommu_enable_event_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
  - drivers/iommu/amd/init.c:iommu_enable_command_buffer
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5c246)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b679ae)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:ecmd_submit_sync
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel/iommu.c:__iommu_flush_context
  - drivers/iommu/intel/iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c343)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_finish_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
  - drivers/iommu/intel/svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6d8a9)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b70bae)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:iommu_pmu_assign_event
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bffa16)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff8396576d)
Location: arch/x86/include/asm/io.h:96
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff81e98660)
Location: arch/x86/include/asm/io.h:96
Inline: True
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
In lib/iomap.c (c0000000007e6b8c)
Location: arch/powerpc/include/asm/io-defs.h:19
Inline: True
```
```
In drivers/gpio/gpio-mmio.c (c000000000847d18)
Location: arch/powerpc/include/asm/io-defs.h:19
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write64
```
```
In drivers/base/regmap/regmap-mmio.c (c0000000009c0c30)
Location: arch/powerpc/include/asm/io-defs.h:19
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (c000000000a05d3c)
Location: arch/powerpc/include/asm/io-defs.h:19
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828ac82b)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap.c (ffffffff81529f62)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/gpio/gpio-mmio.c (ffffffff81569a65)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write64
```
```
In drivers/acpi/osl.c (ffffffff815ca0f3)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff8168a27d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa869)
Location: arch/x86/include/asm/io.h:97
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
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
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
In drivers/iommu/dmar.c (ffffffff816ab926)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816ae6df)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816b6dca)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b7d21)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816ece9a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170ad33)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff828fe95d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff818937d1)
Location: arch/x86/include/asm/io.h:97
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a4af2)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap.c (ffffffff8151a242)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff815b3173)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/acpi/nfit/core.c (ffffffff815f4a28)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_do_io
```
```
In drivers/char/hpet.c (ffffffff81667c9d)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff81688059)
Location: arch/x86/include/asm/io.h:97
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
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
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
In drivers/iommu/dmar.c (ffffffff81689286)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168c03f)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff81694a0a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81695961)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff816c74da)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff816de7b3)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff828f6493)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff8184bcd1)
Location: arch/x86/include/asm/io.h:97
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bf72a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In lib/iomap.c (ffffffff81525ff2)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff815ca673)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff816b84ed)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8a49)
Location: arch/x86/include/asm/io.h:97
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
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
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
In drivers/iommu/dmar.c (ffffffff816d9b06)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816dc8bf)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816e529a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e61f1)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8171a57a)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff81749b03)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/i2c/busses/i2c-amd-mp2-pci.c (ffffffff81867feb)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_rw
```
```
In drivers/clocksource/numachip.c (ffffffff82913b8c)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff818e72d1)
Location: arch/x86/include/asm/io.h:97
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e8e2)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c2877)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_handle_quirks
  - arch/x86/kernel/pci-calgary_64.c:calioc2_tce_cache_blast
  - arch/x86/kernel/pci-calgary_64.c:calgary_tce_cache_blast
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828cab2c)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_misc_control
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_payload_first
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099c84)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81099ffb)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
  - arch/x86/platform/uv/uv_time.c:uv_setup_intr
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb1be)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
```
In lib/iomap.c (ffffffff8153f972)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - lib/iomap.c:iowrite64be_hi_lo
  - lib/iomap.c:iowrite64be_lo_hi
  - lib/iomap.c:iowrite64_hi_lo
  - lib/iomap.c:iowrite64_lo_hi
```
```
In drivers/acpi/osl.c (ffffffff815e4507)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_write_memory
```
```
In drivers/char/hpet.c (ffffffff816d2abd)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_alloc
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_release
  - drivers/char/hpet.c:hpet_interrupt
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2ff9)
Location: arch/x86/include/asm/io.h:97
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
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
  - drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt
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
In drivers/iommu/dmar.c (ffffffff816f40b6)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:__dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f6eff)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_iotlb
  - drivers/iommu/intel-iommu.c:__iommu_flush_context
  - drivers/iommu/intel-iommu.c:iommu_set_root_entry
```
```
In drivers/iommu/intel-svm.c (ffffffff816ff979)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_finish_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
  - drivers/iommu/intel-svm.c:intel_svm_enable_prq
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff817008f1)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:iommu_set_irq_remapping
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817358da)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write64le
```
```
In drivers/nvdimm/region_devs.c (ffffffff81764f83)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:generic_nvdimm_flush
```
```
In drivers/clocksource/numachip.c (ffffffff8291a853)
Location: arch/x86/include/asm/io.h:97
Inline: True
Inline callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
  - drivers/clocksource/numachip.c:numachip_timer_each
  - drivers/clocksource/numachip.c:numachip2_set_next_event
```
```
In drivers/mailbox/pcc.c (ffffffff81903f51)
Location: arch/x86/include/asm/io.h:97
Inline: True
```
</details>
</li>
</ul>

## Differences
