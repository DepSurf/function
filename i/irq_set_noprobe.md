# Function: <code>irq_set_noprobe</code>

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
In drivers/gpio/gpiolib.c (ffffffff81425180)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81fa6c08)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8156bce6)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8157b1dc)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff8157e39c)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815834ec)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:563
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8158de2c)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8158f97c)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff815910cc)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81591abc)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81593f7c)
Location: include/linux/irq.h:563
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff8146f080)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81fd3025)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815c0c66)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815d021c)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff815d3683)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff815d95ec)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:592
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff815e2d0c)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff815e47ec)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff815e5ecc)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff815e686c)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff815e8e2c)
Location: include/linux/irq.h:592
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff81491097)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff820109a5)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815f00a6)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815fce2c)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816003d3)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816062dc)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:609
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8160fbbc)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8161169c)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81612d7c)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816136fc)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81615c3c)
Location: include/linux/irq.h:609
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff8149ab57)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff820f2499)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81604266)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81610bac)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81614283)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8161a0dc)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:659
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81623c7c)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8162572c)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81626e0c)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8162773c)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81629b8c)
Location: include/linux/irq.h:659
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff814d9064)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff826fbc92)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8166c646)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8167942c)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff8167c923)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816827ac)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:688
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8168c56c)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8168e01c)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8168f6dc)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8169000c)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff816924ac)
Location: include/linux/irq.h:688
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff815081d5)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff82725fd4)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816a80a6)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816b4c3c)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816b8373)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816be82c)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:690
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816c863c)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff816ca12c)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff816cb7dc)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816cc10c)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff816ce5ac)
Location: include/linux/irq.h:690
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff8151cb15)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff828de1aa)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8cf6)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816d613c)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d95b3)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816dfbfc)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:691
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816e9b3c)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff816eb6ac)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff816ecd8c)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff816ed6cc)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff816efbcc)
Location: include/linux/irq.h:691
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff8154add8)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff828f8ab3)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817040a9)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81711061)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81714cf9)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81719301)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:704
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817232c1)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81724e11)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff817264d1)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81726e11)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81728f61)
Location: include/linux/irq.h:704
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff8156bf18)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff829019b4)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817283f9)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81735361)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81739009)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8173d5f1)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:722
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81747561)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff817490c1)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8174a791)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8174b0e1)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8174d1b1)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff8161011c)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff82d18bbb)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817e4667)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817f26b1)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff817f6669)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817faf81)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:752
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81805261)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff818071d1)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff818086e1)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81809161)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8180b281)
Location: include/linux/irq.h:752
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff816365e4)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff83006834)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817f94c7)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81806c71)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81809391)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8180d2d1)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:765
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81815b51)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81817341)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81818631)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81819011)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8181aa01)
Location: include/linux/irq.h:765
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff816196a6)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8321141c)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817dd747)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817eb8a1)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff817edf31)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817f1aa1)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:767
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817fa211)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff817fb7b1)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff817fca71)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff817fd431)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff817fe121)
Location: include/linux/irq.h:767
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff816889a7)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff832fa4df)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81869067)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81878421)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8187a1a1)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:769
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81883701)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81884d61)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81886401)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81887181)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81887fd1)
Location: include/linux/irq.h:769
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff817a5997)
Location: include/linux/irq.h:773
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff834b2d95)
Location: include/linux/irq.h:773
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b1c95)
Location: include/linux/irq.h:773
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff819c07cc)
Location: include/linux/irq.h:773
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff819c293c)
Location: include/linux/irq.h:773
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:773
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff819cc1ec)
Location: include/linux/irq.h:773
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff819cda5c)
Location: include/linux/irq.h:773
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff819cf1ec)
Location: include/linux/irq.h:773
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff819d00cc)
Location: include/linux/irq.h:773
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff819d106c)
Location: include/linux/irq.h:773
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff818be557)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff83eed67c)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b26c15)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b36aec)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b38b5c)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:775
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b43f7c)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81b4647c)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b47ffc)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81b490ec)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a4fc)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff819016e7)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8371332c)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b77155)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b89c5c)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81b8bfcc)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:788
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b9735c)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81b9984c)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81b9b44c)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81b9c53c)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9d93c)
Location: include/linux/irq.h:788
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff81948fe7)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff83946d58)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcaf25)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81bddb5c)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81bdfecc)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:770
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81beb32c)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff81bed7fc)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81bef40c)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff81bf052c)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf192c)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/irqchip/qcom-irq-combiner.c (ffff80001067bd18)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_irq_map
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069c528)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/gpio/gpiolib.c (ffff8000106bf244)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffff800011493ab8)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffff80001091d524)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffff80001092c748)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (ffff80001092f4f4)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (ffff800010930bfc)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffff800010933bc4)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffff8000109388b0)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e2e0)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (ffff80001094410c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffff800010946c20)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffff8000109483c4)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffff800010949044)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffff80001094b688)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
```
In drivers/edac/altera_edac.c (ffff800010b16044)
Location: include/linux/irq.h:722
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
In drivers/pinctrl/pinctrl-single.c (c083f2f0)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/gpio/gpiolib.c (c085f9f8)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (c0a029c4)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (c0a0b324)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (c0a10b80)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (c0a11edc)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (c0a16bb8)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (c0a20d14)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/tps65217.c (c0a22f5c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_irq_map
```
```
In drivers/mfd/twl6030-irq.c (c0a26d94)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (c0a2d224)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (c0a2fe64)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (c0a31548)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (c0a3208c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (c0a341bc)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/pinctrl/pinctrl-single.c (c000000000833d78)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/gpio/gpiolib.c (c00000000083cec8)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (c0000000009c20b4)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (c0000000009cbb9c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (c0000000009cf18c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (c0000000009d0d2c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (c0000000009d4ba8)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (c0000000009df52c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e67b0)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (c0000000009eda5c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (c0000000009f151c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (c0000000009f345c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (c0000000009f44ec)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (c0000000009f71bc)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/irqchip/irq-sifive-plic.c (ffffffe00049576c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/irqchip/irq-sifive-plic.c:plic_irqdomain_map
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0778)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a683e)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffe00059cd18)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffe0005a3a32)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/stmpe.c (ffffffe0005a5ece)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_irq_map
```
```
In drivers/mfd/tc3589x.c (ffffffe0005a7126)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a9a1c)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffe0005ad5f4)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b2320)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
```
In drivers/mfd/lp8788-irq.c (ffffffe0005b6c46)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffe0005b8ec8)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffe0005ba3c6)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffe0005baee4)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffe0005bce48)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff815616d8)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff828e919b)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816ee1d9)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816fcd69)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff817010d1)
Location: include/linux/irq.h:722
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
In drivers/gpio/gpiolib.c (ffffffff81552528)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8819)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d0b79)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff816d4ee1)
Location: include/linux/irq.h:722
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
In drivers/gpio/gpiolib.c (ffffffff81560248)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff828fccd7)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8171b8b9)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81728821)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff8172c4c9)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff81730ab1)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:722
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8173aa21)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff8173c581)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff8173dc51)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff8173e5a1)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff81740671)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
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
In drivers/gpio/gpiolib.c (ffffffff8157a0b8)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff829029d6)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81736c19)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81743c61)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_irq_domain_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81747909)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
```
In drivers/mfd/wm831x-irq.c (ffffffff8174bef1)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/wm831x-irq.c:wm831x_irq_map
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:722
Inline: True
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81755e61)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_map
```
```
In drivers/mfd/max8925-core.c (ffffffff817579c1)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8925-core.c:max8925_irq_domain_map
```
```
In drivers/mfd/max8997-irq.c (ffffffff81759091)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8997-irq.c:max8997_irq_domain_map
```
```
In drivers/mfd/max8998-irq.c (ffffffff817599e1)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_domain_map
```
```
In drivers/mfd/tps6586x.c (ffffffff8175bab1)
Location: include/linux/irq.h:722
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_map
```
</details>
</li>
</ul>

## Differences
