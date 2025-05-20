# Function: <code>i2c_set_clientdata</code>

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
In drivers/gpio/gpio-sx150x.c (ffffffff8142b677)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8157b00c)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8157bb70)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff8158223c)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81583fc5)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8158551c)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65217.c (ffffffff81585613)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81585a5e)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81586aba)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps80031.c (ffffffff815871b6)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81589d79)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8158bdd9)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff8158c29a)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8158d67f)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8158dbf6)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8158e1d3)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8158e727)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8158e95f)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8158ee68)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8158f308)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81590245)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81590b22)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81591702)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff81592a6a)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81593299)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81593b93)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81594044)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8159482e)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81594d4c)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81595152)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff81595cf1)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff81596457)
Location: include/linux/i2c.h:250
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
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
In drivers/gpio/gpio-sx150x.c (ffffffff81476713)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815cfff8)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815d0a8d)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff815d831d)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff815da089)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff815db605)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff815db78a)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff815dbc02)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps80031.c (ffffffff815dc1e1)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff815deb1c)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff815e1035)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff815e14f1)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff815e2885)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff815e2adc)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff815e30b3)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff815e35da)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff815e3819)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff815e3d22)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff815e4182)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff815e50c2)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff815e591c)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff815e64dc)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff815e78b9)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff815e80e4)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff815e8a2c)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff815e8ef4)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:258
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff815e9bf2)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff815e9fe2)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff815eaaec)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff815eb257)
Location: include/linux/i2c.h:258
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8148b053)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815fcc05)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815fd7e5)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff8160500d)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81606d79)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff816082d5)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8160845a)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff816088d2)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps80031.c (ffffffff81608eb1)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8160b7ac)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8160dcd5)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff8160e191)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8160f735)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8160f98c)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8160ff63)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8161048a)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff816106c9)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81610bd2)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81611032)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81611f72)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff816127cc)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8161337c)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff816146c9)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81614ef4)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8161583c)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81615d04)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:267
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff81616a02)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81616df2)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816178fc)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff81618067)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81700f73)
Location: include/linux/i2c.h:267
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81494983)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8161099c)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816115eb)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81618edd)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8161aba8)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8161c185)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8161c30a)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8161c742)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8161cd1e)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8161f8bc)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81621dd5)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81622281)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff816237f5)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81623a4c)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81624013)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8162452a)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81624779)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81624c82)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff816250d2)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81625fe2)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81626868)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816273d8)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff816286b9)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81628ee4)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816297a6)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81629c4f)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:273
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff8162a93f)
Location: include/linux/i2c.h:273
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8162acf2)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8162b814)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff8162bf5f)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817167c3)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814d0c39)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8167921c)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81679e6e)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff8168157d)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81683288)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81684875)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff816849fa)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81684e32)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffffffff81684f87)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8168555e)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816880fc)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8168a605)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff8168aad1)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8168c0e5)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8168c33c)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8168c903)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8168ce1a)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8168d069)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8168d572)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8168d9c2)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8168e8d4)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff8168f138)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8168fca8)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff81690fc9)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816917fa)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816920c6)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8169256f)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:273
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff8169327f)
Location: include/linux/i2c.h:273
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff81693632)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff81694154)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff816948bf)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81694f11)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817879c8)
Location: include/linux/i2c.h:273
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81501b1e)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816b4cfe)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816b591c)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff816bd5d6)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff816bf304)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff816c08ff)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff816c0a9c)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff816c0ecf)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffffffff816c1037)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff816c160e)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816c424d)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff816c66f9)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff816c6b89)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff816c81af)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff816c83f9)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff816c89de)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff816c8f17)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff816c9160)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff816c966b)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff816c9abb)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816caaa2)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff816cb244)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816cbdb1)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff816cd0f1)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816cd90f)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816ce20f)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff816ce67f)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:361
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff816cf36c)
Location: include/linux/i2c.h:361
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff816cf75a)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816d0294)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff816d098d)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff816d0fe0)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8a7e)
Location: include/linux/i2c.h:361
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815165ee)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816d5f2e)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816d6b7c)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff816de826)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff816e06d4)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff816e1d3f)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff816e1edc)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff816e230f)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffffffff816e2477)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff816e2a4e)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816e563d)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff816e7af9)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff816e7fa9)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff816e96af)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff816e98f9)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff816e9f3e)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff816ea45c)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff816ea6e0)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff816eabeb)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff816eb03b)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816ebf62)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff816ec7e4)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816ed361)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff816ee6b1)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816eeecf)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816ef82f)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff816efc9f)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:360
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff816f098c)
Location: include/linux/i2c.h:360
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff816f0d7a)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816f18b4)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff816f202d)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff816f2683)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f011e)
Location: include/linux/i2c.h:360
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8154480e)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81710ecc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817122c2)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/wm8400-core.c (ffffffff8171800d)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81719e40)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8171b3fc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8171b57b)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8171b9b2)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffffffff8171bb17)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8171bfbb)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8171ed6c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff817212cc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81721789)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81722e11)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8172305d)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff817236ec)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81723bbb)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81723e3c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8172432a)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8172478e)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817256fc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81725f64)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81726ae4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff81727c2d)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8172855e)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81728fe7)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff817293cf)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff8172a04d)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8172a3da)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8172af37)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff8172b5bf)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8172bbe1)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81830580)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815656ee)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817351bc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817365c2)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/wm8400-core.c (ffffffff8173c31d)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8173e130)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8173f6cc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8173f84b)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8173fc82)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffffffff8173fde7)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff81740292)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8174303c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8174556c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81745a29)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff817470b1)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff817472fd)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8174798c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81747e5b)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff817480dc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff817485ca)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81748a3e)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817499ac)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff8174a224)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8174ada4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff8174bedd)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8174c7ae)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8174d224)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8174d60f)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff8174e24d)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8174e5da)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8174f137)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff8174f80f)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8174fe31)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861eb0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff816078cf)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817f277c)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817f3896)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/wm8400-core.c (ffffffff817f9c23)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff817fbac0)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff817fd16c)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff817fd2eb)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff817fd722)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffffffff817fd887)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff817fdd39)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff818013fc)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8180324c)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff818036a8)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81804d31)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81804ffd)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8180568c)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81805bcb)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81805f4c)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
```
```
In drivers/mfd/max77693.c (ffffffff818063da)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8180685e)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff818078ec)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81807f84)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81808d14)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff81809f6a)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8180a7fe)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8180b5cb)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8180b80f)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:359
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff8180c79d)
Location: include/linux/i2c.h:359
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8180cc4c)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8180d807)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff8180df5f)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8180e581)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819356e6)
Location: include/linux/i2c.h:359
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8162c07d)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81806d3c)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff818074f8)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/wm8400-core.c (ffffffff8180c713)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8180dbd0)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8180ebac)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8180ed0b)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8180f052)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffffffff8180f187)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8180f5b9)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8181234c)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/da903x.c (ffffffff818143f8)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81815691)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8181591d)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81815f3c)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8181636c)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8181676c)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
```
```
In drivers/mfd/max77693.c (ffffffff818169fa)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81816b5e)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8181792c)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81817f44)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81818be4)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff81819baa)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8181a12e)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81c1500e)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8181abdf)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:356
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff8181b91d)
Location: include/linux/i2c.h:356
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8181bd5c)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8181c587)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff8181cc6f)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8181d141)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c756)
Location: include/linux/i2c.h:356
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8160fc9c)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817eb96c)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec118)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/wm8400-core.c (ffffffff817f0f9d)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff817f23b4)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff817f33df)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff817f353b)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff817f3882)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffffffff817f39b7)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff817f3df8)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff817f6a8c)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/da903x.c (ffffffff817f8ad8)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff817f9d6f)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff817f9fea)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff817fa5f0)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff817fa98d)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff817fabd1)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff817fae5a)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff817fafbe)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817fbd9c)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff817fc384)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff817fd004)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff817fd84e)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81c06c98)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff817fe31f)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:362
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff817fed0d)
Location: include/linux/i2c.h:362
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff817ff0be)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff817ff94c)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff8180000e)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff818004d1)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191fffa)
Location: include/linux/i2c.h:362
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8167ed2c)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff818784ec)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81878ce8)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/wm8400-core.c (ffffffff8187962d)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8187b004)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8187c32f)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8187c45b)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8187c802)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8187ccba)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8187fd9c)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/da903x.c (ffffffff81881f32)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8188321f)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8188349a)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81883ae0)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81883e7d)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff818840c1)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8188434a)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff818844ae)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8188534c)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81885939)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81886ae4)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff818875ee)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81d0a29d)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff818881cf)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:363
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff81888cad)
Location: include/linux/i2c.h:363
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff81888ebe)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/as3711.c (ffffffff8188a3fe)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8188a8d1)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2c9a)
Location: include/linux/i2c.h:363
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8179a82c)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff819c089d)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff819c11eb)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/wm8400-core.c (ffffffff819c1c3c)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff819c3844)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff819c4ccf)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff819c4e26)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff819c5202)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/twl6040.c (ffffffff819c839c)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/da903x.c (ffffffff819ca7c3)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff819cbcaf)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff819cbf1a)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff819cc63d)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff819cca2d)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff819ccd24)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff819ccfc1)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff819cd155)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff819ce0cd)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff819ce719)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff819cf9c4)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff819d05af)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81ed26f4)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff819d12bf)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:376
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff819d1e3c)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff819d215e)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/as3711.c (ffffffff819d373c)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff819d3c3a)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b230e8)
Location: include/linux/i2c.h:376
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818b10fc)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b36bcd)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81b37550)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81b39d5c)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81b3bafb)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81b3be3b)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81b3c1e2)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81b3efbc)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/da903x.c (ffffffff81b41cce)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81b43904)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81b43bfa)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81b44489)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81b449a3)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81b44f1f)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81b454ca)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81b4597b)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b46d2d)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81b47410)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81b4890b)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81b497e6)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a7d8)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81b4abee)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:377
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff81b4b993)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81b4c26e)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/as3711.c (ffffffff81b4dc1b)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81b4df1c)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81b4e329)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb597b)
Location: include/linux/i2c.h:377
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818f4180)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b8a04d)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81b8a9c0)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81b8d1bc)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81b8ef1b)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81b8f25b)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81b8f632)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81b9243c)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/da903x.c (ffffffff81b95048)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81b96ca4)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81b96faa)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81b97889)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81b97d53)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81b982cf)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81b9889a)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81b98d4b)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b9a0fd)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81b9a7e0)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81b9bd6b)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81b9cc33)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9dc1b)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81b9e02f)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81b9e999)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81b9ede3)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81b9f6be)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/as3711.c (ffffffff81ba108b)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81ba13dc)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81ba1789)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1cfee)
Location: include/linux/i2c.h:383
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8193b9a6)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81bddf4d)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81bde8c0)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81be10e2)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81be2e3b)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81be317b)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81be3552)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81be63dc)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/da903x.c (ffffffff81be9018)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81beac74)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81beaf7a)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81beb859)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81bebd23)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81bec290)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81bec84a)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81beccfb)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81bee0ad)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81bee782)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81befd1c)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81bf0c23)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf1c0b)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81bf215f)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81bf2af9)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81bf2f43)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81bf381e)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/as3711.c (ffffffff81bf521b)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81bf556c)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81bf5919)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2d3b)
Location: include/linux/i2c.h:374
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffff80001069ef78)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffff80001092d1a0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092df20)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/tc3589x.c (ffff800010930cc4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/wm8400-core.c (ffff800010937324)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffff800010939424)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffff80001093ab2c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffff80001093ace4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffff80001093b300)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffff80001093b490)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffff80001093ba24)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffff80001093f18c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffff800010941c8c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffff800010942260)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffff800010943b10)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffff800010943e3c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffff8000109445c8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffff800010944aa4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffff800010944d8c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (ffff8000109459ac)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (ffff800010945da8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (ffff800010946108)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffff800010946550)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffff80001094741c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffff800010947dcc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffff800010948bb0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffff80001094a14c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffff80001094aca0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffff80001094b938)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffff80001094bcd4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/palmas.c (ffff80001094cc88)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffff80001094d588)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffff80001094e1d8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffff80001094f19c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (ffff80001094f434)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (c0841840)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (c0a0bc24)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (c0a0f978)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/tc3589x.c (c0a11f9c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/wm8400-core.c (c0a1f518)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (c0a217b0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (c0a22d28)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65217.c (c0a23290)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_probe
```
```
In drivers/mfd/tps65910.c (c0a23658)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (c0a23cb8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps80031.c (c0a242ec)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (c0a288a8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (c0a2accc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (c0a2b278)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (c0a2cbe0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (c0a2cf98)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (c0a2d7c0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (c0a2dd04)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (c0a2dfa0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (c0a2ec14)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (c0a2f000)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (c0a2f30c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (c0a2f788)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (c0a3076c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (c0a30fb0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (c0a31c4c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (c0a3320c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (c0a33930)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (c0a3431c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (c0a35f58)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/palmas.c (c0a36df8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (c0a373d0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (c0a38238)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (c0a391f8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (c0a394b8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/rtc/rtc-pcf8523.c (c0b8d330)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/rtc/rtc-pcf8523.c:pcf8523_probe
```
```
In sound/soc/codecs/sgtl5000.c (c0cbe770)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (c00000000083722c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (c0000000009cc6f8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (c0000000009cd830)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/tc3589x.c (c0000000009d0e44)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/wm8400-core.c (c0000000009dd7e4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (c0000000009e0434)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (c0000000009e21e0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (c0000000009e23e0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (c0000000009e2bcc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps80031.c (c0000000009e3288)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (c0000000009e8228)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (c0000000009ea7b4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (c0000000009eafa8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (c0000000009ed180)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (c0000000009ed6a8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (c0000000009ee1ec)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (c0000000009ee834)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (c0000000009eebd4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (c0000000009efcd0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (c0000000009f01d4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (c0000000009f0644)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (c0000000009f0c48)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (c0000000009f2140)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (c0000000009f2d3c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (c0000000009f3f54)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (c0000000009f5bfc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (c0000000009f65ec)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (c0000000009f7578)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (c0000000009f79d4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/palmas.c (c0000000009f8ef4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (c0000000009f9a94)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (c0000000009fa9f0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (c0000000009fba48)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (c0000000009fbdf4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffe0004a2c60)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffe0005a4294)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4d38)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/tc3589x.c (ffffffe0005a71e2)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffe0005ac3da)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffe0005ae066)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffe0005af4f2)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffe0005af65a)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffe0005afbc6)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps80031.c (ffffffe0005b0088)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffe0005b2e72)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffe0005b4e7c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffe0005b533c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffe0005b66ca)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffe0005b69fa)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffe0005b7004)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffe0005b74a0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffe0005b76c4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (ffffffe0005b7f0e)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (ffffffe0005b81f0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffe0005b84b4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffe0005b87fa)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffe0005b961e)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffe0005b9e98)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffe0005baaf8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffe0005bbec2)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffe0005bc542)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffe0005bcfee)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffe0005bd2fc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffe0005bdeb6)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffe0005be6b6)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffe0005bf0d2)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffe0005bfaf8)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (ffffffe0005bfcca)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81559a1e)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8172867c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81729a82)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/wm8400-core.c (ffffffff8172f7dd)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff817315f0)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81732b8c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81732d0b)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81733142)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffffffff817332a7)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff81733752)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff817364fc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81738a2c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81738ee9)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8173a571)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8173a7bd)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8173ae4c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8173b31b)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8173b59c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8173ba8a)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8173befe)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8173ce6c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff8173d6e4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8173e264)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff8173f39d)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8173fc6e)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff817406e4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81740acf)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff8174170d)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff81741a9a)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff817425f7)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff81742ccf)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff817432f1)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81856040)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
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
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815738ae)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81743abc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81744ec2)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/wm8400-core.c (ffffffff8174ac1d)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8174ca30)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8174dfcc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8174e14b)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8174e582)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps68470.c (ffffffff8174e6e7)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8174eb92)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8175193c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81753e6c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81754329)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff817559b1)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81755bfd)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8175628c)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8175675b)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff817569dc)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81756eca)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8175733e)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817582ac)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81758b24)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff817596a4)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff8175a7dd)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8175b0ae)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8175bb24)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8175bf0f)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/palmas.c (ffffffff8175cb4d)
Location: include/linux/i2c.h:355
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8175ceda)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8175da37)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/as3711.c (ffffffff8175e11f)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8175e741)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81871170)
Location: include/linux/i2c.h:355
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
</details>
</li>
</ul>

## Differences
