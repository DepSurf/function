# Function: <code>irq_data_get_irq_handler_data</code>

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
In arch/x86/kernel/apic/msi.c (ffffffff81058656)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81062e25)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_unmask
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/pci/htirq.c (ffffffff8145578c)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/pci/htirq.c:mask_ht_irq
  - drivers/pci/htirq.c:unmask_ht_irq
```
```
In drivers/iommu/dmar.c (ffffffff8153519e)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_unmask
  - drivers/iommu/dmar.c:dmar_msi_mask
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
In arch/x86/kernel/apic/msi.c (ffffffff81058986)
Location: include/linux/irq.h:665
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81062b05)
Location: include/linux/irq.h:665
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_msi_unmask
```
```
In drivers/pci/htirq.c (ffffffff814a241c)
Location: include/linux/irq.h:665
Inline: True
Inline callers:
  - drivers/pci/htirq.c:unmask_ht_irq
  - drivers/pci/htirq.c:mask_ht_irq
```
```
In drivers/iommu/dmar.c (ffffffff81589abe)
Location: include/linux/irq.h:665
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff8105b716)
Location: include/linux/irq.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81065c95)
Location: include/linux/irq.h:682
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_mask
  - arch/x86/kernel/hpet.c:hpet_msi_unmask
```
```
In drivers/pci/htirq.c (ffffffff814c406c)
Location: include/linux/irq.h:682
Inline: True
Inline callers:
  - drivers/pci/htirq.c:unmask_ht_irq
  - drivers/pci/htirq.c:mask_ht_irq
```
```
In drivers/iommu/dmar.c (ffffffff815b716e)
Location: include/linux/irq.h:682
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff8105ae66)
Location: include/linux/irq.h:732
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81064140)
Location: include/linux/irq.h:732
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/pci/htirq.c (ffffffff814ce2fc)
Location: include/linux/irq.h:732
Inline: True
Inline callers:
  - drivers/pci/htirq.c:unmask_ht_irq
  - drivers/pci/htirq.c:mask_ht_irq
```
```
In drivers/iommu/dmar.c (ffffffff815ccf4e)
Location: include/linux/irq.h:732
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff8105f376)
Location: include/linux/irq.h:761
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff810682c0)
Location: include/linux/irq.h:761
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/dmar.c (ffffffff81633d4e)
Location: include/linux/irq.h:761
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff81062485)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff8106ae10)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/dmar.c (ffffffff8166eee5)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff81068185)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81070ba0)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/dmar.c (ffffffff8168d445)
Location: include/linux/irq.h:764
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff8106b975)
Location: include/linux/irq.h:777
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81074bf0)
Location: include/linux/irq.h:777
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/dmar.c (ffffffff816c4e55)
Location: include/linux/irq.h:777
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff8106c215)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81075bc0)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/dmar.c (ffffffff816e7d85)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff81073535)
Location: include/linux/irq.h:825
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff8107d340)
Location: include/linux/irq.h:825
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/gpio/gpio-msic.c (ffffffff8161911d)
Location: include/linux/irq.h:825
Inline: True
Inline callers:
  - drivers/gpio/gpio-msic.c:msic_gpio_irq_handler
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179e8c5)
Location: include/linux/irq.h:825
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_mask
  - drivers/iommu/intel/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/hpet.c (ffffffff8107d2b0)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/gpio/gpio-msic.c (ffffffff8163f94d)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - drivers/gpio/gpio-msic.c:msic_gpio_irq_handler
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ac615)
Location: include/linux/irq.h:838
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_mask
  - drivers/iommu/intel/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/hpet.c (ffffffff8107e3b0)
Location: include/linux/irq.h:840
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178f4e5)
Location: include/linux/irq.h:840
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_mask
  - drivers/iommu/intel/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/hpet.c (ffffffff8108cef0)
Location: include/linux/irq.h:842
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/intel/dmar.c (ffffffff81816e05)
Location: include/linux/irq.h:842
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_mask
  - drivers/iommu/intel/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/hpet.c (ffffffff8109db4f)
Location: include/linux/irq.h:846
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/intel/dmar.c (ffffffff81957e15)
Location: include/linux/irq.h:846
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_mask
  - drivers/iommu/intel/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/hpet.c (ffffffff810b4d1f)
Location: include/linux/irq.h:848
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abedf5)
Location: include/linux/irq.h:848
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_mask
  - drivers/iommu/intel/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/hpet.c (ffffffff810b7def)
Location: include/linux/irq.h:861
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0b7a5)
Location: include/linux/irq.h:861
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_mask
  - drivers/iommu/intel/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/hpet.c (ffffffff810bf22f)
Location: include/linux/irq.h:843
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_write_msg
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5f885)
Location: include/linux/irq.h:843
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_msi_mask
  - drivers/iommu/intel/dmar.c:dmar_msi_unmask
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
In drivers/irqchip/irq-gic.c (ffff80001066b8f0)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_set_vcpu_affinity
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106cd9f4)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:gpio_irq_type_unbanked
  - drivers/gpio/gpio-davinci.c:gpio_irq_enable
  - drivers/gpio/gpio-davinci.c:gpio_irq_disable
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
In drivers/irqchip/irq-gic.c (c0814a70)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_set_vcpu_affinity
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
In arch/powerpc/sysdev/xive/common.c (c0000000000bcb28)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_get_irqchip_state
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_vcpu_affinity
  - arch/powerpc/sysdev/xive/common.c:xive_irq_retrigger
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_type
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_affinity
  - arch/powerpc/sysdev/xive/common.c:xive_irq_mask
  - arch/powerpc/sysdev/xive/common.c:xive_irq_unmask
  - arch/powerpc/sysdev/xive/common.c:xive_irq_shutdown
  - arch/powerpc/sysdev/xive/common.c:xive_irq_startup
  - arch/powerpc/sysdev/xive/common.c:xive_pick_irq_target
  - arch/powerpc/sysdev/xive/common.c:xive_irq_eoi
  - arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config
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
In arch/x86/kernel/apic/msi.c (ffffffff8106bd05)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81074bc0)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/dmar.c (ffffffff816ad865)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff8105c025)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81064bf0)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/dmar.c (ffffffff8168b1c5)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff8106c1b5)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81074b70)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/dmar.c (ffffffff816dba45)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
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
In arch/x86/kernel/apic/msi.c (ffffffff8106d8b5)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_write_msg
```
```
In arch/x86/kernel/hpet.c (ffffffff81076bd0)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
  - arch/x86/kernel/hpet.c:hpet_msi_mask
```
```
In drivers/iommu/dmar.c (ffffffff816f6015)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_msi_mask
  - drivers/iommu/dmar.c:dmar_msi_unmask
```
</details>
</li>
</ul>

## Differences
