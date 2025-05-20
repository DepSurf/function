# Function: <code>irq_set_nested_thread</code>

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
In drivers/gpio/gpiolib.c (ffffffff81424899)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8156bcd8)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8157b1ce)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff8157e38e)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815834de)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8158536d)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/tps65912-irq.c (ffffffff81586807)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/tps65912-irq.c:tps65912_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81588aa0)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8158de1e)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8158f96e)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff815910be)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81591aae)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81593f6e)
Location: include/linux/irq.h:583
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81595a4c)
Location: include/linux/irq.h:583
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
In drivers/gpio/gpiolib.c (ffffffff8146e5e9)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815c0c58)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815d020e)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff815d3675)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815d95de)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff815db450)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff815ddd7a)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:612
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff815e2cfe)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff815e47de)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff815e5ebe)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff815e685e)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff815e8e1e)
Location: include/linux/irq.h:612
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff815ea888)
Location: include/linux/irq.h:612
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
In drivers/gpio/gpiolib.c (ffffffff81490649)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815f0098)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815fce1e)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816003c5)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816062ce)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81608127)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8160aa0a)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:629
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8160fbae)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8161168e)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81612d6e)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816136ee)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81615c2e)
Location: include/linux/irq.h:629
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81617698)
Location: include/linux/irq.h:629
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
In drivers/gpio/gpiolib.c (ffffffff81499d39)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81604258)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81610b9e)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81614275)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8161a0ce)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8161bfae)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8161eb57)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:679
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81623c6e)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8162571e)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81626dfe)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8162772e)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81629b7e)
Location: include/linux/irq.h:679
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8162b588)
Location: include/linux/irq.h:679
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
In drivers/gpio/gpiolib.c (ffffffff814d8029)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8166c638)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8167941e)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff8167c915)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8168279e)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8168469e)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81687397)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:708
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8168c55e)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8168e00e)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8168f6ce)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8168fffe)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8169249e)
Location: include/linux/irq.h:708
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81693ec8)
Location: include/linux/irq.h:708
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
In drivers/gpio/gpiolib.c (ffffffff815075e2)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816a8098)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816b4c2e)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816b8365)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816be81e)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff816c0761)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816c33fd)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:710
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816c862e)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff816ca11e)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff816cb7ce)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816cc0fe)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff816ce59e)
Location: include/linux/irq.h:710
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816d0018)
Location: include/linux/irq.h:710
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
In drivers/gpio/gpiolib.c (ffffffff8151bb62)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8ce8)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816d612e)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d95a5)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816dfbee)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff816e1ba1)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff816e47ed)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:711
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816e9b2e)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff816eb69e)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff816ecd7e)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816ed6be)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff816efbbe)
Location: include/linux/irq.h:711
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff816f1638)
Location: include/linux/irq.h:711
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
In drivers/gpio/gpiolib.c (ffffffff81549ea7)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8170409a)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81711052)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81714cea)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817192f2)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8171b25e)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8171de7a)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:724
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817232b2)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81724e02)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff817264c2)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81726e02)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81728f52)
Location: include/linux/irq.h:724
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8172abb2)
Location: include/linux/irq.h:724
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
In drivers/gpio/gpiolib.c (ffffffff8156b047)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817283ea)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81735352)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81738ffa)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8173d5e2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8173f54e)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8174214a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:742
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81747552)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff817490b2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8174a782)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8174b0d2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8174d1a2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8174edb2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void irq_set_nested_thread(unsigned int irq, bool nest);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160e229)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817e464a)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817f26a2)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff817f665a)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817faf72)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff817fcfee)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817ffd66)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
Direct callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:772
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81805252)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff818071c2)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff818086d2)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81809152)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8180b272)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8180d47e)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff817ff950-ffffffff817ff975: irq_set_nested_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void irq_set_nested_thread(unsigned int irq, bool nest);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81634af9)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817f94aa)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81806c62)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81809382)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8180d2c2)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8180ea6e)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81811006)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
Direct callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:785
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81815b42)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81817332)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81818622)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81819002)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8181a9f2)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8181c40e)
Location: include/linux/irq.h:785
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff81810bf0-ffffffff81810c15: irq_set_nested_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void irq_set_nested_thread(unsigned int irq, bool nest);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81618579)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817dd72a)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817eb892)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff817edf22)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817f1a92)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff817f329e)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff817f5786)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
Direct callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:787
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817fa202)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff817fb7a2)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff817fca62)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff817fd422)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff817fe112)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff817ff7ce)
Location: include/linux/irq.h:787
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff817f5370-ffffffff817f5395: irq_set_nested_thread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void irq_set_nested_thread(unsigned int irq, bool nest);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81687815)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8186904a)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81878412)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8187a192)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8187c1db)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8187e916)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
Direct callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:789
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff818836f2)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81884d52)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff818863f2)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81887172)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81887fc2)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81889ec6)
Location: include/linux/irq.h:789
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
**Symbols:**

