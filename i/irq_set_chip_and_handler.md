# Function: <code>irq_set_chip_and_handler</code>

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
In arch/x86/kernel/i8259.c (ffffffff810336e8)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff81f66b06)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff810df548)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff810e0e12)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_disassociate
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
```
```
In drivers/gpio/gpiolib.c (ffffffff814248a7)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8157b1b7)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8157ba88)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (ffffffff8157e377)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815834c7)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81585356)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/tps65912-irq.c (ffffffff815867f0)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/tps65912-irq.c:tps65912_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81588a88)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:513
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8158b66a)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8158de07)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8158f957)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff815910a7)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81591a97)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81593f57)
Location: include/linux/irq.h:513
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81595a35)
Location: include/linux/irq.h:513
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
In arch/x86/kernel/i8259.c (ffffffff810328b8)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff81f8e975)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff810e4eb8)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff810e6e80)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8146e5f7)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/irq.h:538
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815d01f7)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815d0d49)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (ffffffff815d365e)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815d95c7)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff815db420)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815ddd5e)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:538
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff815e0d9e)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff815e2ce7)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff815e47c7)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff815e5ea7)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff815e6847)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff815e8e07)
Location: include/linux/irq.h:538
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff815ea851)
Location: include/linux/irq.h:538
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
In arch/x86/kernel/i8259.c (ffffffff81032528)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff81fc9d04)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff810eb7c8)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff810ed870)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff81490657)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/irq.h:555
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815fce07)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815fd702)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (ffffffff816003ae)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816062b7)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff816080f7)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160a9ee)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:555
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8160da3b)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8160fb97)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81611677)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81612d57)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816136d7)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81615c17)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81617661)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core.c (ffffffff8170ac98)
Location: include/linux/irq.h:555
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff81030768)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff820aa454)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff810eb073)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff810ed250)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff81499d47)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/irq.h:605
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81610b87)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816114b1)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (ffffffff8161425e)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8161a0b7)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8161bf88)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161eb3d)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:605
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81621b3d)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81623c57)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81625707)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81626de7)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81627717)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81629b67)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8162b54f)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8171f598)
Location: include/linux/irq.h:605
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff81032b08)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff826b0f4d)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff810f35d3)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff810f5c60)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff814d8037)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/irq.h:634
Inline: True
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81679407)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81679d51)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (ffffffff8167c8fe)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81682787)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81684678)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8168737d)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:634
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8168a36d)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8168c547)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8168dff7)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8168f6b7)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8168ffe7)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81692487)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81693e8f)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817904f8)
Location: include/linux/irq.h:634
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff81033e25)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff826da631)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff810fb873)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff810fe011)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff815075c9)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816b4c17)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816b5810)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (ffffffff816b834e)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816be807)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff816c074e)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c33ea)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:636
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816c6484)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816c8617)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff816ca107)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff816cb7b7)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816cc0e7)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff816ce587)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816d0005)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d30f5)
Location: include/linux/irq.h:636
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff81035175)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff82890a67)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff81107037)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811097e1)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8151bb49)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816d6117)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816d6a70)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d958e)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816dfbd7)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff816e1b8e)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e47da)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:637
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816e7884)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816e9b17)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff816eb687)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff816ecd67)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816ed6a7)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff816efba7)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816f1625)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fa235)
Location: include/linux/irq.h:637
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff810370d9)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff828a7fd8)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff81110621)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff81112dd0)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff81549e8b)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8171103a)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817121ae)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (ffffffff81714cd2)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817192da)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8171b247)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171de62)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:650
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81721040)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8172329a)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81724dea)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff817264aa)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81726dea)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81728f3a)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8172ab9a)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183af65)
Location: include/linux/irq.h:650
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff810378a9)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff828ab03a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff8111c881)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff8111f060)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8156b02b)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8173533a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817364ae)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (ffffffff81738fe2)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8173d5ca)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8173f537)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81742132)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:668
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8174519f)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8174753a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8174909a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8174a76a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8174b0ba)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8174d18a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8174ed9a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186c8f5)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff810396a9)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff82cd028f)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff81128991)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff8112a10f)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8160e20b)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/gpio/gpio-msic.c (ffffffff81619480)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817f268a)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817f3c94)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (ffffffff817f6642)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817faf5a)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff817fcfd7)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ffd4e)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:698
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81802f46)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8180523a)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff818071aa)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff818086ba)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8180913a)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8180b25a)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8180d466)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81940625)
Location: include/linux/irq.h:698
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff81039f09)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff82fbc0cf)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff811242a0)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff81125aef)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_remove_irq
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff81634adb)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/gpio/gpio-msic.c (ffffffff8163fcb0)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81806c4a)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff818078f4)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (ffffffff8180936a)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8180d2aa)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8180ea57)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81810fee)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:711
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81813dd6)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81815b2a)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8181731a)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8181860a)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81818fea)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8181a9da)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8181c3f6)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81946798)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff8103b9d9)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff831c687a)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff811245f0)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811271d9)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff8161855b)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817eb87a)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec3bf)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (ffffffff817edf0a)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817f1a7a)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff817f3287)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f576e)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:713
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817f84e6)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817fa1ea)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff817fb78a)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff817fca4a)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff817fd40a)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff817fe0fa)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff817ff7b6)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81929fc8)
Location: include/linux/irq.h:713
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff810414c3)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff832a76a0)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff81144bf2)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff81147739)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff816877f8)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff818783fa)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81878f9f)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8187a17a)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8187c1c4)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e8fe)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:715
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81881936)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff818836da)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81884d3a)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff818863da)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8188715a)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81887faa)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81889eae)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cd148)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff8104911e)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff834569d9)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff81168dd7)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff8116bb7a)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff817a4a7a)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff819c07a7)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff819c14dd)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/wm831x-irq.c (ffffffff819c2917)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff819c4b54)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c6e20)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:718
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff819ca199)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff819cc1c7)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff819cda37)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff819cf1c7)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff819d00a7)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff819d1047)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff819d315e)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2f1e8)
Location: include/linux/irq.h:718
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff810540de)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff83e74fda)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff8119d637)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811a0d6a)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff818bc79a)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b36ac7)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b38b37)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81b3b924)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3d9e0)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:720
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b41629)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b43f57)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81b46457)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b47fd7)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81b490c7)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a4d7)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81b4d54c)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc3058)
Location: include/linux/irq.h:720
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff8105513e)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff83696a0a)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff811af4cd)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811b2bf4)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff818ff90a)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b89c37)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b8bfa7)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81b8ed12)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b90e70)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:733
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b94999)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b97337)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81b99827)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b9b427)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81b9c517)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9d917)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81ba09bc)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2ab78)
Location: include/linux/irq.h:733
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff8105c37e)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff838c672a)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff811bf0cd)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff811c2a14)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_dispose_mapping
```
```
In drivers/gpio/gpiolib.c (ffffffff819470fa)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81bddb37)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81bdfea7)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81be2c32)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be4e10)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:715
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be8969)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81beb307)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81bed7d7)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81bef3e7)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81bf0507)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf1907)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81bf4b1c)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de0a38)
Location: include/linux/irq.h:715
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In kernel/irq/generic-chip.c (ffff8000101812a4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffff800010184b88)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/irqchip/irq-bcm2835.c (ffff800011470958)
Location: include/linux/irq.h:668
Inline: True
```
```
In drivers/irqchip/irq-sun4i.c (ffff80001066b288)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-sun4i.c:sun4i_irq_map
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800010676d54)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_map
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff80001067a05c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_irq_map
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff80001067bcec)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_irq_map
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d640)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069c508)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b6968)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (ffff8000106b7ecc)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
```
```
In drivers/gpio/gpiolib.c (ffff8000106be8e8)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf1b0)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_map
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071ecac)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
```
```
In drivers/pci/controller/pci-aardvark.c (ffff80001071fd64)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_irq_map
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721444)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_map
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff800010723474)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010723f3c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_legacy_map
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010726bb4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_intx_map
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff800010729fec)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intx_map
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072bbcc)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_intx_map
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff80001073264c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_init_legacy_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffff80001092c718)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092de58)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (ffff80001092f458)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (ffff800010930b78)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffff800010933b98)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffff800010938880)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffff80001093a96c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093da60)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e250)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/ezx-pcap.c (ffff800010941090)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffff8000109440e0)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffff800010946bf0)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffff800010948398)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffff800010949018)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffff80001094b658)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffff80001094ded4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffff800010aaf480)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
```
In drivers/edac/altera_edac.c (ffff800010b16020)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:a10_eccmgr_irqdomain_map
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
In kernel/irq/generic-chip.c (c03d0da0)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (c03d3c30)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/irqchip/exynos-combiner.c (c0813908)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_irq_domain_map
```
```
In drivers/irqchip/irq-hip04.c (c0813d88)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_map
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_map
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081e958)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
```
```
In drivers/irqchip/irq-rda-intc.c (c081ecb4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-rda-intc.c:rda_irq_map
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081f9d4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_domain_map
```
```
In drivers/irqchip/irq-aspeed-vic.c (c0821c40)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-vic.c:avic_map
  - drivers/irqchip/irq-aspeed-vic.c:avic_map
```
```
In drivers/irqchip/irq-aspeed-i2c-ic.c (c0821d90)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_map_irq_domain
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c082315c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_irq_map
```
```
In drivers/pinctrl/pinctrl-single.c (c083f2d0)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852084)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_irq_map
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (c0858e4c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
```
```
In drivers/gpio/gpiolib.c (c085e6e0)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/gpio/gpio-htc-egpio.c (c1550acc)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
```
```
In drivers/gpio/gpio-mpc8xxx.c (c0869878)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_gpio_irq_map
```
```
In drivers/gpio/gpio-tegra.c (c0871a04)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a7e50)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
```
```
In drivers/pci/controller/pci-tegra.c (c08abc8c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_msi_map
```
```
In drivers/pci/controller/pcie-rcar.c (c08ae94c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_map
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b0188)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
```
```
In drivers/pci/controller/pcie-altera.c (c08b22a4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_intx_map
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b4e28)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_intx_map
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c08b9ca8)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_intx_map
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf6a8)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_intx_map
```
```
In drivers/mfd/88pm860x-core.c (c0a0b2fc)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/asic3.c (c0a0ed58)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_irq_remove
```
```
In drivers/mfd/htc-i2cpld.c (c0a0f89c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (c0a10af0)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (c0a11e64)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/t7l66xb.c (c0a12844)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
```
```
In drivers/mfd/tc6393xb.c (c0a13c2c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
```
```
In drivers/mfd/arizona-irq.c (c0a16b8c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (c0a20ce8)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (c0a22b88)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/tps65217.c (c0a22f28)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_irq_map
```
```
In drivers/mfd/twl4030-irq.c (c0a264c8)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (c0a26d10)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/ezx-pcap.c (c0a2aa48)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (c0a2d1f8)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (c0a2fe3c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (c0a3151c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (c0a32060)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (c0a34194)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (c0a37f4c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (c0b90fe4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
```
In drivers/memory/omap-gpmc.c (c0c6f7e8)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_irq_map
  - drivers/memory/omap-gpmc.c:gpmc_irq_map
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
In arch/powerpc/sysdev/mpic.c (c0000000000b6124)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
```
```
In arch/powerpc/sysdev/i8259.c (c0000000000b8d2c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/powerpc/sysdev/i8259.c:i8259_host_map
```
```
In arch/powerpc/sysdev/xics/xics-common.c (c0000000000ba0c0)
Location: include/linux/irq.h:668
Inline: True
```
```
In arch/powerpc/sysdev/xics/ics-rtas.c (c0000000000bb828)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/ics-rtas.c:ics_rtas_map
```
```
In arch/powerpc/sysdev/xics/ics-opal.c (c0000000000bbf8c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/ics-opal.c:ics_opal_map
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000be310)
Location: include/linux/irq.h:668
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c0000000000ccfac)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_map
```
```
In kernel/irq/generic-chip.c (c0000000001dc010)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (c0000000001debb8)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000833d50)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/gpio/gpiolib.c (c00000000083b900)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/pci/controller/pci-ftpci100.c (c0000000008904f4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
```
```
In drivers/pci/controller/pcie-xilinx.c (c000000000891dd4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
```
```
In drivers/mfd/88pm860x-core.c (c0000000009cbb64)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (c0000000009cd740)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (c0000000009cf0bc)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (c0000000009d0c7c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (c0000000009d4b70)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (c0000000009df4f4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (c0000000009e1f8c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e5b14)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e66ec)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/ezx-pcap.c (c0000000009ea454)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (c0000000009eda24)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (c0000000009f14e4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (c0000000009f3424)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (c0000000009f44b4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (c0000000009f7184)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (c0000000009fa610)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (c000000000b9216c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In kernel/irq/generic-chip.c (ffffffe00011902a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffe00011ba54)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe000495744)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_irqdomain_map
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0756)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a57d4)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e5e0c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_irq_map
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e6d18)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_intx_map
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffe0005a3a08)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4c68)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (ffffffe0005a5e44)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_unmap
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (ffffffe0005a70ae)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_unmap
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a99f2)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffe0005ad5ca)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffe0005af346)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b1bfe)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b22aa)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_unmap
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b4adc)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffe0005b6c1c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffe0005b8e9e)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffe0005ba39c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffe0005baeba)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffe0005bce1e)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffe0005bee9c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b7a86)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff81037a09)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff8289904c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff81114e61)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff81117640)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff815607eb)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816fcd42)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817010aa)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8170323f)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
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
In arch/x86/kernel/i8259.c (ffffffff810273e9)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff82891347)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff81105b71)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff81108330)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8155163b)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d0b52)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816d4eba)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816d703f)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
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
In arch/x86/kernel/i8259.c (ffffffff81037869)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff828ac02c)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff81112d51)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff81115530)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff8155f35b)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817287fa)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8172996e)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (ffffffff8172c4a2)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81730a8a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff817329f7)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817355f2)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:668
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8173865f)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8173a9fa)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8173c55a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8173dc2a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8173e57a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8174064a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8174225a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81860a85)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
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
In arch/x86/kernel/i8259.c (ffffffff81038869)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:make_8259A_irq
```
```
In arch/x86/kernel/irqinit.c (ffffffff828ac04a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - arch/x86/kernel/irqinit.c:init_ISA_irqs
```
```
In kernel/irq/generic-chip.c (ffffffff8111e4df)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In kernel/irq/irqdomain.c (ffffffff81120b60)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
  - kernel/irq/irqdomain.c:irq_domain_disassociate
```
```
In drivers/gpio/gpiolib.c (ffffffff815791db)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81743c3a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81744dae)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-irq.c (ffffffff817478e2)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8174beca)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8174de37)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81750a32)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:668
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81753bef)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_remove
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81755e3a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8175799a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8175906a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff817599ba)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8175ba8a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8175d69a)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187bc95)
Location: include/linux/irq.h:668
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_host_notify_irq_map
```
</details>
</li>
</ul>

## Differences
