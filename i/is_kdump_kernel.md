# Function: <code>is_kdump_kernel</code>

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
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/crash_dump.h:54
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/crash_dump.h:54
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/crash_dump.h:54
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/crash_dump.h:54
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/crash_dump.h:54
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
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
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
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/crash_dump.h:58
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
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/crash_dump.h:58
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/crash_dump.h:58
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
In arch/x86/kernel/pci-calgary_64.c (0)
Location: include/linux/crash_dump.h:59
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/crash_dump.h:59
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/crash_dump.h:59
Inline: True
```
```
In drivers/iommu/amd_iommu_init.c (0)
Location: include/linux/crash_dump.h:59
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/crash_dump.h:59
Inline: True
```
```
In drivers/iommu/intel_irq_remapping.c (0)
Location: include/linux/crash_dump.h:59
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/crash_dump.h:59
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff826ebaae)
Location: include/linux/crash_dump.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In fs/proc/vmcore.c (ffffffff8270ecf9)
Location: include/linux/crash_dump.h:60
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff8149269b)
Location: include/linux/crash_dump.h:60
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff827295bd)
Location: include/linux/crash_dump.h:60
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272aa1e)
Location: include/linux/crash_dump.h:60
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677f1e)
Location: include/linux/crash_dump.h:60
Inline: True
```
```
In net/core/dev.c (ffffffff8188f515)
Location: include/linux/crash_dump.h:60
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a26b0)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In fs/proc/vmcore.c (ffffffff828c5e68)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff814ac46e)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828e1830)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e32f6)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696ffe)
Location: include/linux/crash_dump.h:64
Inline: True
```
```
In net/core/dev.c (ffffffff818b3715)
Location: include/linux/crash_dump.h:64
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bacd2)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In fs/proc/vmcore.c (ffffffff828df78c)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff814da67e)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828fc718)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff828fdc49)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf974)
Location: include/linux/crash_dump.h:64
Inline: True
```
```
In net/core/dev.c (ffffffff818ff5b5)
Location: include/linux/crash_dump.h:64
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd895)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c1194)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In fs/proc/vmcore.c (ffffffff828e8163)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff814f3a3e)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff829056ed)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff82906cb1)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f37b4)
Location: include/linux/crash_dump.h:64
Inline: True
```
```
In net/core/dev.c (ffffffff81929ab5)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In fs/proc/vmcore.c (ffffffff82d02b44)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff815540cc)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_update_queue_map
```
```
In drivers/iommu/dma-iommu.c (ffffffff81791b55)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_deferred_attach
```
```
In drivers/iommu/amd/init.c (ffffffff82d1c467)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1db6f)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817aba3f)
Location: include/linux/crash_dump.h:65
Inline: True
```
```
In net/core/dev.c (ffffffff819fdaf5)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In fs/proc/vmcore.c (ffffffff82fefe47)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff8157078c)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_update_queue_map
```
```
In drivers/iommu/amd/init.c (ffffffff8300a24b)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300b886)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7e1f)
Location: include/linux/crash_dump.h:65
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817bdcd5)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_deferred_attach
```
```
In net/core/dev.c (ffffffff819fd6c5)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In fs/proc/vmcore.c (ffffffff831fa64b)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff81578651)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_update_queue_map
```
```
In drivers/iommu/amd/init.c (ffffffff83214d81)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/iommu.c (ffffffff83216232)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179af93)
Location: include/linux/crash_dump.h:65
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a1365)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init
```
```
In net/core/dev.c (ffffffff819e3f35)
Location: include/linux/crash_dump.h:65
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In fs/proc/vmcore.c (ffffffff832e1588)
Location: include/linux/crash_dump.h:66
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff815dd737)
Location: include/linux/crash_dump.h:66
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd/init.c (ffffffff832fe50f)
Location: include/linux/crash_dump.h:66
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/iommu.c (ffffffff832ffa88)
Location: include/linux/crash_dump.h:66
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823ac3)
Location: include/linux/crash_dump.h:66
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81829f45)
Location: include/linux/crash_dump.h:66
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init
```
```
In net/core/dev.c (ffffffff81a94845)
Location: include/linux/crash_dump.h:66
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In fs/proc/vmcore.c (ffffffff834976a2)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff8168b4a5)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd/init.c (ffffffff834b7146)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:init_iommu_one
  - drivers/iommu/amd/init.c:copy_device_table
