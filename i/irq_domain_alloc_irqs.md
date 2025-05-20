# Function: <code>irq_domain_alloc_irqs</code>

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
In arch/x86/kernel/apic/msi.c (ffffffff810588f5)
Location: include/linux/irqdomain.h:369
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff81058f24)
Location: include/linux/irqdomain.h:369
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
```
```
In kernel/irq/irqdomain.c (ffffffff810e14ec)
Location: include/linux/irqdomain.h:369
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff81058e2c)
Location: include/linux/irqdomain.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff81059274)
Location: include/linux/irqdomain.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
```
```
In kernel/irq/irqdomain.c (ffffffff810e71ad)
Location: include/linux/irqdomain.h:399
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8105bbbc)
Location: include/linux/irqdomain.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff8105c004)
Location: include/linux/irqdomain.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
```
```
In kernel/irq/irqdomain.c (ffffffff810edb9d)
Location: include/linux/irqdomain.h:406
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8105b33c)
Location: include/linux/irqdomain.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/kernel/apic/htirq.c (ffffffff8105b704)
Location: include/linux/irqdomain.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
```
```
In kernel/irq/irqdomain.c (ffffffff810ed51c)
Location: include/linux/irqdomain.h:441
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8105f84c)
Location: include/linux/irqdomain.h:450
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In kernel/irq/irqdomain.c (ffffffff810f5f27)
Location: include/linux/irqdomain.h:450
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8106297b)
Location: include/linux/irqdomain.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In kernel/irq/irqdomain.c (ffffffff810fe24f)
Location: include/linux/irqdomain.h:456
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8106867b)
Location: include/linux/irqdomain.h:459
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In kernel/irq/irqdomain.c (ffffffff81109a1f)
Location: include/linux/irqdomain.h:459
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8106be7c)
Location: include/linux/irqdomain.h:466
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In kernel/irq/irqdomain.c (ffffffff8111300e)
Location: include/linux/irqdomain.h:466
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8106ca2c)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109864a)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8111f29f)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff81073d8c)
Location: include/linux/irqdomain.h:480
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109de3a)
Location: include/linux/irqdomain.h:480
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8112b7df)
Location: include/linux/irqdomain.h:480
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff81074864)
Location: include/linux/irqdomain.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/kernel/hpet.c (ffffffff82fcf9cf)
Location: include/linux/irqdomain.h:493
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099a0a)
Location: include/linux/irqdomain.h:493
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8112729f)
Location: include/linux/irqdomain.h:493
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/iommu/amd/init.c (ffffffff817a9477)
Location: include/linux/irqdomain.h:493
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_setup_intcapxt
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
In arch/x86/kernel/apic/msi.c (ffffffff81075314)
Location: include/linux/irqdomain.h:489
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/kernel/hpet.c (ffffffff831da4c1)
Location: include/linux/irqdomain.h:489
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a217)
Location: include/linux/irqdomain.h:489
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8112755f)
Location: include/linux/irqdomain.h:489
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/iommu/amd/init.c (ffffffff8178b2dd)
Location: include/linux/irqdomain.h:489
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
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
In arch/x86/kernel/apic/msi.c (ffffffff81082804)
Location: include/linux/irqdomain.h:498
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/kernel/hpet.c (ffffffff832bd5be)
Location: include/linux/irqdomain.h:498
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa241)
Location: include/linux/irqdomain.h:498
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81147acb)
Location: include/linux/irqdomain.h:498
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/iommu/amd/init.c (ffffffff81812a5e)
Location: include/linux/irqdomain.h:498
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
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
In arch/x86/kernel/apic/msi.c (ffffffff810923e7)
Location: include/linux/irqdomain.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/kernel/hpet.c (ffffffff8346ef9a)
Location: include/linux/irqdomain.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfc8d)
Location: include/linux/irqdomain.h:513
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff8116c014)
Location: include/linux/irqdomain.h:513
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
```
In drivers/iommu/amd/init.c (ffffffff81953a0b)
Location: include/linux/irqdomain.h:513
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
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
In arch/x86/kernel/apic/msi.c (ffffffff810a73d7)
Location: include/linux/irqdomain.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/kernel/hpet.c (ffffffff83e95591)
Location: include/linux/irqdomain.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810dbb7d)
Location: include/linux/irqdomain.h:501
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In drivers/iommu/amd/init.c (ffffffff81ab90fb)
Location: include/linux/irqdomain.h:501
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
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
In arch/x86/kernel/apic/msi.c (ffffffff810aa637)
Location: include/linux/irqdomain.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/kernel/hpet.c (ffffffff836b90f1)
Location: include/linux/irqdomain.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e714c)
Location: include/linux/irqdomain.h:504
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In drivers/gpio/gpiolib.c (ffffffff818ff4c9)
Location: include/linux/irqdomain.h:504
Inline: True
```
```
In drivers/iommu/amd/init.c (ffffffff81b05576)
Location: include/linux/irqdomain.h:504
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
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
In arch/x86/kernel/apic/msi.c (ffffffff810b16b7)
Location: include/linux/irqdomain.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/kernel/hpet.c (ffffffff838e99d0)
Location: include/linux/irqdomain.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef4fc)
Location: include/linux/irqdomain.h:504
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In drivers/gpio/gpiolib.c (ffffffff81946df2)
Location: include/linux/irqdomain.h:504
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
```
In drivers/iommu/amd/init.c (ffffffff81b5868b)
Location: include/linux/irqdomain.h:504
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:__iommu_setup_intcapxt
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010184dec)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In kernel/irq/irqdomain.c (c03d4004)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/irqdomain.h:540
Inline: True
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
In kernel/irq/irqdomain.c (ffffffe00011bd46)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8106c51c)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In kernel/irq/irqdomain.c (ffffffff8111787f)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8105c83c)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In kernel/irq/irqdomain.c (ffffffff8110856f)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8106c9cc)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In kernel/irq/irqdomain.c (ffffffff8111576f)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
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
In arch/x86/kernel/apic/msi.c (ffffffff8106e0cc)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099b1a)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
```
In kernel/irq/irqdomain.c (ffffffff81120d9f)
Location: include/linux/irqdomain.h:473
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
```
</details>
</li>
</ul>

## Differences
