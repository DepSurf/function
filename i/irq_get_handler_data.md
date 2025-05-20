# Function: <code>irq_get_handler_data</code>

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
In drivers/pci/htirq.c (ffffffff81455646)
Location: include/linux/irq.h:630
Inline: True
Inline callers:
  - drivers/pci/htirq.c:write_ht_irq_msg
  - drivers/pci/htirq.c:fetch_ht_irq_msg
```
```
In drivers/xen/events/events_base.c (ffffffff814c78bc)
Location: include/linux/irq.h:630
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
```
```
In drivers/iommu/dmar.c (ffffffff8153528c)
Location: include/linux/irq.h:630
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_write
  - drivers/iommu/dmar.c:dmar_msi_read
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81588625)
Location: include/linux/irq.h:630
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/pci/htirq.c (ffffffff814a236d)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/pci/htirq.c:fetch_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
```
```
In drivers/xen/events/events_base.c (ffffffff8151832c)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff81589bfc)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815dd6a5)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/pci/htirq.c (ffffffff814c3fbd)
Location: include/linux/irq.h:676
Inline: True
Inline callers:
  - drivers/pci/htirq.c:fetch_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
```
```
In drivers/xen/events/events_base.c (ffffffff8154483c)
Location: include/linux/irq.h:676
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff815b72ac)
Location: include/linux/irq.h:676
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160a335)
Location: include/linux/irq.h:676
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/pci/htirq.c (ffffffff814ce25d)
Location: include/linux/irq.h:726
Inline: True
Inline callers:
  - drivers/pci/htirq.c:fetch_ht_irq_msg
  - drivers/pci/htirq.c:write_ht_irq_msg
```
```
In drivers/xen/events/events_base.c (ffffffff8155863c)
Location: include/linux/irq.h:726
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff815cd08e)
Location: include/linux/irq.h:726
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161e448)
Location: include/linux/irq.h:726
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/xen/events/events_base.c (ffffffff815bca7c)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff81633e8e)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81686c88)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/xen/events/events_base.c (ffffffff815f512c)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff8166f015)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c2dc5)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/xen/events/events_base.c (ffffffff8161021c)
Location: include/linux/irq.h:758
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff8168d575)
Location: include/linux/irq.h:758
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e41c5)
Location: include/linux/irq.h:758
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/xen/events/events_base.c (ffffffff81643e8c)
Location: include/linux/irq.h:771
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff816c4f75)
Location: include/linux/irq.h:771
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171d855)
Location: include/linux/irq.h:771
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/xen/events/events_base.c (ffffffff8166643c)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff816e7ea5)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81741b25)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/iommu/intel/dmar.c (ffffffff8179e9e5)
Location: include/linux/irq.h:819
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_read
  - drivers/iommu/intel/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ff645)
Location: include/linux/irq.h:819
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/iommu/intel/dmar.c (ffffffff817ac742)
Location: include/linux/irq.h:832
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_read
  - drivers/iommu/intel/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff818108e5)
Location: include/linux/irq.h:832
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/iommu/intel/dmar.c (ffffffff8178f612)
Location: include/linux/irq.h:834
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_read
  - drivers/iommu/intel/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f5073)
Location: include/linux/irq.h:834
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/iommu/intel/dmar.c (ffffffff81816f32)
Location: include/linux/irq.h:836
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_read
  - drivers/iommu/intel/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e113)
Location: include/linux/irq.h:836
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/iommu/intel/dmar.c (ffffffff81957f62)
Location: include/linux/irq.h:840
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_read
  - drivers/iommu/intel/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c65e3)
Location: include/linux/irq.h:840
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/iommu/intel/dmar.c (ffffffff81abef62)
Location: include/linux/irq.h:842
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_read
  - drivers/iommu/intel/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3d063)
Location: include/linux/irq.h:842
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/iommu/intel/dmar.c (ffffffff81b0b937)
Location: include/linux/irq.h:855
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_read
  - drivers/iommu/intel/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b904d3)
Location: include/linux/irq.h:855
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/iommu/intel/dmar.c (ffffffff81b5fa17)
Location: include/linux/irq.h:837
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_read
  - drivers/iommu/intel/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be4443)
Location: include/linux/irq.h:837
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/xen/events/events_base.c (ffff80001082fdf8)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093d2f0)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl4030-irq.c (c0a25d74)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In arch/powerpc/sysdev/xive/common.c (c0000000000bd450)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_irq_domain_unmap
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e50c8)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl4030-irq.c (ffffffe0005b14b0)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/xen/events/events_base.c (ffffffff8162c16c)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff816ad985)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
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
In drivers/iommu/dmar.c (ffffffff8168b2e5)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
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
In drivers/xen/events/events_base.c (ffffffff8165a27c)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff816dbb65)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81734fe5)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
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
In drivers/xen/events/events_base.c (ffffffff8167484c)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:evtchn_get
  - drivers/xen/events/events_base.c:evtchn_make_refcounted
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:xen_free_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:cpu_from_evtchn
  - drivers/xen/events/events_base.c:evtchn_from_irq
  - drivers/xen/events/events_base.c:xen_irq_info_virq_setup
  - drivers/xen/events/events_base.c:xen_irq_info_ipi_setup
  - drivers/xen/events/events_base.c:xen_irq_info_evtchn_setup
```
```
In drivers/iommu/dmar.c (ffffffff816f6135)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_read
  - drivers/iommu/dmar.c:dmar_msi_write
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81750425)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:handle_twl4030_sih
```
</details>
</li>
</ul>

## Differences
