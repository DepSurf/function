# Function: <code>irq_set_status_flags</code>

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
In arch/x86/kernel/apic/io_apic.c (ffffffff81056301)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810586af)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff810da456)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid
```
```
In kernel/irq/irqdomain.c (ffffffff810e0e00)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
```
```
In drivers/gpio/gpiolib.c (ffffffff814251a8)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/iommu/amd_iommu.c (ffffffff81531db4)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153d72d)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff81558174)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8156bcd8)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8157b1ce)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff8157e38e)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815834de)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8158536d)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/tps65912-irq.c (ffffffff81586807)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/tps65912-irq.c:tps65912_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81588aa0)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:553
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8158de1e)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8158f96e)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff815910be)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81591aae)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81593f6e)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81595a4c)
Location: include/linux/irq.h:553
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81056571)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810589df)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff810df965)
Location: include/linux/irq.h:582
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff810e6e72)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8146f0a8)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/iommu/amd_iommu.c (ffffffff81585f32)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8159238f)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff815aa286)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815c0c58)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815d020e)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff815d3675)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815d95de)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff815db450)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815ddd7a)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:582
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff815e2cfe)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff815e47de)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff815e5ebe)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff815e685e)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff815e8e1e)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff815ea888)
Location: include/linux/irq.h:582
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81059321)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105b76f)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff810e6245)
Location: include/linux/irq.h:599
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff810ed862)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff814910bf)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/iommu/amd_iommu.c (ffffffff815b33a9)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815bfc4f)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff815d8eb1)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815f0098)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815fce1e)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816003c5)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816062ce)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81608127)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160aa0a)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:599
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8160fbae)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8161168e)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81612d6e)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816136ee)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81615c2e)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81617698)
Location: include/linux/irq.h:599
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81058981)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105aebb)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff810e5895)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff810ed242)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8149ab7f)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c8acf)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d56bc)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff815ed99f)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81604258)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81610b9e)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81614275)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8161a0ce)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8161bfae)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161eb57)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:649
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81623c6e)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8162571e)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81626dfe)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8162772e)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81629b7e)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8162b588)
Location: include/linux/irq.h:649
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105ce01)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105f3cb)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff810edb65)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff810f5c52)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff814d9090)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162f461)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163c46c)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff81654d4f)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8166c638)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8167941e)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff8167c915)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8168279e)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8168469e)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81687397)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:678
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8168c55e)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8168e00e)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8168f6ce)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8168fffe)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8169249e)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81693ec8)
Location: include/linux/irq.h:678
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105fdc1)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810624c5)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff810f5fba)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff810fe003)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff815081f7)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/iommu/amd_iommu.c (ffffffff81669d0b)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677b32)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff8169065c)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816a8098)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816b4c2e)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816b8365)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816be81e)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff816c0761)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c33fd)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:680
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816c862e)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff816ca11e)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff816cb7ce)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816cc0fe)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff816ce59e)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816d0018)
Location: include/linux/irq.h:680
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81065b31)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff810681c5)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff8110174a)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff811097d3)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8151cb37)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/iommu/amd_iommu.c (ffffffff816888db)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696c12)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff816b0cec)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8ce8)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816d612e)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d95a5)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816dfbee)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff816e1ba1)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e47ed)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:681
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816e9b2e)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff816eb69e)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff816ecd7e)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816ed6be)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff816efbbe)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816f1638)
Location: include/linux/irq.h:681
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810692e3)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106b9b5)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff81109f45)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff81112dc2)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8154adfe)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8169559e)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bfe9b)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf528)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff816ea98f)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8170409a)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81711052)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81714cea)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817192f2)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8171b25e)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171de7a)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:694
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817232b2)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81724e02)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff817264c2)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81726e02)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81728f52)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8172abb2)
Location: include/linux/irq.h:694
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069c63)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c255)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810984e6)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff81116315)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff8111f052)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8156bf3e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b812e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e2ef8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f3368)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff8170e9cf)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817283ea)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81735352)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81738ffa)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8173d5e2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8173f54e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8174214a)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:712
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81747552)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff817490b2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8174a782)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8174b0d2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8174d1a2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8174edb2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8107294b)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/apic/msi.c (ffffffff81073575)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109dcd6)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff81121fc5)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff8112a0f5)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8161016d)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c20e)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd/iommu.c (ffffffff81798703)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817abf03)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff817ca39f)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817e464a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817f26a2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff817f665a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817faf72)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff817fcfee)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ffd66)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:742
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81805252)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff818071c2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff818086d2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81809152)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8180b272)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8180d47e)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81073dc9)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff8107cc2a)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810998a6)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff8111e045)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff81125ae9)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff81636635)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/xen/events/events_base.c (ffffffff81732a17)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786d2e)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a6e34)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b8385)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff817dee3f)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817f94aa)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81806c62)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81809382)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8180d2c2)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8180ea6e)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81811006)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:755
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81815b42)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81817332)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81818622)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81819002)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8181a9f2)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8181c40e)
Location: include/linux/irq.h:755
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8107485a)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff8107dd2a)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a0b6)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff8111e2e5)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff811271cb)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff816196f7)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/xen/events/events_base.c (ffffffff817165e7)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a68e)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd/iommu.c (ffffffff817888c4)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179b4cd)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff817c323f)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817dd72a)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817eb892)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff817edf22)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817f1a92)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff817f329e)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f5786)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:757
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817fa202)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff817fb7a2)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff817fca62)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff817fd422)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff817fe112)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff817ff7ce)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81080cde)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff8108c69a)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810aa0d6)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff8113e765)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff8114772b)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff816889fa)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/xen/events/events_base.c (ffffffff8179387f)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817ef7bd)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd/iommu.c (ffffffff81810204)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81823ff9)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff8184d5bf)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8186904a)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81878412)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8187a192)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8187c1db)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e916)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:759
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff818836f2)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81884d52)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff818863f2)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81887172)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81887fc2)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81889ec6)
Location: include/linux/irq.h:759
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8108ff41)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff8109d03d)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810bfb0a)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff81161d15)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff8116bb6b)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff817a59f6)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/xen/events/events_base.c (ffffffff818cc40f)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192fb7a)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd/iommu.c (ffffffff81950757)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81963a11)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff819929b0)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b1c78)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff819c07be)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff819c292e)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff819c4b6b)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c6e38)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:763
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff819cc1de)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff819cda4e)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff819cf1de)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff819d00be)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff819d105e)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff819d3175)
Location: include/linux/irq.h:763
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/i8259.c (ffffffff810540e3)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff83e74fed)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a4f01)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff810b40cd)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810db9ea)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff81195505)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff811a0d5b)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff818be5b6)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/xen/events/events_base.c (ffffffff81a1d9af)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8df5a)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab5d94)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81accb88)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff81b02ed0)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b26bf8)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b36ade)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b38b4e)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81b3b93b)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3d9f7)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b43f6e)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81b4646e)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b47fee)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81b490de)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a4ee)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81b4d563)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/i8259.c (ffffffff81055143)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff83696a1d)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a7fe7)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff810b71cd)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810e6f7e)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff811a6ed5)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff811b2be6)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff81901746)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/xen/events/events_base.c (ffffffff81a66baf)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad970a)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b02264)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b196c7)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff81b50ed0)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b77138)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b89c4e)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b8bfbe)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81b8ed29)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b90e87)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:778
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b9734e)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81b9983e)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b9b43e)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81b9c52e)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9d92e)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81ba09d3)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/i8259.c (ffffffff8105c383)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff838c673d)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810af076)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:mp_check_pin_attr
```
```
In arch/x86/kernel/hpet.c (ffffffff810be60d)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef32f)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff811b6a2c)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff811c2a06)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff81949046)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/xen/events/events_base.c (ffffffff81ab9524)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2c9fa)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b55c22)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6ef80)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff81ba9480)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcaf08)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81bddb4e)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81bdfebe)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81be2c49)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be4e27)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:760
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81beb31e)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81bed7ee)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81bef3fe)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81bf051e)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf191e)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81bf4b33)
Location: include/linux/irq.h:760
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e09f4)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init
```
```
In kernel/irq/irqdesc.c (ffff800010177f54)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffff800010184b78)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/irqchip/irq-bcm2836.c (ffff80001066ad94)
Location: include/linux/irq.h:712
Inline: True
```
```
In drivers/irqchip/irq-gic.c (ffff80001066bb48)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066e68c)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v4.c (ffff800010675420)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v4.c:its_map_vlpi
```
```
In drivers/irqchip/irq-partition-percpu.c (ffff800010675c38)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff80001067a074)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_irq_map
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d624)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map
```
```
In drivers/gpio/gpiolib.c (ffff8000106bf2a0)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106cdf20)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
```
```
In drivers/pci/controller/pci-aardvark.c (ffff80001071fd54)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_map
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010723f68)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_legacy_map
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001080ac68)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_detach_irq
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a794c)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/base/power/wakeirq.c (ffff8000108fee60)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffff80001091d508)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffff80001092c738)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (ffff80001092f4e4)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (ffff800010930bec)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffff800010933bb4)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffff8000109388a0)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffff80001093a980)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093da74)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e2c4)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (ffff8000109440fc)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffff800010946c10)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffff8000109483b4)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffff800010949034)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffff80001094b678)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffff80001094dee8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/perf/arm_pmu.c (ffff800010b954a0)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98c34)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
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
In kernel/irq/irqdesc.c (c03c98a8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (c03d3c20)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/irqchip/irq-hip04.c (c0813da4)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_map
```
```
In drivers/irqchip/irq-gic.c (c0814e1c)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
```
```
In drivers/irqchip/irq-gic-v3.c (c0817488)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v4.c (c081d808)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v4.c:its_map_vlpi
```
```
In drivers/irqchip/irq-partition-percpu.c (c081e028)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081e948)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
```
```
In drivers/irqchip/irq-rda-intc.c (c081ec9c)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-rda-intc.c:rda_irq_map
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c0823138)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map
```
```
In drivers/gpio/gpiolib.c (c085fa54)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/dma/ipu/ipu_irq.c (c0927400)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_detach_irq
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c09a4558)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/base/power/wakeirq.c (c09e9108)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (c0a029a8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (c0a0b314)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/asic3.c (c0a0ed48)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_irq_remove
```
```
In drivers/mfd/stmpe.c (c0a10b70)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (c0a11ecc)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/tc6393xb.c (c0a133a8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_detach_irq
```
```
In drivers/mfd/arizona-irq.c (c0a16ba8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (c0a20d04)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (c0a22b9c)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/tps65217.c (c0a22f40)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_irq_map
```
```
In drivers/mfd/twl4030-irq.c (c0a264dc)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (c0a26d78)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (c0a2d214)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (c0a2fe54)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (c0a31538)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (c0a3207c)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (c0a341ac)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (c0a37f60)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/clocksource/timer-tegra.c (c15abd78)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
```
```
In drivers/clocksource/exynos_mct.c (c15ac1d8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/clocksource/exynos_mct.c:mct_init_dt
```
```
In drivers/perf/arm_pmu.c (c0c7ea4c)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_request_irq
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
In arch/powerpc/sysdev/i8259.c (c0000000000b8d18)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/powerpc/sysdev/i8259.c:i8259_host_map
  - arch/powerpc/sysdev/i8259.c:i8259_host_map
```
```
In kernel/irq/irqdesc.c (c0000000001d19e8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (c0000000001debb0)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (c00000000083cf50)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c00000000093e48c)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/base/power/wakeirq.c (c00000000099bb64)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (c0000000009c208c)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (c0000000009cbb84)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (c0000000009cf174)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (c0000000009d0d14)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (c0000000009d4b90)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (c0000000009df514)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (c0000000009e1fa4)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e5b30)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e6788)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (c0000000009eda44)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (c0000000009f1504)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (c0000000009f3444)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (c0000000009f44d4)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (c0000000009f71a4)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (c0000000009fa628)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In kernel/irq/irqdesc.c (ffffffe000112b14)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffe00011ba2e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a6866)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffe00055e276)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/base/power/wakeirq.c (ffffffe00058cfd8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffe00059cd0a)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffe0005a3a24)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (ffffffe0005a5ec0)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (ffffffe0005a7118)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a9a0e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffe0005ad5e6)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffe0005af37a)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b1c26)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b2312)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (ffffffe0005b6c38)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffe0005b8eba)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffe0005ba3b8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffe0005baed6)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffe0005bce3a)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffe0005beeda)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069753)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106bd45)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff8110e8f5)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff81117632)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff815616fe)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167db8e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a8948)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8b58)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff816d411f)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816ee1ca)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816fcd5a)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817010c2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81059ab3)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8105c065)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff810ff645)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff81108322)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8155254e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165cc7e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff81686338)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696798)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff816af3bf)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c880a)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d0b6a)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816d4ed2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81069c03)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106c1f5)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In kernel/irq/irqdesc.c (ffffffff8110c7e5)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff81115522)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8156026e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816abf6e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d6bb8)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e7028)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff8170268f)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8171b8aa)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81728812)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff8172c4ba)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81730aa2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81732a0e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8173560a)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:712
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8173aa12)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8173c572)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8173dc42)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8173e592)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81740662)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81742272)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8106b383)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_register_handler
```
```
In arch/x86/kernel/apic/msi.c (ffffffff8106d8f5)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:hpet_msi_init
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810999b6)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff81117cf5)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
```
```
In kernel/irq/irqdomain.c (ffffffff81120b52)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8157a0de)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c63ce)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f1168)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701728)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
```
In drivers/base/power/wakeirq.c (ffffffff8171ceaf)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_dedicated_wake_irq
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81736c0a)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81743c52)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff817478fa)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8174bee2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8174de4e)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81750a4a)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:712
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81755e52)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff817579b2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81759082)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff817599d2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8175baa2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8175d6b2)
Location: include/linux/irq.h:712
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
</ul>

## Differences