```
```
In drivers/iommu/intel/iommu.c (ffffffff834b8827)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962f35)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196a495)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init
```
```
In net/core/dev.c (ffffffff81c0f9d5)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In fs/proc/vmcore.c (ffffffff83eccbd8)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff817494c4)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd/init.c (ffffffff83ef3711)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:__copy_device_table
```
```
In drivers/iommu/intel/iommu.c (ffffffff83ef553a)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acc000)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad44d5)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init
```
```
In net/core/dev.c (ffffffff81dc21d3)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In fs/proc/vmcore.c (ffffffff836f1c58)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff81785c03)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd/init.c (ffffffff837192cd)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:__copy_device_table
```
```
In drivers/iommu/intel/iommu.c (ffffffff8371b0bb)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18b86)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b22ca5)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init
```
```
In net/core/dev.c (ffffffff81e31733)
Location: include/linux/crash_dump.h:63
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In mm/mm_init.c (ffffffff8391434d)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In block/blk-mq.c (ffffffff817c8283)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd/init.c (ffffffff8394cdcd)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_amd_iommu_init
  - drivers/iommu/amd/init.c:init_iommu_one_late
  - drivers/iommu/amd/init.c:__copy_device_table
```
```
In drivers/iommu/intel/iommu.c (ffffffff8394eb9b)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e4f5)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b798e5)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_init
```
```
In net/core/dev.c (ffffffff81eefeb3)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/arm64/kernel/cpufeature.c (ffff80001009a4cc)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:has_useable_cnp
```
```
In fs/proc/vmcore.c (ffff800011461d48)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffff8000105f329c)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010670720)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:gic_check_reserved_range
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d71b0)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_reset
```
```
In net/core/dev.c (ffff800010bc6128)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In fs/proc/vmcore.c (c15398f0)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (c079f3ac)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/irqchip/irq-gic-v3-its.c (c0818cd4)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:gic_check_reserved_range
```
```
In net/core/dev.c (c0ce17b4)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/powerpc/kernel/iommu.c (c0000000000529f8)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_init_table
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c00000000136092c)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_init_ioda_phb
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfffc)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:opal_imc_counters_probe
```
```
In arch/powerpc/platforms/pseries/iommu.c (c0000000000ef7d0)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/iommu.c:iommu_table_setparms
```
```
In fs/proc/vmcore.c (c00000000138d9bc)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (c00000000078aa60)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In net/core/dev.c (c000000000ca0cf0)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In block/blk-mq.c (0)
Location: include/linux/crash_dump.h:97
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/crash_dump.h:97
Inline: True
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828ac16a)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In fs/proc/vmcore.c (ffffffff828d1017)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff814ec01e)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828eced4)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff828ee48e)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8fa4)
Location: include/linux/crash_dump.h:64
Inline: True
```
```
In net/core/dev.c (ffffffff818c9ab5)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828a4431)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In fs/proc/vmcore.c (ffffffff828c9733)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff814dc56e)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff828e4361)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e5925)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696be4)
Location: include/linux/crash_dump.h:64
Inline: True
```
```
In net/core/dev.c (ffffffff818839f5)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/kernel/pci-calgary_64.c (ffffffff828bf069)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In fs/proc/vmcore.c (ffffffff828e3d97)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff814e80ae)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff82900a10)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff82901fd4)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e7474)
Location: include/linux/crash_dump.h:64
Inline: True
```
```
In net/core/dev.c (ffffffff8191aab5)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be8c2)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/pci-calgary_64.c (ffffffff828c21b6)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:detect_calgary
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
  - arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init
```
```
In fs/proc/vmcore.c (ffffffff828e91ad)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - fs/proc/vmcore.c:vmcore_init
```
```
In block/blk-mq.c (ffffffff8150104e)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
```
In drivers/iommu/amd_iommu_init.c (ffffffff8290674f)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:init_iommu_all
```
```
In drivers/iommu/intel-iommu.c (ffffffff82907d13)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701b74)
Location: include/linux/crash_dump.h:64
Inline: True
```
```
In net/core/dev.c (ffffffff8193bcc5)
Location: include/linux/crash_dump.h:64
Inline: True
Inline callers:
  - net/core/dev.c:netif_get_num_default_rss_queues
```
</details>
</li>
</ul>

## Differences