```
ffffffff8187e4d0-ffffffff8187e4f5: irq_set_nested_thread (STB_LOCAL)
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
In drivers/gpio/gpiolib.c (ffffffff817a4aa3)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b1c78)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff819c07be)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff819c292e)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff819c4b6b)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff819c6e38)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:793
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff819cc1de)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff819cda4e)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff819cf1de)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff819d00be)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff819d105e)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff819d3175)
Location: include/linux/irq.h:793
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
In drivers/gpio/gpiolib.c (ffffffff818bc7c3)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b26bf8)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b36ade)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b38b4e)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81b3b93b)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b3d9f7)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:795
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b43f6e)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81b4646e)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b47fee)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81b490de)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a4ee)
Location: include/linux/irq.h:795
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81b4d563)
Location: include/linux/irq.h:795
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
In drivers/gpio/gpiolib.c (ffffffff818ff933)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b77138)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b89c4e)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b8bfbe)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81b8ed29)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81b90e87)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:808
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b9734e)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81b9983e)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b9b43e)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81b9c52e)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9d92e)
Location: include/linux/irq.h:808
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81ba09d3)
Location: include/linux/irq.h:808
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
In drivers/gpio/gpiolib.c (ffffffff81947123)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcaf08)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81bddb4e)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81bdfebe)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81be2c49)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be4e27)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:790
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81beb31e)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81bed7ee)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81bef3fe)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81bf051e)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf191e)
Location: include/linux/irq.h:790
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81bf4b33)
Location: include/linux/irq.h:790
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
In drivers/gpio/gpiolib.c (ffff8000106be914)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffff80001091d508)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffff80001092c738)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (ffff80001092f4e4)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (ffff800010930bec)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffff800010933bb4)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffff8000109388a0)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffff80001093a980)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffff80001093da74)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e2c4)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (ffff8000109440fc)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffff800010946c10)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffff8000109483b4)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffff800010949034)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffff80001094b678)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffff80001094dee8)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In drivers/gpio/gpiolib.c (c085e704)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (c0a029a8)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (c0a0b314)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (c0a10b70)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (c0a11ecc)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (c0a16ba8)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (c0a20d04)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (c0a22b9c)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/tps65217.c (c0a22f40)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_irq_map
```
```
In drivers/mfd/twl4030-irq.c (c0a264dc)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (c0a26d78)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (c0a2d214)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (c0a2fe54)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (c0a31538)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (c0a3207c)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (c0a341ac)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (c0a37f60)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
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
In drivers/gpio/gpiolib.c (c00000000083b940)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (c0000000009c208c)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (c0000000009cbb84)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (c0000000009cf174)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (c0000000009d0d14)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (c0000000009d4b90)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (c0000000009df514)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (c0000000009e1fa4)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (c0000000009e5b30)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e6788)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (c0000000009eda44)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (c0000000009f1504)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (c0000000009f3444)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (c0000000009f44d4)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (c0000000009f71a4)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (c0000000009fa628)
Location: include/linux/irq.h:742
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
In drivers/gpio/gpiolib.c (ffffffe0004a57fc)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffe00059cd0a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffe0005a3a24)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (ffffffe0005a5ec0)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (ffffffe0005a7118)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a9a0e)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffe0005ad5e6)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffe0005af37a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffe0005b1c26)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b2312)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (ffffffe0005b6c38)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffe0005b8eba)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffe0005ba3b8)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffe0005baed6)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffe0005bce3a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffe0005beeda)
Location: include/linux/irq.h:742
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
In drivers/gpio/gpiolib.c (ffffffff81560807)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816ee1ca)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816fcd5a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817010c2)
Location: include/linux/irq.h:742
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
In drivers/gpio/gpiolib.c (ffffffff81551657)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c880a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d0b6a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816d4ed2)
Location: include/linux/irq.h:742
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
In drivers/gpio/gpiolib.c (ffffffff8155f377)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8171b8aa)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81728812)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff8172c4ba)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81730aa2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff81732a0e)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff8173560a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:742
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8173aa12)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8173c572)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8173dc42)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8173e592)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81740662)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff81742272)
Location: include/linux/irq.h:742
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
In drivers/gpio/gpiolib.c (ffffffff815791f7)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmap
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81736c0a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81743c52)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff817478fa)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8174bee2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/wm8350-irq.c (ffffffff8174de4e)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81750a4a)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:742
Inline: False
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81755e52)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff817579b2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81759082)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff817599d2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8175baa2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/mfd/rc5t583-irq.c (ffffffff8175d6b2)
Location: include/linux/irq.h:742
Inline: True
Inline callers:
  - drivers/mfd/rc5t583-irq.c:rc5t583_irq_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
