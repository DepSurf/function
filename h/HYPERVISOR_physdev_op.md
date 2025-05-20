# Function: <code>HYPERVISOR_physdev_op</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101be71)
Location: arch/x86/include/asm/xen/hypercall.h:388
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_set_iopl_mask
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
```
In arch/x86/xen/apic.c (ffffffff81025baf)
Location: arch/x86/include/asm/xen/hypercall.h:388
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff814c78d7)
Location: arch/x86/include/asm/xen/hypercall.h:388
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_init_IRQ
```
```
In drivers/xen/pci.c (ffffffff814d1b96)
Location: arch/x86/include/asm/xen/hypercall.h:388
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff814d1d60)
Location: arch/x86/include/asm/xen/hypercall.h:388
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff816f760d)
Location: arch/x86/include/asm/xen/hypercall.h:388
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/enlighten.c (ffffffff81f887e3)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_set_iopl_mask
```
```
In arch/x86/xen/apic.c (ffffffff81024f9f)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81fd104b)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff8152287a)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff81522a80)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff8175c2ad)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/enlighten.c (ffffffff81fc3bd1)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_set_iopl_mask
```
```
In arch/x86/xen/apic.c (ffffffff810256bf)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff8200e9c3)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff8154ed5a)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff8154ef60)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff8178881d)
Location: arch/x86/include/asm/xen/hypercall.h:389
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff8101c02f)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a5e7a)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask
```
```
In drivers/xen/events/events_base.c (ffffffff820f0473)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff81563048)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff815634c0)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff817a792e)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff8101ccaf)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826ac547)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask
```
```
In drivers/xen/events/events_base.c (ffffffff826f9c7d)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff815c7350)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
```
```
In drivers/xen/dbgp.c (ffffffff815c77b0)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff8181ec3e)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff8101d6cc)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d5698)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask
```
```
In drivers/xen/events/events_base.c (ffffffff82724009)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff8272461b)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_mcfg_late
```
```
In drivers/xen/dbgp.c (ffffffff81600027)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff81868d73)
Location: arch/x86/include/asm/xen/hypercall.h:394
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff8101cf5c)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b71c)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask
```
```
In drivers/xen/events/events_base.c (ffffffff828dc1e2)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff828dc7f4)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_mcfg_late
```
```
In drivers/xen/dbgp.c (ffffffff8161b0f7)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff81888df3)
Location: arch/x86/include/asm/xen/hypercall.h:361
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff8101ea7c)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2b66)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask
```
```
In drivers/xen/events/events_base.c (ffffffff828f6adb)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
```
```
In drivers/xen/pci.c (ffffffff828f70e4)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_mcfg_late
```
```
In drivers/xen/dbgp.c (ffffffff8164ede4)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff818d36c3)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff8101f41c)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a5c19)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask
```
```
In drivers/xen/events/events_base.c (ffffffff828ffb32)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
```
```
In drivers/xen/pci.c (ffffffff81670f82)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81671394)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff8190612a)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff810219dc)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccbf04)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_update_io_bitmap
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In drivers/xen/events/events_base.c (ffffffff82d16edb)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:restore_pirqs
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff8172165e)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81721a94)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In arch/x86/pci/xen.c (ffffffff81bb6023)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff810220bc)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7d38)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_update_io_bitmap
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In drivers/xen/events/events_base.c (ffffffff83004acb)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:restore_pirqs
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff8173e331)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff8173e754)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In arch/x86/pci/xen.c (ffffffff81bcb1d3)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff8102444c)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c2473)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_update_io_bitmap
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In drivers/xen/events/events_base.c (ffffffff8320f580)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff81721dd5)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81722275)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In arch/x86/pci/xen.c (ffffffff81bbeb0c)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff8102882c)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a2eb9)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_update_io_bitmap
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In drivers/xen/events/events_base.c (ffffffff832f8527)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff817a0c13)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff817a10c5)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In arch/x86/pci/xen.c (ffffffff81c8ea45)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_restore_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff8102cfec)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff834520ed)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_update_io_bitmap
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In drivers/xen/events/events_base.c (ffffffff834b0d65)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff818dae3a)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff818daf60)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In arch/x86/pci/xen.c (ffffffff81e3e40a)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
  - arch/x86/pci/xen.c:xen_register_pirq
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
In arch/x86/xen/apic.c (ffffffff8103431c)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6f02a)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_update_io_bitmap
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In drivers/xen/events/events_base.c (ffffffff83eeab2b)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff81a2de1d)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81a2df60)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In arch/x86/pci/xen.c (ffffffff82017b8a)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
  - arch/x86/pci/xen.c:xen_register_pirq
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
In arch/x86/xen/apic.c (ffffffff810342ac)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8368ff60)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_update_io_bitmap
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In drivers/xen/events/events_base.c (ffffffff8371051b)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff81a775c1)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81a77710)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In arch/x86/pci/xen.c (ffffffff82097f7a)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
  - arch/x86/pci/xen.c:xen_register_pirq
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
In arch/x86/xen/apic.c (ffffffff8103a4ac)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bfab0)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_update_io_bitmap
  - arch/x86/xen/enlighten_pv.c:xen_invalidate_io_bitmap
```
```
In drivers/xen/events/events_base.c (ffffffff83943e9b)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:do_eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
```
In drivers/xen/pci.c (ffffffff81ac97d1)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_pci_notifier
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81ac9920)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_external_startup
  - drivers/xen/dbgp.c:xen_dbgp_reset_prep
```
```
In arch/x86/pci/xen.c (ffffffff8216f45a)
Location: arch/x86/include/asm/xen/hypercall.h:444
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_restore_msi
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
  - arch/x86/pci/xen.c:xen_register_pirq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/dbgp.c:xen_dbgp_op
```
**Symbols:**

```
ffff8000100f0d44-ffff8000100f0d50: HYPERVISOR_physdev_op (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101f57c)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82893c22)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask
```
```
In drivers/xen/events/events_base.c (ffffffff828e734f)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_restore_pirqs
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
```
```
In drivers/xen/pci.c (ffffffff81637042)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff81637454)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff818a54ea)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101f3dc)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6c19)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask
```
```
In drivers/xen/events/events_base.c (ffffffff828fae55)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
```
```
In drivers/xen/pci.c (ffffffff81664dc2)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff816651d4)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff818f6b4a)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
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
In arch/x86/xen/apic.c (ffffffff8101f62c)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6bed)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_set_iopl_mask
```
```
In drivers/xen/events/events_base.c (ffffffff82900b86)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_test_irq_shared
  - drivers/xen/events/events_base.c:xen_destroy_irq
  - drivers/xen/events/events_base.c:xen_allocate_pirq_msi
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:eoi_pirq
```
```
In drivers/xen/pci.c (ffffffff8167f372)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/pci.c:xen_add_device
```
```
In drivers/xen/dbgp.c (ffffffff8167f784)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - drivers/xen/dbgp.c:xen_dbgp_op
```
```
In arch/x86/pci/xen.c (ffffffff8191785a)
Location: arch/x86/include/asm/xen/hypercall.h:374
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
  - arch/x86/pci/xen.c:acpi_register_gsi_xen
```
</details>
</li>
</ul>

## Differences
