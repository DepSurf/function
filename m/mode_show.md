# Function: <code>mode_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815a20e0)
Location: drivers/nvdimm/pfn_devs.c:56
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff816838b0)
Location: drivers/thermal/thermal_core.c:613
Inline: False
```
**Symbols:**

```
ffffffff815a20e0-ffffffff815a2168: mode_show (STB_LOCAL)
ffffffff816838b0-ffffffff81683939: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f17e0)
Location: drivers/nvdimm/namespace_devs.c:1277
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815f8c90)
Location: drivers/nvdimm/pfn_devs.c:57
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff816e4f10)
Location: drivers/thermal/thermal_core.c:613
Inline: False
```
**Symbols:**

```
ffffffff815f17e0-ffffffff815f1882: mode_show (STB_LOCAL)
ffffffff815f8c90-ffffffff815f8cf2: mode_show (STB_LOCAL)
ffffffff816e4f10-ffffffff816e4f99: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8161ef20)
Location: drivers/nvdimm/namespace_devs.c:1385
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81626f10)
Location: drivers/nvdimm/pfn_devs.c:57
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81718820)
Location: drivers/thermal/thermal_sysfs.c:51
Inline: False
```
**Symbols:**

```
ffffffff8161ef20-ffffffff8161efc2: mode_show (STB_LOCAL)
ffffffff81626f10-ffffffff81626f72: mode_show (STB_LOCAL)
ffffffff81718820-ffffffff817188a9: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81633370)
Location: drivers/nvdimm/namespace_devs.c:1544
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8163bbc0)
Location: drivers/nvdimm/pfn_devs.c:57
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81730ac0)
Location: drivers/thermal/thermal_sysfs.c:51
Inline: False
```
**Symbols:**

```
ffffffff81633370-ffffffff81633411: mode_show (STB_LOCAL)
ffffffff8163bbc0-ffffffff8163bc22: mode_show (STB_LOCAL)
ffffffff81730ac0-ffffffff81730b49: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169bce0)
Location: drivers/nvdimm/namespace_devs.c:1553
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816a47e0)
Location: drivers/nvdimm/pfn_devs.c:57
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817a1b50)
Location: drivers/thermal/thermal_sysfs.c:51
Inline: False
```
**Symbols:**

```
ffffffff8169bce0-ffffffff8169bd81: mode_show (STB_LOCAL)
ffffffff816a47e0-ffffffff816a4842: mode_show (STB_LOCAL)
ffffffff817a1b50-ffffffff817a1bdc: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816d8110)
Location: drivers/nvdimm/namespace_devs.c:1551
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e1030)
Location: drivers/nvdimm/pfn_devs.c:57
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff817deb40)
Location: drivers/pps/sysfs.c:60
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817e9040)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff816d8110-ffffffff816d81b6: mode_show (STB_LOCAL)
ffffffff816e1030-ffffffff816e1092: mode_show (STB_LOCAL)
ffffffff817deb40-ffffffff817deb69: mode_show (STB_LOCAL)
ffffffff817e9040-ffffffff817e90cc: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fa130)
Location: drivers/nvdimm/namespace_devs.c:1574
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81703680)
Location: drivers/nvdimm/pfn_devs.c:57
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff81809f70)
Location: drivers/pps/sysfs.c:60
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81814ef0)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff816fa130-ffffffff816fa1dc: mode_show (STB_LOCAL)
ffffffff81703680-ffffffff817036e2: mode_show (STB_LOCAL)
ffffffff81809f70-ffffffff81809f99: mode_show (STB_LOCAL)
ffffffff81814ef0-ffffffff81814f7c: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81733be0)
Location: drivers/nvdimm/namespace_devs.c:1581
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173d140)
Location: drivers/nvdimm/pfn_devs.c:49
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff8184bc10)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81857100)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff81733be0-ffffffff81733c94: mode_show (STB_LOCAL)
ffffffff8173d140-ffffffff8173d1a2: mode_show (STB_LOCAL)
ffffffff8184bc10-ffffffff8184bc36: mode_show (STB_LOCAL)
ffffffff81857100-ffffffff81857191: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81757970)
Location: drivers/nvdimm/namespace_devs.c:1581
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81760f70)
Location: drivers/nvdimm/pfn_devs.c:49
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff8187d420)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81888bb0)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff81757970-ffffffff81757a24: mode_show (STB_LOCAL)
ffffffff81760f70-ffffffff81760fd2: mode_show (STB_LOCAL)
ffffffff8187d420-ffffffff8187d446: mode_show (STB_LOCAL)
ffffffff81888bb0-ffffffff81888c41: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81817930)
Location: drivers/nvdimm/namespace_devs.c:1561
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81820b20)
Location: drivers/nvdimm/pfn_devs.c:38
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff8194b7f0)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819575d0)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff81817930-ffffffff818179e4: mode_show (STB_LOCAL)
ffffffff81820b20-ffffffff81820b8b: mode_show (STB_LOCAL)
ffffffff8194b7f0-ffffffff8194b816: mode_show (STB_LOCAL)
ffffffff819575d0-ffffffff8195765d: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d3200)
Location: kernel/reboot.c:618
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81826a60)
Location: drivers/nvdimm/namespace_devs.c:1561
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182fa10)
Location: drivers/nvdimm/pfn_devs.c:38
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff81951200)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195d350)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff810d3200-ffffffff810d3236: mode_show (STB_LOCAL)
ffffffff81826a60-ffffffff81826b14: mode_show (STB_LOCAL)
ffffffff8182fa10-ffffffff8182fa7b: mode_show (STB_LOCAL)
ffffffff81951200-ffffffff81951226: mode_show (STB_LOCAL)
ffffffff8195d350-ffffffff8195d392: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d4ef0)
Location: kernel/reboot.c:618
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81809cc0)
Location: drivers/nvdimm/namespace_devs.c:1561
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81812ca0)
Location: drivers/nvdimm/pfn_devs.c:38
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff81935080)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81940230)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff810d4ef0-ffffffff810d4f26: mode_show (STB_LOCAL)
ffffffff81809cc0-ffffffff81809d74: mode_show (STB_LOCAL)
ffffffff81812ca0-ffffffff81812d0b: mode_show (STB_LOCAL)
ffffffff81935080-ffffffff819350a6: mode_show (STB_LOCAL)
ffffffff81940230-ffffffff81940272: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810e80e0)
Location: kernel/reboot.c:697
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff818945f0)
Location: drivers/nvdimm/namespace_devs.c:1561
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189d310)
Location: drivers/nvdimm/pfn_devs.c:38
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff819d84a0)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819e4b50)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff810e80e0-ffffffff810e8116: mode_show (STB_LOCAL)
ffffffff818945f0-ffffffff818946a4: mode_show (STB_LOCAL)
ffffffff8189d310-ffffffff8189d37b: mode_show (STB_LOCAL)
ffffffff819d84a0-ffffffff819d84c6: mode_show (STB_LOCAL)
ffffffff819e4b50-ffffffff819e4b92: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81102510)
Location: kernel/reboot.c:1069
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819ddcd0)
Location: drivers/nvdimm/namespace_devs.c:1318
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff819e6c30)
Location: drivers/nvdimm/pfn_devs.c:37
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff81b3b880)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81b49d70)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff81102510-ffffffff81102550: mode_show (STB_LOCAL)
ffffffff819ddcd0-ffffffff819ddd80: mode_show (STB_LOCAL)
ffffffff819e6c30-ffffffff819e6ca2: mode_show (STB_LOCAL)
ffffffff81b3b880-ffffffff81b3b8b0: mode_show (STB_LOCAL)
ffffffff81b49d70-ffffffff81b49dbb: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81127840)
Location: kernel/reboot.c:1086
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b59570)
Location: drivers/nvdimm/namespace_devs.c:1310
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81b62d90)
Location: drivers/nvdimm/pfn_devs.c:39
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff81cd1700)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81ce1520)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff81127840-ffffffff81127880: mode_show (STB_LOCAL)
ffffffff81b59570-ffffffff81b59620: mode_show (STB_LOCAL)
ffffffff81b62d90-ffffffff81b62e02: mode_show (STB_LOCAL)
ffffffff81cd1700-ffffffff81cd1730: mode_show (STB_LOCAL)
ffffffff81ce1520-ffffffff81ce158e: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81134ce0)
Location: kernel/reboot.c:1086
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81bacad0)
Location: drivers/nvdimm/namespace_devs.c:1310
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb6370)
Location: drivers/nvdimm/pfn_devs.c:39
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff81d39140)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81d49790)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff81134ce0-ffffffff81134d20: mode_show (STB_LOCAL)
ffffffff81bacad0-ffffffff81bacb80: mode_show (STB_LOCAL)
ffffffff81bb6370-ffffffff81bb63e2: mode_show (STB_LOCAL)
ffffffff81d39140-ffffffff81d39170: mode_show (STB_LOCAL)
ffffffff81d49790-ffffffff81d497fe: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff8113fcd0)
Location: kernel/reboot.c:1109
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c00e10)
Location: drivers/nvdimm/namespace_devs.c:1319
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0a960)
Location: drivers/nvdimm/pfn_devs.c:39
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff81def3e0)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81e005a0)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff8113fcd0-ffffffff8113fd10: mode_show (STB_LOCAL)
ffffffff81c00e10-ffffffff81c00ec0: mode_show (STB_LOCAL)
ffffffff81c0a960-ffffffff81c0a9d2: mode_show (STB_LOCAL)
ffffffff81def3e0-ffffffff81def410: mode_show (STB_LOCAL)
ffffffff81e005a0-ffffffff81e0060e: mode_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff800010958cd8)
Location: drivers/nvdimm/namespace_devs.c:1581
Inline: False
```
```
In drivers/pps/sysfs.c (ffff800010ac6bf8)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffff800010ad6320)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffff800010958cd8-ffff800010958d6c: mode_show (STB_LOCAL)
ffff800010ac6bf8-ffff800010ac6c3c: mode_show (STB_LOCAL)
ffff800010ad6320-ffff800010ad63c4: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/musb/musb_core.c (c0b64f8c)
Location: drivers/usb/musb/musb_core.c:1720
Inline: False
```
```
In drivers/pps/sysfs.c (c0ba6708)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (c0bb6a04)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
c0b64f8c-c0b64ff0: mode_show (STB_LOCAL)
c0ba6708-c0ba6738: mode_show (STB_LOCAL)
c0bb6a04-c0bb6ab4: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/perf/imc-pmu.c (c00000000012a5e0)
Location: arch/powerpc/perf/imc-pmu.c:55
Inline: False
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a08c90)
Location: drivers/nvdimm/namespace_devs.c:1581
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a157e0)
Location: drivers/nvdimm/pfn_devs.c:49
Inline: True
```
```
In drivers/pps/sysfs.c (c000000000ba8290)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (c000000000bbc560)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
c00000000012a5e0-c00000000012a61c: mode_show (STB_LOCAL)
c000000000a08c90-c000000000a08dbc: mode_show (STB_LOCAL)
c000000000a157e0-c000000000a158b0: mode_show (STB_LOCAL)
c000000000ba8290-c000000000ba82d8: mode_show (STB_LOCAL)
c000000000bbc560-c000000000bbc64c: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c797e)
Location: drivers/nvdimm/namespace_devs.c:1581
Inline: False
```
```
In drivers/pps/sysfs.c (ffffffe0006c56de)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d14dc)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffe0005c797e-ffffffe0005c7a02: mode_show (STB_LOCAL)
ffffffe0006c56de-ffffffe0006c571c: mode_show (STB_LOCAL)
ffffffe0006d14dc-ffffffe0006d1546: mode_show (STB_LOCAL)
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
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8170c060)
Location: drivers/nvdimm/namespace_devs.c:1581
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81715660)
Location: drivers/nvdimm/pfn_devs.c:49
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff81825990)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8182ea30)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff8170c060-ffffffff8170c114: mode_show (STB_LOCAL)
ffffffff81715660-ffffffff817156c2: mode_show (STB_LOCAL)
ffffffff81825990-ffffffff818259b6: mode_show (STB_LOCAL)
ffffffff8182ea30-ffffffff8182eac1: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816dfae0)
Location: drivers/nvdimm/namespace_devs.c:1581
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e90e0)
Location: drivers/nvdimm/pfn_devs.c:49
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff817ed020)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817f60c0)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff816dfae0-ffffffff816dfb94: mode_show (STB_LOCAL)
ffffffff816e90e0-ffffffff816e9142: mode_show (STB_LOCAL)
ffffffff817ed020-ffffffff817ed046: mode_show (STB_LOCAL)
ffffffff817f60c0-ffffffff817f6151: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8174ae30)
Location: drivers/nvdimm/namespace_devs.c:1581
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81754430)
Location: drivers/nvdimm/pfn_devs.c:49
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff818728d0)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8187e060)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff8174ae30-ffffffff8174aee4: mode_show (STB_LOCAL)
ffffffff81754430-ffffffff81754492: mode_show (STB_LOCAL)
ffffffff818728d0-ffffffff818728f6: mode_show (STB_LOCAL)
ffffffff8187e060-ffffffff8187e0f1: mode_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t mode_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff817662b0)
Location: drivers/nvdimm/namespace_devs.c:1581
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176f8a0)
Location: drivers/nvdimm/pfn_devs.c:49
Inline: True
```
```
In drivers/pps/sysfs.c (ffffffff8188e280)
Location: drivers/pps/sysfs.c:46
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81899a90)
Location: drivers/thermal/thermal_sysfs.c:49
Inline: False
```
**Symbols:**

```
ffffffff817662b0-ffffffff81766364: mode_show (STB_LOCAL)
ffffffff8176f8a0-ffffffff8176f902: mode_show (STB_LOCAL)
ffffffff8188e280-ffffffff8188e2a6: mode_show (STB_LOCAL)
ffffffff81899a90-ffffffff81899b21: mode_show (STB_LOCAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
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
<code>char *page</code>
</li>
<li>
<b>Param removed. </b>
<code>char *buf</code>
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
