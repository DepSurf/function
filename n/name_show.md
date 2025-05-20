# Function: <code>name_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff814d8b00)
Location: drivers/regulator/core.c:373
Inline: False
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff816764f0)
Location: drivers/rtc/rtc-sysfs.c:28
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff8167dd70)
Location: drivers/i2c/i2c-dev.c:100
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff81688700)
Location: drivers/thermal/thermal_hwmon.c:62
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff816eda40)
Location: drivers/devfreq/devfreq-event.c:441
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff816ee260)
Location: drivers/extcon/extcon.c:210
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_update_state
```
```
In drivers/powercap/powercap_sys.c (ffffffff816f1c80)
Location: drivers/powercap/powercap_sys.c:359
Inline: False
```
```
In net/rfkill/core.c (ffffffff81810e20)
Location: net/rfkill/core.c:585
Inline: False
```
**Symbols:**

```
ffffffff814d8b00-ffffffff814d8b50: name_show (STB_LOCAL)
ffffffff816764f0-ffffffff81676516: name_show (STB_LOCAL)
ffffffff8167dd70-ffffffff8167ddbb: name_show (STB_LOCAL)
ffffffff81688700-ffffffff81688726: name_show (STB_LOCAL)
ffffffff816eda40-ffffffff816eda79: name_show (STB_LOCAL)
ffffffff816ee260-ffffffff816ee289: name_show (STB_LOCAL)
ffffffff816f1c80-ffffffff816f1ca3: name_show (STB_LOCAL)
ffffffff81810e20-ffffffff81810e46: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/core.c (ffffffff815298b0)
Location: drivers/regulator/core.c:349
Inline: False
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff816d6b10)
Location: drivers/rtc/rtc-sysfs.c:28
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff816df010)
Location: drivers/i2c/i2c-dev.c:102
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff816e9400)
Location: drivers/thermal/thermal_hwmon.c:62
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81752950)
Location: drivers/devfreq/devfreq-event.c:440
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff81753a9a)
Location: drivers/extcon/extcon.c:198
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_update_state
```
```
In drivers/powercap/powercap_sys.c (ffffffff81756ca0)
Location: drivers/powercap/powercap_sys.c:359
Inline: False
```
```
In net/rfkill/core.c (ffffffff81883d30)
Location: net/rfkill/core.c:607
Inline: False
```
**Symbols:**

```
ffffffff815298b0-ffffffff81529900: name_show (STB_LOCAL)
ffffffff816d6b10-ffffffff816d6b36: name_show (STB_LOCAL)
ffffffff816df010-ffffffff816df05b: name_show (STB_LOCAL)
ffffffff816e9400-ffffffff816e9426: name_show (STB_LOCAL)
ffffffff81752950-ffffffff81752989: name_show (STB_LOCAL)
ffffffff81753390-ffffffff817533b9: name_show (STB_LOCAL)
ffffffff81756ca0-ffffffff81756cc3: name_show (STB_LOCAL)
ffffffff81883d30-ffffffff81883d56: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5f00)
Location: kernel/irq/irqdesc.c:203
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81555dc0)
Location: drivers/regulator/core.c:350
Inline: False
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff817067f0)
Location: drivers/rtc/rtc-sysfs.c:28
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff8170f3f0)
Location: drivers/i2c/i2c-dev.c:102
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff8171a260)
Location: drivers/thermal/thermal_hwmon.c:62
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8177e740)
Location: drivers/devfreq/devfreq-event.c:440
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8177f517)
Location: drivers/extcon/extcon.c:384
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff81783280)
Location: drivers/powercap/powercap_sys.c:359
Inline: False
```
```
In net/rfkill/core.c (ffffffff818b85d0)
Location: net/rfkill/core.c:607
Inline: False
```
**Symbols:**

```
ffffffff810e5f00-ffffffff810e5f5e: name_show (STB_LOCAL)
ffffffff81555dc0-ffffffff81555e10: name_show (STB_LOCAL)
ffffffff817067f0-ffffffff81706816: name_show (STB_LOCAL)
ffffffff8170f3f0-ffffffff8170f43b: name_show (STB_LOCAL)
ffffffff8171a260-ffffffff8171a286: name_show (STB_LOCAL)
ffffffff8177e740-ffffffff8177e779: name_show (STB_LOCAL)
ffffffff8177f340-ffffffff8177f369: name_show (STB_LOCAL)
ffffffff81783280-ffffffff817832a3: name_show (STB_LOCAL)
ffffffff818b85d0-ffffffff818b85f6: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5550)
Location: kernel/irq/irqdesc.c:215
Inline: False
```
```
In drivers/regulator/core.c (ffffffff8156a380)
Location: drivers/regulator/core.c:350
Inline: False
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8171c7b0)
Location: drivers/rtc/rtc-sysfs.c:28
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff817253b0)
Location: drivers/i2c/i2c-dev.c:102
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff8172c120)
Location: drivers/hwmon/hwmon.c:66
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff81732530)
Location: drivers/thermal/thermal_hwmon.c:62
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8179d020)
Location: drivers/devfreq/devfreq-event.c:440
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8179e011)
Location: drivers/extcon/extcon.c:387
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff817a2040)
Location: drivers/powercap/powercap_sys.c:359
Inline: False
```
```
In net/rfkill/core.c (ffffffff818def20)
Location: net/rfkill/core.c:665
Inline: False
```
**Symbols:**

```
ffffffff810e5550-ffffffff810e55ae: name_show (STB_LOCAL)
ffffffff8156a380-ffffffff8156a3d0: name_show (STB_LOCAL)
ffffffff8171c7b0-ffffffff8171c7f0: name_show (STB_LOCAL)
ffffffff817253b0-ffffffff817253fb: name_show (STB_LOCAL)
ffffffff8172c120-ffffffff8172c143: name_show (STB_LOCAL)
ffffffff81732530-ffffffff81732556: name_show (STB_LOCAL)
ffffffff8179d020-ffffffff8179d059: name_show (STB_LOCAL)
ffffffff8179de00-ffffffff8179de29: name_show (STB_LOCAL)
ffffffff817a2040-ffffffff817a2063: name_show (STB_LOCAL)
ffffffff818def20-ffffffff818def46: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ed880)
Location: kernel/irq/irqdesc.c:213
Inline: False
```
```
In drivers/regulator/core.c (ffffffff815ce550)
Location: drivers/regulator/core.c:350
Inline: False
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8178da30)
Location: drivers/rtc/rtc-sysfs.c:28
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff81796840)
Location: drivers/i2c/i2c-dev.c:103
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff8179d8d0)
Location: drivers/hwmon/hwmon.c:66
Inline: False
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff817a36a0)
Location: drivers/thermal/thermal_hwmon.c:62
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81814150)
Location: drivers/devfreq/devfreq-event.c:440
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff81815171)
Location: drivers/extcon/extcon.c:375
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff81819180)
Location: drivers/powercap/powercap_sys.c:359
Inline: False
```
```
In net/rfkill/core.c (ffffffff81964cb0)
Location: net/rfkill/core.c:665
Inline: False
```
**Symbols:**

```
ffffffff810ed880-ffffffff810ed8de: name_show (STB_LOCAL)
ffffffff815ce550-ffffffff815ce5a0: name_show (STB_LOCAL)
ffffffff8178da30-ffffffff8178da70: name_show (STB_LOCAL)
ffffffff81796840-ffffffff8179688b: name_show (STB_LOCAL)
ffffffff8179d8d0-ffffffff8179d8f3: name_show (STB_LOCAL)
ffffffff817a36a0-ffffffff817a36c6: name_show (STB_LOCAL)
ffffffff81814150-ffffffff81814189: name_show (STB_LOCAL)
ffffffff81814f60-ffffffff81814f89: name_show (STB_LOCAL)
ffffffff81819180-ffffffff818191a3: name_show (STB_LOCAL)
ffffffff81964cb0-ffffffff81964cd6: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f5c50)
Location: kernel/irq/irqdesc.c:229
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81607330)
Location: drivers/regulator/core.c:420
Inline: False
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff817d0050)
Location: drivers/rtc/rtc-sysfs.c:28
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff817d9470)
Location: drivers/i2c/i2c-dev.c:103
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff817dead0)
Location: drivers/pps/sysfs.c:78
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff817e4e40)
Location: drivers/hwmon/hwmon.c:66
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8185e020)
Location: drivers/devfreq/devfreq-event.c:440
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8185f097)
Location: drivers/extcon/extcon.c:375
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff81863230)
Location: drivers/powercap/powercap_sys.c:359
Inline: False
```
```
In net/rfkill/core.c (ffffffff819be550)
Location: net/rfkill/core.c:679
Inline: False
```
**Symbols:**

```
ffffffff810f5c50-ffffffff810f5cae: name_show (STB_LOCAL)
ffffffff81607330-ffffffff81607380: name_show (STB_LOCAL)
ffffffff817d0050-ffffffff817d0090: name_show (STB_LOCAL)
ffffffff817d9470-ffffffff817d94bb: name_show (STB_LOCAL)
ffffffff817dead0-ffffffff817deaf6: name_show (STB_LOCAL)
ffffffff817e4e40-ffffffff817e4e63: name_show (STB_LOCAL)
ffffffff8185e020-ffffffff8185e059: name_show (STB_LOCAL)
ffffffff8185ee80-ffffffff8185eea9: name_show (STB_LOCAL)
ffffffff81863230-ffffffff81863253: name_show (STB_LOCAL)
ffffffff819be550-ffffffff819be576: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81101370)
Location: kernel/irq/irqdesc.c:229
Inline: False
```
```
In drivers/regulator/core.c (ffffffff816226e0)
Location: drivers/regulator/core.c:604
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff817f6fe0)
Location: drivers/rtc/sysfs.c:28
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff818008c0)
Location: drivers/i2c/i2c-dev.c:103
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81809f00)
Location: drivers/pps/sysfs.c:78
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff81810610)
Location: drivers/hwmon/hwmon.c:69
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8187da40)
Location: drivers/devfreq/devfreq-event.c:440
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8187ea37)
Location: drivers/extcon/extcon.c:375
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff818829c0)
Location: drivers/powercap/powercap_sys.c:359
Inline: False
```
```
In net/rfkill/core.c (ffffffff819f56f0)
Location: net/rfkill/core.c:681
Inline: False
```
**Symbols:**

```
ffffffff81101370-ffffffff811013ce: name_show (STB_LOCAL)
ffffffff816226e0-ffffffff81622730: name_show (STB_LOCAL)
ffffffff817f6fe0-ffffffff817f7020: name_show (STB_LOCAL)
ffffffff818008c0-ffffffff8180090b: name_show (STB_LOCAL)
ffffffff81809f00-ffffffff81809f26: name_show (STB_LOCAL)
ffffffff81810610-ffffffff81810633: name_show (STB_LOCAL)
ffffffff8187da40-ffffffff8187da79: name_show (STB_LOCAL)
ffffffff8187e820-ffffffff8187e849: name_show (STB_LOCAL)
ffffffff818829c0-ffffffff818829e3: name_show (STB_LOCAL)
ffffffff819f56f0-ffffffff819f5716: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81109b70)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffffffff816563c0)
Location: drivers/regulator/core.c:586
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff81837cf0)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff81841830)
Location: drivers/i2c/i2c-dev.c:95
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff8184bbb0)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff818526b0)
Location: drivers/hwmon/hwmon.c:66
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818c7fe0)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff818c9061)
Location: drivers/extcon/extcon.c:367
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff818cd040)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (ffffffff81a64de0)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
ffffffff81109b70-ffffffff81109bce: name_show (STB_LOCAL)
ffffffff816563c0-ffffffff81656405: name_show (STB_LOCAL)
ffffffff81837cf0-ffffffff81837d32: name_show (STB_LOCAL)
ffffffff81841830-ffffffff8184187d: name_show (STB_LOCAL)
ffffffff8184bbb0-ffffffff8184bbd3: name_show (STB_LOCAL)
ffffffff818526b0-ffffffff818526d3: name_show (STB_LOCAL)
ffffffff818c7fe0-ffffffff818c801c: name_show (STB_LOCAL)
ffffffff818c8ea0-ffffffff818c8ec6: name_show (STB_LOCAL)
ffffffff818cd040-ffffffff818cd063: name_show (STB_LOCAL)
ffffffff81a64de0-ffffffff81a64e06: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81115f40)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffffffff816788f0)
Location: drivers/regulator/core.c:592
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81713d70)
Location: drivers/base/power/wakeup_stats.c:89
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff81869660)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff818731b0)
Location: drivers/i2c/i2c-dev.c:95
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff8187d3c0)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff818840f0)
Location: drivers/hwmon/hwmon.c:67
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff818f6970)
Location: drivers/remoteproc/remoteproc_sysfs.c:117
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff818f8430)
Location: drivers/devfreq/devfreq.c:1113
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818fa470)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff818fb4b1)
Location: drivers/extcon/extcon.c:367
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff818ff430)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (ffffffff81a9b7c0)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
ffffffff81115f40-ffffffff81115f9e: name_show (STB_LOCAL)
ffffffff816788f0-ffffffff81678935: name_show (STB_LOCAL)
ffffffff81713d70-ffffffff81713d96: name_show (STB_LOCAL)
ffffffff81869660-ffffffff818696a2: name_show (STB_LOCAL)
ffffffff818731b0-ffffffff818731fd: name_show (STB_LOCAL)
ffffffff8187d3c0-ffffffff8187d3e3: name_show (STB_LOCAL)
ffffffff818840f0-ffffffff81884113: name_show (STB_LOCAL)
ffffffff818f6970-ffffffff818f6993: name_show (STB_LOCAL)
ffffffff818f8430-ffffffff818f845f: name_show (STB_LOCAL)
ffffffff818fa470-ffffffff818fa4ac: name_show (STB_LOCAL)
ffffffff818fb2f0-ffffffff818fb316: name_show (STB_LOCAL)
ffffffff818ff430-ffffffff818ff453: name_show (STB_LOCAL)
ffffffff81a9b7c0-ffffffff81a9b7e6: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81121c60)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81729650)
Location: drivers/regulator/core.c:595
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817cf850)
Location: drivers/base/power/wakeup_stats.c:89
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff8193d2c0)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819401b0)
Location: drivers/i2c/i2c-core-base.c:469
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff819473b0)
Location: drivers/i2c/i2c-dev.c:97
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff8194b790)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff81952be0)
Location: drivers/hwmon/hwmon.c:68
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff819ccaa0)
Location: drivers/remoteproc/remoteproc_sysfs.c:118
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff819ce8e0)
Location: drivers/devfreq/devfreq.c:1260
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d0f10)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff819d1c00)
Location: drivers/extcon/extcon.c:367
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d64a0)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (ffffffff81b96f50)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
ffffffff81121c60-ffffffff81121cbe: name_show (STB_LOCAL)
ffffffff81729650-ffffffff817296ab: name_show (STB_LOCAL)
ffffffff817cf850-ffffffff817cf876: name_show (STB_LOCAL)
ffffffff8193d2c0-ffffffff8193d302: name_show (STB_LOCAL)
ffffffff819401b0-ffffffff819401e4: name_show (STB_LOCAL)
ffffffff819473b0-ffffffff81947442: name_show (STB_LOCAL)
ffffffff8194b790-ffffffff8194b7b3: name_show (STB_LOCAL)
ffffffff81952be0-ffffffff81952c03: name_show (STB_LOCAL)
ffffffff819ccaa0-ffffffff819ccac3: name_show (STB_LOCAL)
ffffffff819ce8e0-ffffffff819ce90f: name_show (STB_LOCAL)
ffffffff819d0f10-ffffffff819d0f4c: name_show (STB_LOCAL)
ffffffff819d1c00-ffffffff819d1c26: name_show (STB_LOCAL)
ffffffff819d64a0-ffffffff819d64c3: name_show (STB_LOCAL)
ffffffff81b96f50-ffffffff81b96f76: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111dcc0)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81746160)
Location: drivers/regulator/core.c:618
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817e3e10)
Location: drivers/base/power/wakeup_stats.c:91
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff819432d0)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81946320)
Location: drivers/i2c/i2c-core-base.c:597
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff8194d1c0)
Location: drivers/i2c/i2c-dev.c:97
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff819511a0)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff81957a60)
Location: drivers/hwmon/hwmon.c:68
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff819cc260)
Location: drivers/remoteproc/remoteproc_sysfs.c:219
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff819ce260)
Location: drivers/devfreq/devfreq.c:1341
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d0bd0)
Location: drivers/devfreq/devfreq-event.c:439
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff819d1800)
Location: drivers/extcon/extcon.c:367
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d58c0)
Location: drivers/powercap/powercap_sys.c:346
Inline: False
```
```
In net/rfkill/core.c (ffffffff81ba6bf0)
Location: net/rfkill/core.c:681
Inline: False
```
**Symbols:**

```
ffffffff8111dcc0-ffffffff8111dd1e: name_show (STB_LOCAL)
ffffffff81746160-ffffffff817461bb: name_show (STB_LOCAL)
ffffffff817e3e10-ffffffff817e3e36: name_show (STB_LOCAL)
ffffffff819432d0-ffffffff81943312: name_show (STB_LOCAL)
ffffffff81946320-ffffffff81946354: name_show (STB_LOCAL)
ffffffff8194d1c0-ffffffff8194d252: name_show (STB_LOCAL)
ffffffff819511a0-ffffffff819511c3: name_show (STB_LOCAL)
ffffffff81957a60-ffffffff81957a83: name_show (STB_LOCAL)
ffffffff819cc260-ffffffff819cc283: name_show (STB_LOCAL)
ffffffff819ce260-ffffffff819ce28f: name_show (STB_LOCAL)
ffffffff819d0bd0-ffffffff819d0c0c: name_show (STB_LOCAL)
ffffffff819d1800-ffffffff819d1826: name_show (STB_LOCAL)
ffffffff819d58c0-ffffffff819d58e3: name_show (STB_LOCAL)
ffffffff81ba6bf0-ffffffff81ba6c16: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111def0)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81729bd0)
Location: drivers/regulator/core.c:619
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817c8250)
Location: drivers/base/power/wakeup_stats.c:91
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff81926af0)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81929b60)
Location: drivers/i2c/i2c-core-base.c:641
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff81931410)
Location: drivers/i2c/i2c-dev.c:97
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81935020)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff8193b6a0)
Location: drivers/hwmon/hwmon.c:68
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff819b13d0)
Location: drivers/remoteproc/remoteproc_sysfs.c:224
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff819b33d0)
Location: drivers/devfreq/devfreq.c:1359
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819b5e40)
Location: drivers/devfreq/devfreq-event.c:439
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff819b6ae0)
Location: drivers/extcon/extcon.c:367
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819bb990)
Location: drivers/powercap/powercap_sys.c:346
Inline: False
```
```
In net/rfkill/core.c (ffffffff81b95d80)
Location: net/rfkill/core.c:682
Inline: False
```
**Symbols:**

```
ffffffff8111def0-ffffffff8111df4e: name_show (STB_LOCAL)
ffffffff81729bd0-ffffffff81729c2b: name_show (STB_LOCAL)
ffffffff817c8250-ffffffff817c8276: name_show (STB_LOCAL)
ffffffff81926af0-ffffffff81926b32: name_show (STB_LOCAL)
ffffffff81929b60-ffffffff81929b94: name_show (STB_LOCAL)
ffffffff81931410-ffffffff819314a2: name_show (STB_LOCAL)
ffffffff81935020-ffffffff81935043: name_show (STB_LOCAL)
ffffffff8193b6a0-ffffffff8193b6c3: name_show (STB_LOCAL)
ffffffff819b13d0-ffffffff819b13f3: name_show (STB_LOCAL)
ffffffff819b33d0-ffffffff819b33ff: name_show (STB_LOCAL)
ffffffff819b5e40-ffffffff819b5e79: name_show (STB_LOCAL)
ffffffff819b6ae0-ffffffff819b6b06: name_show (STB_LOCAL)
ffffffff819bb990-ffffffff819bb9b3: name_show (STB_LOCAL)
ffffffff81b95d80-ffffffff81b95da6: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113e360)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/pnp/card.c (ffffffff8176d750)
Location: drivers/pnp/card.c:184
Inline: False
```
```
In drivers/regulator/core.c (ffffffff817a8cc0)
Location: drivers/regulator/core.c:609
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81852750)
Location: drivers/base/power/wakeup_stats.c:91
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff819c9a30)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cccb0)
Location: drivers/i2c/i2c-core-base.c:642
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff819d46f0)
Location: drivers/i2c/i2c-dev.c:98
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff819d8440)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff819dfed0)
Location: drivers/hwmon/hwmon.c:68
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81a5fab0)
Location: drivers/remoteproc/remoteproc_sysfs.c:224
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81a61cb0)
Location: drivers/devfreq/devfreq.c:1359
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81a649b0)
Location: drivers/devfreq/devfreq-event.c:439
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff81a656d0)
Location: drivers/extcon/extcon.c:367
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff81a6ab10)
Location: drivers/powercap/powercap_sys.c:346
Inline: False
```
```
In net/rfkill/core.c (ffffffff81c625f0)
Location: net/rfkill/core.c:682
Inline: False
```
**Symbols:**

```
ffffffff8113e360-ffffffff8113e3be: name_show (STB_LOCAL)
ffffffff8176d750-ffffffff8176d776: name_show (STB_LOCAL)
ffffffff817a8cc0-ffffffff817a8d1b: name_show (STB_LOCAL)
ffffffff81852750-ffffffff81852776: name_show (STB_LOCAL)
ffffffff819c9a30-ffffffff819c9a72: name_show (STB_LOCAL)
ffffffff819cccb0-ffffffff819ccce4: name_show (STB_LOCAL)
ffffffff819d46f0-ffffffff819d4782: name_show (STB_LOCAL)
ffffffff819d8440-ffffffff819d8463: name_show (STB_LOCAL)
ffffffff819dfed0-ffffffff819dfef3: name_show (STB_LOCAL)
ffffffff81a5fab0-ffffffff81a5fad3: name_show (STB_LOCAL)
ffffffff81a61cb0-ffffffff81a61cdf: name_show (STB_LOCAL)
ffffffff81a649b0-ffffffff81a649e9: name_show (STB_LOCAL)
ffffffff81a656d0-ffffffff81a656f6: name_show (STB_LOCAL)
ffffffff81a6ab10-ffffffff81a6ab33: name_show (STB_LOCAL)
ffffffff81c625f0-ffffffff81c62616: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81160fe0)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/pnp/card.c (ffffffff818a2860)
Location: drivers/pnp/card.c:184
Inline: False
```
```
In drivers/regulator/core.c (ffffffff818e33c0)
Location: drivers/regulator/core.c:610
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81998690)
Location: drivers/base/power/wakeup_stats.c:91
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff81b2ae80)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2e920)
Location: drivers/i2c/i2c-core-base.c:643
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff81b36b60)
Location: drivers/i2c/i2c-dev.c:98
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81b3b810)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff81b448c0)
Location: drivers/hwmon/hwmon.c:70
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81bcfe60)
Location: drivers/remoteproc/remoteproc_sysfs.c:213
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd2ad0)
Location: drivers/devfreq/devfreq.c:1389
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81bd5680)
Location: drivers/devfreq/devfreq-event.c:439
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff81bd6d41)
Location: drivers/extcon/extcon.c:367
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff81bdb420)
Location: drivers/powercap/powercap_sys.c:346
Inline: False
```
```
In net/rfkill/core.c (ffffffff81e04e60)
Location: net/rfkill/core.c:682
Inline: False
```
**Symbols:**

```
ffffffff81160fe0-ffffffff81161040: name_show (STB_LOCAL)
ffffffff818a2860-ffffffff818a2890: name_show (STB_LOCAL)
ffffffff818e33c0-ffffffff818e3433: name_show (STB_LOCAL)
ffffffff81998690-ffffffff819986c0: name_show (STB_LOCAL)
ffffffff81b2ae80-ffffffff81b2aecc: name_show (STB_LOCAL)
ffffffff81b2e920-ffffffff81b2e95e: name_show (STB_LOCAL)
ffffffff81b36b60-ffffffff81b36c09: name_show (STB_LOCAL)
ffffffff81b3b810-ffffffff81b3b83d: name_show (STB_LOCAL)
ffffffff81b448c0-ffffffff81b448ed: name_show (STB_LOCAL)
ffffffff81bcfe60-ffffffff81bcfe8d: name_show (STB_LOCAL)
ffffffff81bd2ad0-ffffffff81bd2b09: name_show (STB_LOCAL)
ffffffff81bd5680-ffffffff81bd56cd: name_show (STB_LOCAL)
ffffffff81bd6ab0-ffffffff81bd6ae0: name_show (STB_LOCAL)
ffffffff81bdb420-ffffffff81bdb44d: name_show (STB_LOCAL)
ffffffff81e04e60-ffffffff81e04e90: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811945c0)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/pnp/card.c (ffffffff819ec0c0)
Location: drivers/pnp/card.c:184
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81a384e0)
Location: drivers/regulator/core.c:610
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81b097b0)
Location: drivers/base/power/wakeup_stats.c:91
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff81cbeb50)
Location: drivers/rtc/sysfs.c:25
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc2580)
Location: drivers/i2c/i2c-core-base.c:644
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff81ccbe50)
Location: drivers/i2c/i2c-dev.c:98
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81cd1670)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdb980)
Location: drivers/hwmon/hwmon.c:71
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81d7afc0)
Location: drivers/remoteproc/remoteproc_sysfs.c:213
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7e8e0)
Location: drivers/devfreq/devfreq.c:1391
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81d81c80)
Location: drivers/devfreq/devfreq-event.c:439
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff81d835f1)
Location: drivers/extcon/extcon.c:377
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff81d85fb0)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (ffffffff81fda080)
Location: net/rfkill/core.c:682
Inline: False
```
**Symbols:**

```
ffffffff811945c0-ffffffff81194620: name_show (STB_LOCAL)
ffffffff819ec0c0-ffffffff819ec0f0: name_show (STB_LOCAL)
ffffffff81a384e0-ffffffff81a38553: name_show (STB_LOCAL)
ffffffff81b097b0-ffffffff81b097e0: name_show (STB_LOCAL)
ffffffff81cbeb50-ffffffff81cbeb9c: name_show (STB_LOCAL)
ffffffff81cc2580-ffffffff81cc25be: name_show (STB_LOCAL)
ffffffff81ccbe50-ffffffff81ccbef9: name_show (STB_LOCAL)
ffffffff81cd1670-ffffffff81cd169d: name_show (STB_LOCAL)
ffffffff81cdb980-ffffffff81cdb9ad: name_show (STB_LOCAL)
ffffffff81d7afc0-ffffffff81d7afed: name_show (STB_LOCAL)
ffffffff81d7e8e0-ffffffff81d7e919: name_show (STB_LOCAL)
ffffffff81d81c80-ffffffff81d81ccd: name_show (STB_LOCAL)
ffffffff81d83340-ffffffff81d83370: name_show (STB_LOCAL)
ffffffff81d85fb0-ffffffff81d85fdd: name_show (STB_LOCAL)
ffffffff81fda080-ffffffff81fda0b0: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a5e20)
Location: kernel/irq/irqdesc.c:262
Inline: False
```
```
In drivers/pnp/card.c (ffffffff81a347f0)
Location: drivers/pnp/card.c:184
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81a82030)
Location: drivers/regulator/core.c:676
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81b577c0)
Location: drivers/base/power/wakeup_stats.c:91
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff81d26460)
Location: drivers/rtc/sysfs.c:25
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d29f90)
Location: drivers/i2c/i2c-core-base.c:659
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff81d33bc0)
Location: drivers/i2c/i2c-dev.c:98
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81d390b0)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff81d43ce0)
Location: drivers/hwmon/hwmon.c:71
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81de9180)
Location: drivers/remoteproc/remoteproc_sysfs.c:213
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81decc70)
Location: drivers/devfreq/devfreq.c:1392
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81df0040)
Location: drivers/devfreq/devfreq-event.c:439
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff81df1a36)
Location: drivers/extcon/extcon.c:387
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff81df4420)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (ffffffff82055d40)
Location: net/rfkill/core.c:682
Inline: False
```
**Symbols:**

```
ffffffff811a5e20-ffffffff811a5e80: name_show (STB_LOCAL)
ffffffff81a347f0-ffffffff81a34820: name_show (STB_LOCAL)
ffffffff81a82030-ffffffff81a820a3: name_show (STB_LOCAL)
ffffffff81b577c0-ffffffff81b577f0: name_show (STB_LOCAL)
ffffffff81d26460-ffffffff81d264ac: name_show (STB_LOCAL)
ffffffff81d29f90-ffffffff81d29fce: name_show (STB_LOCAL)
ffffffff81d33bc0-ffffffff81d33c69: name_show (STB_LOCAL)
ffffffff81d390b0-ffffffff81d390dd: name_show (STB_LOCAL)
ffffffff81d43ce0-ffffffff81d43d0d: name_show (STB_LOCAL)
ffffffff81de9180-ffffffff81de91ad: name_show (STB_LOCAL)
ffffffff81decc70-ffffffff81decca9: name_show (STB_LOCAL)
ffffffff81df0040-ffffffff81df008d: name_show (STB_LOCAL)
ffffffff81df1710-ffffffff81df1740: name_show (STB_LOCAL)
ffffffff81df4420-ffffffff81df444d: name_show (STB_LOCAL)
ffffffff82055d40-ffffffff82055d70: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b5910)
Location: kernel/irq/irqdesc.c:262
Inline: False
```
```
In drivers/pnp/card.c (ffffffff81a7fc90)
Location: drivers/pnp/card.c:184
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81ad4690)
Location: drivers/regulator/core.c:678
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81bafdb0)
Location: drivers/base/power/wakeup_stats.c:91
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff81ddc1d0)
Location: drivers/rtc/sysfs.c:25
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81ddfe50)
Location: drivers/i2c/i2c-core-base.c:662
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff81de9930)
Location: drivers/i2c/i2c-dev.c:98
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81def350)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfa6b0)
Location: drivers/hwmon/hwmon.c:71
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81e9f3c0)
Location: drivers/remoteproc/remoteproc_sysfs.c:213
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea3010)
Location: drivers/devfreq/devfreq.c:1413
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81ea6600)
Location: drivers/devfreq/devfreq-event.c:439
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff81ea8086)
Location: drivers/extcon/extcon.c:387
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff81eaaab0)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (ffffffff821285c0)
Location: net/rfkill/core.c:694
Inline: False
```
**Symbols:**

```
ffffffff811b5910-ffffffff811b5970: name_show (STB_LOCAL)
ffffffff81a7fc90-ffffffff81a7fcc0: name_show (STB_LOCAL)
ffffffff81ad4690-ffffffff81ad4703: name_show (STB_LOCAL)
ffffffff81bafdb0-ffffffff81bafde0: name_show (STB_LOCAL)
ffffffff81ddc1d0-ffffffff81ddc21c: name_show (STB_LOCAL)
ffffffff81ddfe50-ffffffff81ddfe8e: name_show (STB_LOCAL)
ffffffff81de9930-ffffffff81de99d9: name_show (STB_LOCAL)
ffffffff81def350-ffffffff81def37d: name_show (STB_LOCAL)
ffffffff81dfa6b0-ffffffff81dfa6dd: name_show (STB_LOCAL)
ffffffff81e9f3c0-ffffffff81e9f3ed: name_show (STB_LOCAL)
ffffffff81ea3010-ffffffff81ea3049: name_show (STB_LOCAL)
ffffffff81ea6600-ffffffff81ea664d: name_show (STB_LOCAL)
ffffffff81ea7d60-ffffffff81ea7d90: name_show (STB_LOCAL)
ffffffff81eaaab0-ffffffff81eaaadd: name_show (STB_LOCAL)
ffffffff821285c0-ffffffff821285f0: name_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010177678)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffff8000108415d0)
Location: drivers/regulator/core.c:592
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffff8000109056f8)
Location: drivers/base/power/wakeup_stats.c:89
Inline: False
```
```
In drivers/rtc/sysfs.c (ffff800010aabf38)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab7318)
Location: drivers/i2c/i2c-dev.c:95
Inline: False
```
```
In drivers/pps/sysfs.c (ffff800010ac6b68)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffff800010ad0e18)
Location: drivers/hwmon/hwmon.c:67
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffff800010b82b00)
Location: drivers/remoteproc/remoteproc_sysfs.c:117
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffff800010b84dc0)
Location: drivers/devfreq/devfreq.c:1113
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffff800010b86da8)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In drivers/extcon/extcon.c (ffff800010b89468)
Location: drivers/extcon/extcon.c:367
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffff800010b8eca0)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (ffff800010d6b698)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
ffff800010177678-ffff800010177730: name_show (STB_LOCAL)
ffff8000108415d0-ffff800010841648: name_show (STB_LOCAL)
ffff8000109056f8-ffff80001090573c: name_show (STB_LOCAL)
ffff800010aabf38-ffff800010aabf90: name_show (STB_LOCAL)
ffff800010ab7318-ffff800010ab7374: name_show (STB_LOCAL)
ffff800010ac6b68-ffff800010ac6ba8: name_show (STB_LOCAL)
ffff800010ad0e18-ffff800010ad0e58: name_show (STB_LOCAL)
ffff800010b82b00-ffff800010b82b40: name_show (STB_LOCAL)
ffff800010b84dc0-ffff800010b84e0c: name_show (STB_LOCAL)
ffff800010b86da8-ffff800010b86e00: name_show (STB_LOCAL)
ffff800010b87d70-ffff800010b87db4: name_show (STB_LOCAL)
ffff800010b8eca0-ffff800010b8ece0: name_show (STB_LOCAL)
ffff800010d6b698-ffff800010d6b6d8: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c9010)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (c094ac48)
Location: drivers/regulator/core.c:592
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (c09ef1bc)
Location: drivers/base/power/wakeup_stats.c:89
Inline: False
```
```
In drivers/rtc/sysfs.c (c0b8a4f8)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-dev.c (c0b9729c)
Location: drivers/i2c/i2c-dev.c:95
Inline: False
```
```
In drivers/pps/sysfs.c (c0ba669c)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (c0bb1664)
Location: drivers/hwmon/hwmon.c:67
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (c0c65eb8)
Location: drivers/remoteproc/remoteproc_sysfs.c:117
Inline: False
```
```
In drivers/devfreq/devfreq.c (c0c67e2c)
Location: drivers/devfreq/devfreq.c:1113
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (c0c69d44)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In drivers/extcon/extcon.c (c0c6c7dc)
Location: drivers/extcon/extcon.c:367
Inline: True
```
```
In drivers/powercap/powercap_sys.c (c0c78d40)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (c0e69ad0)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
c03c9010-c03c9078: name_show (STB_LOCAL)
c094ac48-c094ac9c: name_show (STB_LOCAL)
c09ef1bc-c09ef1ec: name_show (STB_LOCAL)
c0b8a4f8-c0b8a544: name_show (STB_LOCAL)
c0b9729c-c0b972ec: name_show (STB_LOCAL)
c0ba669c-c0ba66cc: name_show (STB_LOCAL)
c0bb1664-c0bb1694: name_show (STB_LOCAL)
c0c65eb8-c0c65ee8: name_show (STB_LOCAL)
c0c67e2c-c0c67e64: name_show (STB_LOCAL)
c0c69d44-c0c69d90: name_show (STB_LOCAL)
c0c6c7dc-c0c6c80c: name_show (STB_LOCAL)
c0c78d40-c0c78d70: name_show (STB_LOCAL)
c0e69ad0-c0e69b00: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/pseries/vio.c (c0000000000ffe50)
Location: arch/powerpc/platforms/pseries/vio.c:1526
Inline: False
```
```
In kernel/irq/irqdesc.c (c0000000001d13a0)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (c0000000008dbbc0)
Location: drivers/regulator/core.c:592
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (c0000000009a3fe0)
Location: drivers/base/power/wakeup_stats.c:89
Inline: False
```
```
In drivers/rtc/sysfs.c (c000000000b8e100)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-dev.c (c000000000b9a930)
Location: drivers/i2c/i2c-dev.c:95
Inline: False
```
```
In drivers/pps/sysfs.c (c000000000ba81e0)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (c000000000bb4f60)
Location: drivers/hwmon/hwmon.c:67
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (c000000000c5fc10)
Location: drivers/remoteproc/remoteproc_sysfs.c:117
Inline: False
```
```
In drivers/devfreq/devfreq.c (c000000000c629f0)
Location: drivers/devfreq/devfreq.c:1113
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (c000000000c65aa0)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In drivers/extcon/extcon.c (c000000000c66dd0)
Location: drivers/extcon/extcon.c:367
Inline: True
```
```
In drivers/powercap/powercap_sys.c (c000000000c6d660)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (c000000000ea8f00)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
c0000000000ffe50-c0000000000ffe98: name_show (STB_LOCAL)
c0000000001d13a0-c0000000001d1470: name_show (STB_LOCAL)
c0000000008dbbc0-c0000000008dbc60: name_show (STB_LOCAL)
c0000000009a3fe0-c0000000009a4028: name_show (STB_LOCAL)
c000000000b8e100-c000000000b8e17c: name_show (STB_LOCAL)
c000000000b9a930-c000000000b9a9a0: name_show (STB_LOCAL)
c000000000ba81e0-c000000000ba8228: name_show (STB_LOCAL)
c000000000bb4f60-c000000000bb4fa8: name_show (STB_LOCAL)
c000000000c5fc10-c000000000c5fc58: name_show (STB_LOCAL)
c000000000c629f0-c000000000c62a44: name_show (STB_LOCAL)
c000000000c65aa0-c000000000c65b08: name_show (STB_LOCAL)
c000000000c66dd0-c000000000c66e18: name_show (STB_LOCAL)
c000000000c6d660-c000000000c6d6a8: name_show (STB_LOCAL)
c000000000ea8f00-c000000000ea8f48: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe0001126d6)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffffffe000523324)
Location: drivers/regulator/core.c:592
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffe0006b6810)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffe0006bd0d6)
Location: drivers/i2c/i2c-dev.c:95
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffe0006c565e)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffe0006cd610)
Location: drivers/hwmon/hwmon.c:67
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffe00072e432)
Location: drivers/devfreq/devfreq.c:1113
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffe00072fd52)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffe000730960)
Location: drivers/extcon/extcon.c:367
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffe000734a2c)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (ffffffe00089dfe8)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
ffffffe0001126d6-ffffffe000112766: name_show (STB_LOCAL)
ffffffe000523324-ffffffe000523376: name_show (STB_LOCAL)
ffffffe0006bd0d6-ffffffe0006bd12a: name_show (STB_LOCAL)
ffffffe0006cd610-ffffffe0006cd64c: name_show (STB_LOCAL)
ffffffe00072e432-ffffffe00072e474: name_show (STB_LOCAL)
ffffffe00072fd52-ffffffe00072fd9c: name_show (STB_LOCAL)
ffffffe000730960-ffffffe00073099e: name_show (STB_LOCAL)
ffffffe000734a2c-ffffffe000734a68: name_show (STB_LOCAL)
ffffffe00089dfe8-ffffffe00089e024: name_show (STB_LOCAL)
ffffffe0006b6810-ffffffe0006b685c: name_show (STB_LOCAL)
ffffffe0006c565e-ffffffe0006c569a: name_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110e520)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffffffff8163e3f0)
Location: drivers/regulator/core.c:592
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff816da0a0)
Location: drivers/base/power/wakeup_stats.c:89
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff8181c310)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81825930)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff81829f70)
Location: drivers/hwmon/hwmon.c:67
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81897ca0)
Location: drivers/remoteproc/remoteproc_sysfs.c:117
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81899760)
Location: drivers/devfreq/devfreq.c:1113
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8189b7a0)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8189c7e1)
Location: drivers/extcon/extcon.c:367
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff81a3ab50)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
ffffffff8110e520-ffffffff8110e57e: name_show (STB_LOCAL)
ffffffff8163e3f0-ffffffff8163e435: name_show (STB_LOCAL)
ffffffff816da0a0-ffffffff816da0c6: name_show (STB_LOCAL)
ffffffff8181c310-ffffffff8181c352: name_show (STB_LOCAL)
ffffffff81825930-ffffffff81825953: name_show (STB_LOCAL)
ffffffff81829f70-ffffffff81829f93: name_show (STB_LOCAL)
ffffffff81897ca0-ffffffff81897cc3: name_show (STB_LOCAL)
ffffffff81899760-ffffffff8189978f: name_show (STB_LOCAL)
ffffffff8189b7a0-ffffffff8189b7dc: name_show (STB_LOCAL)
ffffffff8189c620-ffffffff8189c646: name_show (STB_LOCAL)
ffffffff81a3ab50-ffffffff81a3ab76: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ff2e0)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffffffff8161e7d0)
Location: drivers/regulator/core.c:592
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff816b4720)
Location: drivers/base/power/wakeup_stats.c:89
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff817e3a00)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff817ecfc0)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff817f1600)
Location: drivers/hwmon/hwmon.c:67
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81856c30)
Location: drivers/devfreq/devfreq.c:1113
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81858c70)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In net/rfkill/core.c (ffffffff819f7770)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
ffffffff810ff2e0-ffffffff810ff338: name_show (STB_LOCAL)
ffffffff8161e7d0-ffffffff8161e815: name_show (STB_LOCAL)
ffffffff816b4720-ffffffff816b4746: name_show (STB_LOCAL)
ffffffff817e3a00-ffffffff817e3a42: name_show (STB_LOCAL)
ffffffff817ecfc0-ffffffff817ecfe3: name_show (STB_LOCAL)
ffffffff817f1600-ffffffff817f1623: name_show (STB_LOCAL)
ffffffff81856c30-ffffffff81856c5f: name_show (STB_LOCAL)
ffffffff81858c70-ffffffff81858cac: name_show (STB_LOCAL)
ffffffff819f7770-ffffffff819f7796: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110c410)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffffffff8166c730)
Location: drivers/regulator/core.c:592
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81707a30)
Location: drivers/base/power/wakeup_stats.c:89
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff8185d7f0)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff81867340)
Location: drivers/i2c/i2c-dev.c:95
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff81872870)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff818795a0)
Location: drivers/hwmon/hwmon.c:67
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff818e8e50)
Location: drivers/devfreq/devfreq.c:1113
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818eae90)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff818ebed1)
Location: drivers/extcon/extcon.c:367
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff818efe50)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (ffffffff81aa6a00)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
ffffffff8110c410-ffffffff8110c46e: name_show (STB_LOCAL)
ffffffff8166c730-ffffffff8166c775: name_show (STB_LOCAL)
ffffffff81707a30-ffffffff81707a56: name_show (STB_LOCAL)
ffffffff8185d7f0-ffffffff8185d832: name_show (STB_LOCAL)
ffffffff81867340-ffffffff8186738d: name_show (STB_LOCAL)
ffffffff81872870-ffffffff81872893: name_show (STB_LOCAL)
ffffffff818795a0-ffffffff818795c3: name_show (STB_LOCAL)
ffffffff818e8e50-ffffffff818e8e7f: name_show (STB_LOCAL)
ffffffff818eae90-ffffffff818eaecc: name_show (STB_LOCAL)
ffffffff818ebd10-ffffffff818ebd36: name_show (STB_LOCAL)
ffffffff818efe50-ffffffff818efe73: name_show (STB_LOCAL)
ffffffff81aa6a00-ffffffff81aa6a26: name_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t name_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81117540)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81686d60)
Location: drivers/regulator/core.c:592
Inline: False
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81722460)
Location: drivers/base/power/wakeup_stats.c:89
Inline: False
```
```
In drivers/rtc/sysfs.c (ffffffff81878a60)
Location: drivers/rtc/sysfs.c:24
Inline: False
```
```
In drivers/i2c/i2c-dev.c (ffffffff81882550)
Location: drivers/i2c/i2c-dev.c:95
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffff8188e220)
Location: drivers/pps/sysfs.c:64
Inline: False
```
```
In drivers/hwmon/hwmon.c (ffffffff81894f40)
Location: drivers/hwmon/hwmon.c:67
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81908400)
Location: drivers/remoteproc/remoteproc_sysfs.c:117
Inline: False
```
```
In drivers/devfreq/devfreq.c (ffffffff81909ed0)
Location: drivers/devfreq/devfreq.c:1113
Inline: False
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8190bf10)
Location: drivers/devfreq/devfreq-event.c:437
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8190cf51)
Location: drivers/extcon/extcon.c:367
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In drivers/powercap/powercap_sys.c (ffffffff81910ed0)
Location: drivers/powercap/powercap_sys.c:347
Inline: False
```
```
In net/rfkill/core.c (ffffffff81ab2da0)
Location: net/rfkill/core.c:669
Inline: False
```
**Symbols:**

```
ffffffff81117540-ffffffff81117599: name_show (STB_LOCAL)
ffffffff81686d60-ffffffff81686da5: name_show (STB_LOCAL)
ffffffff81722460-ffffffff81722486: name_show (STB_LOCAL)
ffffffff81878a60-ffffffff81878aa2: name_show (STB_LOCAL)
ffffffff81882550-ffffffff8188259d: name_show (STB_LOCAL)
ffffffff8188e220-ffffffff8188e243: name_show (STB_LOCAL)
ffffffff81894f40-ffffffff81894f63: name_show (STB_LOCAL)
ffffffff81908400-ffffffff81908423: name_show (STB_LOCAL)
ffffffff81909ed0-ffffffff81909eff: name_show (STB_LOCAL)
ffffffff8190bf10-ffffffff8190bf4c: name_show (STB_LOCAL)
ffffffff8190cd90-ffffffff8190cdb6: name_show (STB_LOCAL)
ffffffff81910ed0-ffffffff81910ef3: name_show (STB_LOCAL)
ffffffff81ab2da0-ffffffff81ab2dc6: name_show (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device_attribute *attr</code> ➡️ <code>struct kobj_attribute *attr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct kobj_attribute *attr</code> ➡️ <code>struct device_attribute *attr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
