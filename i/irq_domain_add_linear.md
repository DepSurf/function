# Function: <code>irq_domain_add_linear</code>

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
In arch/x86/kernel/apic/io_apic.c (ffffffff810565aa)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8156c2d3)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff8157e451)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81583591)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:237
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8158de85)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff815911f2)
Location: include/linux/irqdomain.h:237
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8105682a)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/irqdomain.h:263
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815c1478)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff815d3755)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815d968b)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:263
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff815e2d65)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff815e5fe6)
Location: include/linux/irqdomain.h:263
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In arch/x86/kernel/apic/io_apic.c (ffffffff810595da)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
```
```
In drivers/pci/host/pcie-designware.c (0)
Location: include/linux/irqdomain.h:270
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815f08b8)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff8160049f)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8160637b)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:270
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8160fc15)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff81612e96)
Location: include/linux/irqdomain.h:270
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/irqdomain.h:305
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816046d6)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff81614352)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8161a176)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:305
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81623cd5)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff81626f25)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/pci/dwc/pcie-designware-host.c (0)
Location: include/linux/irqdomain.h:314
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8166cab6)
Location: include/linux/irqdomain.h:314
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff8167c9f8)
Location: include/linux/irqdomain.h:314
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81682846)
Location: include/linux/irqdomain.h:314
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:314
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8168c5c5)
Location: include/linux/irqdomain.h:314
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff8168f7f5)
Location: include/linux/irqdomain.h:314
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/base/regmap/regmap-irq.c (ffffffff816a8864)
Location: include/linux/irqdomain.h:320
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff816b8442)
Location: include/linux/irqdomain.h:320
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816be8c2)
Location: include/linux/irqdomain.h:320
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:320
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816c86b0)
Location: include/linux/irqdomain.h:320
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff816cb8f2)
Location: include/linux/irqdomain.h:320
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/base/regmap/regmap-irq.c (ffffffff816c9435)
Location: include/linux/irqdomain.h:322
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d9696)
Location: include/linux/irqdomain.h:322
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816dfc92)
Location: include/linux/irqdomain.h:322
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:322
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816e9bb0)
Location: include/linux/irqdomain.h:322
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff816ecea2)
Location: include/linux/irqdomain.h:322
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/base/regmap/regmap-irq.c (ffffffff8170477a)
Location: include/linux/irqdomain.h:324
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff81714dc0)
Location: include/linux/irqdomain.h:324
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817193a2)
Location: include/linux/irqdomain.h:324
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:324
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81723340)
Location: include/linux/irqdomain.h:324
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff817265f9)
Location: include/linux/irqdomain.h:324
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/base/regmap/regmap-irq.c (ffffffff81728aca)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff817390d0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8173d692)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:331
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817475e0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff8174a8b9)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/base/regmap/regmap-irq.c (ffffffff817e5120)
Location: include/linux/irqdomain.h:332
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
```
```
In drivers/mfd/arizona-irq.c (ffffffff817f6950)
Location: include/linux/irqdomain.h:332
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817fb044)
Location: include/linux/irqdomain.h:332
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:332
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff818052e0)
Location: include/linux/irqdomain.h:332
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff8180889e)
Location: include/linux/irqdomain.h:332
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff81809680)
Location: include/linux/irqdomain.h:339
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8180d3a4)
Location: include/linux/irqdomain.h:339
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:339
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81815bd0)
Location: include/linux/irqdomain.h:339
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff818187ee)
Location: include/linux/irqdomain.h:339
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff817ee263)
Location: include/linux/irqdomain.h:344
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817f1b42)
Location: include/linux/irqdomain.h:344
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:344
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817fa290)
Location: include/linux/irqdomain.h:344
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff817fcc2e)
Location: include/linux/irqdomain.h:344
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/mfd/wm831x-irq.c (ffffffff8187a794)
Location: include/linux/irqdomain.h:343
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:343
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81883780)
Location: include/linux/irqdomain.h:343
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff818866bb)
Location: include/linux/irqdomain.h:343
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/mfd/wm831x-irq.c (ffffffff819c2ec4)
Location: include/linux/irqdomain.h:357
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:357
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff819cc270)
Location: include/linux/irqdomain.h:357
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff819cf4f9)
Location: include/linux/irqdomain.h:357
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/mfd/wm831x-irq.c (ffffffff81b39186)
Location: include/linux/irqdomain.h:345
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:345
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b4400f)
Location: include/linux/irqdomain.h:345
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b48339)
Location: include/linux/irqdomain.h:345
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/mfd/wm831x-irq.c (ffffffff81b8c5f6)
Location: include/linux/irqdomain.h:348
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:348
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b973ef)
Location: include/linux/irqdomain.h:348
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b9b7de)
Location: include/linux/irqdomain.h:348
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/mfd/wm831x-irq.c (ffffffff81be04f6)
Location: include/linux/irqdomain.h:348
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:348
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81beb3bf)
Location: include/linux/irqdomain.h:348
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff81bef79e)
Location: include/linux/irqdomain.h:348
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/irqchip/irq-al-fic.c (ffff800011470688)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
```
```
In drivers/irqchip/irq-bcm2835.c (ffff800011470870)
Location: include/linux/irqdomain.h:331
Inline: True
```
```
In drivers/irqchip/irq-bcm2836.c (ffff800011470ab8)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm2836.c:bcm2836_arm_irqchip_l1_intc_of_init
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (ffff800011470d50)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-sun4i.c (ffff80001147100c)
Location: include/linux/irqdomain.h:331
Inline: True
```
```
In drivers/irqchip/irq-sunxi-nmi.c (ffff800011471178)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-sunxi-nmi.c:sunxi_sc_nmi_irq_init
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff80001067682c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/irqchip/irq-bcm7038-l1.c (ffff800011475444)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_of_init
```
```
In drivers/irqchip/irq-brcmstb-l2.c (ffff80001147561c)
Location: include/linux/irqdomain.h:331
Inline: True
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff80001067a14c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b4a8)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d7ac)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e6f0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff800010699b40)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b6900)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (ffff8000106b7e34)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf388)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d05d0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f75c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-aardvark.c (ffff8000107204cc)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010722024)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff8000107238a4)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010724efc)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff80001072592c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff8000107261c4)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010727520)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010727f70)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072a06c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072c72c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff80001147a11c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_host_init
```
```
In drivers/base/regmap/regmap-irq.c (ffff80001091e2b4)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffff800010933e90)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffff80001093895c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e598)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/lp8788-irq.c (ffff800010944194)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffff8000109485e8)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
```
```
In drivers/edac/altera_edac.c (ffff800010b16620)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
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
In drivers/irqchip/irq-al-fic.c (c1549778)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
```
```
In drivers/irqchip/exynos-combiner.c (c15499a4)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_init
```
```
In drivers/irqchip/irq-dw-apb-ictl.c (c154a080)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-dw-apb-ictl.c:dw_apb_ictl_init
```
```
In drivers/irqchip/irq-orion.c (c154a44c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_init
  - drivers/irqchip/irq-orion.c:orion_irq_init
```
```
In drivers/irqchip/irq-omap-intc.c (c154a9f4)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-omap-intc.c:intc_of_init
```
```
In drivers/irqchip/irq-armada-370-xp.c (c154d48c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_of_init
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fbe4)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/irqchip/irq-aspeed-i2c-ic.c (c154e6b4)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-i2c-ic.c:aspeed_i2c_ic_of_init
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c08232d0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083aaf0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852628)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init
```
```
In drivers/pinctrl/mediatek/mtk-eint.c (c0858da4)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
```
```
In drivers/gpio/gpio-mpc8xxx.c (c0869a70)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
```
```
In drivers/gpio/gpio-mvebu.c (c086a64c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/gpio/gpio-tegra.c (c08718a8)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a8364)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08ac638)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
```
In drivers/pci/controller/pcie-rcar.c (c08af504)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b03cc)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pcie-altera.c (c08b27fc)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b30c8)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b4e9c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_setup_irq
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c15524d8)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf734)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_host_init
```
```
In drivers/soc/dove/pmu.c (c158f3a8)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/soc/dove/pmu.c:dove_init_pmu_irq
```
```
In drivers/base/regmap/regmap-irq.c (c0a035d4)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (c0a16cec)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (c0a20db0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/tps65217.c (c0a233dc)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_probe
```
```
In drivers/mfd/twl6030-irq.c (c0a26f98)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/lp8788-irq.c (c0a2d28c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (c0a31744)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
```
```
In drivers/memory/omap-gpmc.c (c0c71594)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_probe
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
In arch/powerpc/sysdev/mpic.c (c000000001358afc)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
```
```
In arch/powerpc/platforms/powernv/opal-irqchip.c (c00000000135da8c)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
```
```
In drivers/irqchip/irq-al-fic.c (c0000000013a0d44)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
```
```
In drivers/pci/controller/pci-ftpci100.c (c000000000891484)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c000000000892290)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/base/regmap/regmap-irq.c (c0000000009c31a4)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (c0000000009d4d40)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (c0000000009df620)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e6a60)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/lp8788-irq.c (c0000000009edaf0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (c0000000009f3768)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/irqchip/irq-al-fic.c (ffffffe00002a9ba)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-al-fic.c:al_fic_init_dt
```
```
In drivers/irqchip/irq-sifive-plic.c (ffffffe00002abf6)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_init
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e6622)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e6fa6)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/base/regmap/regmap-irq.c (ffffffe00059d9a8)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a9b42)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffe0005ad696)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b250a)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/lp8788-irq.c (ffffffe0005b6caa)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffe0005ba5c6)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/base/regmap/regmap-irq.c (ffffffff816ee8aa)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff816fce30)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81701172)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
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
In drivers/base/regmap/regmap-irq.c (ffffffff816c8eea)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d0c40)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816d4f82)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
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
In drivers/base/regmap/regmap-irq.c (ffffffff8171bf8a)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff8172c590)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81730b52)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:331
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8173aaa0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff8173dd79)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
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
In drivers/base/regmap/regmap-irq.c (ffffffff817372ea)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
```
```
In drivers/mfd/arizona-irq.c (ffffffff817479d0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8174bf92)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irqdomain.h:331
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81755ee0)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/max8997-irq.c (ffffffff817591b9)
Location: include/linux/irqdomain.h:331
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_init
```
</details>
</li>
</ul>

## Differences
