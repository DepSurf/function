# Function: <code>state_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810cd5b0)
Location: kernel/power/main.c:307
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81598940)
Location: drivers/nvdimm/dimm_devs.c:290
Inline: False
```
```
In drivers/md/md.c (ffffffff8168c720)
Location: drivers/md/md.c:2520
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff816ee290)
Location: drivers/extcon/extcon.c:172
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_update_state
```
```
In net/rfkill/core.c (ffffffff81810d80)
Location: net/rfkill/core.c:699
Inline: False
```
**Symbols:**

```
ffffffff810cd5b0-ffffffff810cd62a: state_show (STB_LOCAL)
ffffffff81598940-ffffffff815989a3: state_show (STB_LOCAL)
ffffffff8168c720-ffffffff8168c975: state_show (STB_LOCAL)
ffffffff816ee290-ffffffff816ee344: state_show (STB_LOCAL)
ffffffff81810d80-ffffffff81810db9: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d2050)
Location: kernel/power/main.c:308
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff815ee310)
Location: drivers/nvdimm/dimm_devs.c:296
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ebfb0)
Location: drivers/watchdog/watchdog_dev.c:441
Inline: True
```
```
In drivers/md/md.c (ffffffff816edde0)
Location: drivers/md/md.c:2524
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff817533c0)
Location: drivers/extcon/extcon.c:160
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_update_state
```
```
In net/rfkill/core.c (ffffffff81883c60)
Location: net/rfkill/core.c:695
Inline: False
```
**Symbols:**

```
ffffffff810d2050-ffffffff810d20d4: state_show (STB_LOCAL)
ffffffff815ee310-ffffffff815ee373: state_show (STB_LOCAL)
ffffffff816ebfb0-ffffffff816ebffc: state_show (STB_LOCAL)
ffffffff816edde0-ffffffff816ee035: state_show (STB_LOCAL)
ffffffff817533c0-ffffffff81753473: state_show (STB_LOCAL)
ffffffff81883c60-ffffffff81883c99: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d8c00)
Location: kernel/power/main.c:380
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8161b350)
Location: drivers/nvdimm/dimm_devs.c:311
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171cfa0)
Location: drivers/watchdog/watchdog_dev.c:480
Inline: True
```
```
In drivers/md/md.c (ffffffff8171f640)
Location: drivers/md/md.c:2562
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8177f370)
Location: drivers/extcon/extcon.c:365
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff818b8500)
Location: net/rfkill/core.c:695
Inline: False
```
**Symbols:**

```
ffffffff810d8c00-ffffffff810d8c84: state_show (STB_LOCAL)
ffffffff8161b350-ffffffff8161b3b3: state_show (STB_LOCAL)
ffffffff8171cfa0-ffffffff8171cfec: state_show (STB_LOCAL)
ffffffff8171f640-ffffffff8171f918: state_show (STB_LOCAL)
ffffffff8177f370-ffffffff8177f428: state_show (STB_LOCAL)
ffffffff818b8500-ffffffff818b8539: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810d7c00)
Location: kernel/power/main.c:380
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8162f3f0)
Location: drivers/nvdimm/dimm_devs.c:327
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81735210)
Location: drivers/watchdog/watchdog_dev.c:488
Inline: True
```
```
In drivers/md/md.c (ffffffff817392c0)
Location: drivers/md/md.c:2624
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8179de30)
Location: drivers/extcon/extcon.c:368
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff818dee50)
Location: net/rfkill/core.c:753
Inline: False
```
**Symbols:**

```
ffffffff810d7c00-ffffffff810d7c89: state_show (STB_LOCAL)
ffffffff8162f3f0-ffffffff8162f453: state_show (STB_LOCAL)
ffffffff81735210-ffffffff8173525c: state_show (STB_LOCAL)
ffffffff817392c0-ffffffff817395ac: state_show (STB_LOCAL)
ffffffff8179de30-ffffffff8179def6: state_show (STB_LOCAL)
ffffffff818dee50-ffffffff818dee8c: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810dfc50)
Location: kernel/power/main.c:435
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81697bd0)
Location: drivers/nvdimm/dimm_devs.c:345
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817a6ee0)
Location: drivers/watchdog/watchdog_dev.c:489
Inline: True
```
```
In drivers/md/md.c (ffffffff817a9130)
Location: drivers/md/md.c:2679
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff81814f90)
Location: drivers/extcon/extcon.c:356
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff81964be0)
Location: net/rfkill/core.c:753
Inline: False
```
**Symbols:**

```
ffffffff810dfc50-ffffffff810dfcd9: state_show (STB_LOCAL)
ffffffff81697bd0-ffffffff81697c33: state_show (STB_LOCAL)
ffffffff817a6ee0-ffffffff817a6f2c: state_show (STB_LOCAL)
ffffffff817a9130-ffffffff817a93f9: state_show (STB_LOCAL)
ffffffff81814f90-ffffffff81815056: state_show (STB_LOCAL)
ffffffff81964be0-ffffffff81964c1c: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810e82f0)
Location: kernel/power/main.c:465
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816d3d30)
Location: drivers/nvdimm/dimm_devs.c:346
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ee950)
Location: drivers/watchdog/watchdog_dev.c:509
Inline: True
```
```
In drivers/md/md.c (ffffffff817f0a70)
Location: drivers/md/md.c:2694
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8185eeb0)
Location: drivers/extcon/extcon.c:356
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff819be480)
Location: net/rfkill/core.c:767
Inline: False
```
**Symbols:**

```
ffffffff810e82f0-ffffffff810e837c: state_show (STB_LOCAL)
ffffffff816d3d30-ffffffff816d3d93: state_show (STB_LOCAL)
ffffffff817ee950-ffffffff817ee99c: state_show (STB_LOCAL)
ffffffff817f0a70-ffffffff817f0d47: state_show (STB_LOCAL)
ffffffff8185eeb0-ffffffff8185ef6e: state_show (STB_LOCAL)
ffffffff819be480-ffffffff819be4bc: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f3900)
Location: kernel/power/main.c:454
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81617c50)
Location: drivers/xen/xenbus/xenbus_probe.c:405
Inline: False
```
```
In drivers/base/memory.c (ffffffff816bd890)
Location: drivers/base/memory.c:149
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5470)
Location: drivers/nvdimm/dimm_devs.c:334
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181a820)
Location: drivers/watchdog/watchdog_dev.c:509
Inline: True
```
```
In drivers/md/md.c (ffffffff8181c960)
Location: drivers/md/md.c:2685
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8187e850)
Location: drivers/extcon/extcon.c:356
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff819f5620)
Location: net/rfkill/core.c:769
Inline: False
```
**Symbols:**

```
ffffffff810f3900-ffffffff810f398c: state_show (STB_LOCAL)
ffffffff81617c50-ffffffff81617c7f: state_show (STB_LOCAL)
ffffffff816bd890-ffffffff816bd918: state_show (STB_LOCAL)
ffffffff816f5470-ffffffff816f54d3: state_show (STB_LOCAL)
ffffffff8181a820-ffffffff8181a86c: state_show (STB_LOCAL)
ffffffff8181c960-ffffffff8181cc41: state_show (STB_LOCAL)
ffffffff8187e850-ffffffff8187e90e: state_show (STB_LOCAL)
ffffffff819f5620-ffffffff819f565c: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/main.c (ffffffff810fbda0)
Location: kernel/power/main.c:466
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164b900)
Location: drivers/xen/xenbus/xenbus_probe.c:405
Inline: False
```
```
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:160
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:331
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185ca10)
Location: drivers/watchdog/watchdog_dev.c:526
Inline: True
```
```
In drivers/md/md.c (ffffffff8185ebb0)
Location: drivers/md/md.c:2748
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff818c8ed0)
Location: drivers/extcon/extcon.c:348
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff81a64d00)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
ffffffff810fbda0-ffffffff810fbe26: state_show (STB_LOCAL)
ffffffff8164b900-ffffffff8164b931: state_show (STB_LOCAL)
ffffffff816f83d0-ffffffff816f8461: state_show (STB_LOCAL)
ffffffff816f92af-ffffffff816f92d1: state_show.cold (STB_LOCAL)
ffffffff8172ed00-ffffffff8172ed60: state_show (STB_LOCAL)
ffffffff817300e8-ffffffff817300f2: state_show.cold (STB_LOCAL)
ffffffff8185ca10-ffffffff8185ca59: state_show (STB_LOCAL)
ffffffff8185ebb0-ffffffff8185ee68: state_show (STB_LOCAL)
ffffffff818c8ed0-ffffffff818c8f78: state_show (STB_LOCAL)
ffffffff81a64d00-ffffffff81a64d42: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81108210)
Location: kernel/power/main.c:552
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166dd90)
Location: drivers/xen/xenbus/xenbus_probe.c:405
Inline: False
```
```
In drivers/base/memory.c (ffffffff8171cc10)
Location: drivers/base/memory.c:129
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81753030)
Location: drivers/nvdimm/dimm_devs.c:331
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188e5c0)
Location: drivers/watchdog/watchdog_dev.c:525
Inline: True
```
```
In drivers/md/md.c (ffffffff81890720)
Location: drivers/md/md.c:2802
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff818f69a0)
Location: drivers/remoteproc/remoteproc_sysfs.c:78
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff818fb320)
Location: drivers/extcon/extcon.c:348
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff81a9b6e0)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
ffffffff81108210-ffffffff81108296: state_show (STB_LOCAL)
ffffffff8166dd90-ffffffff8166ddc1: state_show (STB_LOCAL)
ffffffff8171cc10-ffffffff8171cc98: state_show (STB_LOCAL)
ffffffff81753030-ffffffff81753093: state_show (STB_LOCAL)
ffffffff8188e5c0-ffffffff8188e609: state_show (STB_LOCAL)
ffffffff81890720-ffffffff818909d8: state_show (STB_LOCAL)
ffffffff818f69a0-ffffffff818f69dc: state_show (STB_LOCAL)
ffffffff818fb320-ffffffff818fb3c8: state_show (STB_LOCAL)
ffffffff81a9b6e0-ffffffff81a9b722: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81112d10)
Location: kernel/power/main.c:591
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171df40)
Location: drivers/xen/xenbus/xenbus_probe.c:406
Inline: False
```
```
In drivers/base/memory.c (ffffffff817d88d0)
Location: drivers/base/memory.c:138
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81811920)
Location: drivers/nvdimm/dimm_devs.c:322
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d1c0)
Location: drivers/watchdog/watchdog_dev.c:545
Inline: True
```
```
In drivers/md/md.c (ffffffff8195f5c0)
Location: drivers/md/md.c:2928
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff819ccad0)
Location: drivers/remoteproc/remoteproc_sysfs.c:79
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff819d1c30)
Location: drivers/extcon/extcon.c:348
Inline: False
```
```
In net/rfkill/core.c (ffffffff81b96e80)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
ffffffff81112d10-ffffffff81112d96: state_show (STB_LOCAL)
ffffffff8171df40-ffffffff8171df73: state_show (STB_LOCAL)
ffffffff817d88d0-ffffffff817d8958: state_show (STB_LOCAL)
ffffffff81811920-ffffffff81811980: state_show (STB_LOCAL)
ffffffff8195d1c0-ffffffff8195d209: state_show (STB_LOCAL)
ffffffff8195f5c0-ffffffff8195f885: state_show (STB_LOCAL)
ffffffff819ccad0-ffffffff819ccb0c: state_show (STB_LOCAL)
ffffffff819d1c30-ffffffff819d1cd8: state_show (STB_LOCAL)
ffffffff81b96e80-ffffffff81b96ebb: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff8110fde0)
Location: kernel/power/main.c:591
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8173aeb0)
Location: drivers/xen/xenbus/xenbus_probe.c:407
Inline: False
```
```
In drivers/base/memory.c (ffffffff817ed2a0)
Location: drivers/base/memory.c:139
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff818209d0)
Location: drivers/nvdimm/dimm_devs.c:322
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81963b70)
Location: drivers/watchdog/watchdog_dev.c:546
Inline: True
```
```
In drivers/md/md.c (ffffffff81965e90)
Location: drivers/md/md.c:2949
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff819cc290)
Location: drivers/remoteproc/remoteproc_sysfs.c:180
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff819d1830)
Location: drivers/extcon/extcon.c:348
Inline: False
```
```
In net/rfkill/core.c (ffffffff81ba6b20)
Location: net/rfkill/core.c:779
Inline: False
```
**Symbols:**

```
ffffffff8110fde0-ffffffff8110fe66: state_show (STB_LOCAL)
ffffffff8173aeb0-ffffffff8173aee3: state_show (STB_LOCAL)
ffffffff817ed2a0-ffffffff817ed300: state_show (STB_LOCAL)
ffffffff818209d0-ffffffff81820a30: state_show (STB_LOCAL)
ffffffff81963b70-ffffffff81963bb9: state_show (STB_LOCAL)
ffffffff81965e90-ffffffff81966155: state_show (STB_LOCAL)
ffffffff819cc290-ffffffff819cc2cc: state_show (STB_LOCAL)
ffffffff819d1830-ffffffff819d18d8: state_show (STB_LOCAL)
ffffffff81ba6b20-ffffffff81ba6b5b: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff81110820)
Location: kernel/power/main.c:591
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171e990)
Location: drivers/xen/xenbus/xenbus_probe.c:473
Inline: False
```
```
In drivers/base/memory.c (ffffffff817d1a70)
Location: drivers/base/memory.c:139
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81803cd0)
Location: drivers/nvdimm/dimm_devs.c:322
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81947f90)
Location: drivers/watchdog/watchdog_dev.c:546
Inline: True
```
```
In drivers/md/md.c (ffffffff8194a050)
Location: drivers/md/md.c:2913
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff819b1400)
Location: drivers/remoteproc/remoteproc_sysfs.c:178
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff819b6b10)
Location: drivers/extcon/extcon.c:348
Inline: False
```
```
In net/rfkill/core.c (ffffffff81b95cb0)
Location: net/rfkill/core.c:780
Inline: False
```
**Symbols:**

```
ffffffff81110820-ffffffff811108a6: state_show (STB_LOCAL)
ffffffff8171e990-ffffffff8171e9c3: state_show (STB_LOCAL)
ffffffff817d1a70-ffffffff817d1ad0: state_show (STB_LOCAL)
ffffffff81803cd0-ffffffff81803d30: state_show (STB_LOCAL)
ffffffff81947f90-ffffffff81947fd9: state_show (STB_LOCAL)
ffffffff8194a050-ffffffff8194a2d2: state_show (STB_LOCAL)
ffffffff819b1400-ffffffff819b1439: state_show (STB_LOCAL)
ffffffff819b6b10-ffffffff819b6bb8: state_show (STB_LOCAL)
ffffffff81b95cb0-ffffffff81b95ceb: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810b71f0)
Location: kernel/cpu.c:2266
Inline: False
```
```
In kernel/power/main.c (ffffffff81130210)
Location: kernel/power/main.c:594
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8179d740)
Location: drivers/xen/xenbus/xenbus_probe.c:470
Inline: False
```
```
In drivers/regulator/core.c (ffffffff817a9e70)
Location: drivers/regulator/core.c:657
Inline: False
```
```
In drivers/base/memory.c (ffffffff8185c810)
Location: drivers/base/memory.c:145
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e120)
Location: drivers/nvdimm/dimm_devs.c:322
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ecf40)
Location: drivers/watchdog/watchdog_dev.c:552
Inline: True
```
```
In drivers/md/md.c (ffffffff819ef0d0)
Location: drivers/md/md.c:2923
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81a5fae0)
Location: drivers/remoteproc/remoteproc_sysfs.c:178
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:348
Inline: False
```
```
In net/rfkill/core.c (ffffffff81c62530)
Location: net/rfkill/core.c:780
Inline: False
```
**Symbols:**

```
ffffffff810b71f0-ffffffff810b724c: state_show (STB_LOCAL)
ffffffff81130210-ffffffff81130296: state_show (STB_LOCAL)
ffffffff8179d740-ffffffff8179d773: state_show (STB_LOCAL)
ffffffff817a9e70-ffffffff817aa02e: state_show (STB_LOCAL)
ffffffff8185c810-ffffffff8185c870: state_show (STB_LOCAL)
ffffffff8188e120-ffffffff8188e180: state_show (STB_LOCAL)
ffffffff819ecf40-ffffffff819ecf7e: state_show (STB_LOCAL)
ffffffff819ef0d0-ffffffff819ef352: state_show (STB_LOCAL)
ffffffff81a5fae0-ffffffff81a5fb35: state_show (STB_LOCAL)
ffffffff81a65700-ffffffff81a657f0: state_show (STB_LOCAL)
ffffffff81d33499-ffffffff81d334b2: state_show.cold (STB_LOCAL)
ffffffff81c62530-ffffffff81c6256b: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810cd980)
Location: kernel/cpu.c:2288
Inline: False
```
```
In kernel/power/main.c (ffffffff81151a00)
Location: kernel/power/main.c:568
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff818d6e80)
Location: drivers/xen/xenbus/xenbus_probe.c:471
Inline: False
```
```
In drivers/regulator/core.c (ffffffff818e45e0)
Location: drivers/regulator/core.c:658
Inline: False
```
```
In drivers/base/memory.c (ffffffff819a39d0)
Location: drivers/base/memory.c:145
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7700)
Location: drivers/nvdimm/dimm_devs.c:301
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b53810)
Location: drivers/watchdog/watchdog_dev.c:550
Inline: True
```
```
In drivers/md/md.c (ffffffff81b561c0)
Location: drivers/md/md.c:2913
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81bcfe90)
Location: drivers/remoteproc/remoteproc_sysfs.c:178
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:348
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff81e04d80)
Location: net/rfkill/core.c:780
Inline: False
```
**Symbols:**

```
ffffffff810cd980-ffffffff810cd9e7: state_show (STB_LOCAL)
ffffffff81151a00-ffffffff81151a89: state_show (STB_LOCAL)
ffffffff818d6e80-ffffffff818d6ebc: state_show (STB_LOCAL)
ffffffff818e45e0-ffffffff818e4788: state_show (STB_LOCAL)
ffffffff819a39d0-ffffffff819a3a44: state_show (STB_LOCAL)
ffffffff819d7700-ffffffff819d776a: state_show (STB_LOCAL)
ffffffff81b53810-ffffffff81b53862: state_show (STB_LOCAL)
ffffffff81b561c0-ffffffff81b5644e: state_show (STB_LOCAL)
ffffffff81bcfe90-ffffffff81bcfef0: state_show (STB_LOCAL)
ffffffff81bd6ae0-ffffffff81bd6be7: state_show (STB_LOCAL)
ffffffff81eff976-ffffffff81eff98f: state_show.cold (STB_LOCAL)
ffffffff81e04d80-ffffffff81e04dc5: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810eba90)
Location: kernel/cpu.c:2312
Inline: False
```
```
In kernel/power/main.c (ffffffff81180700)
Location: kernel/power/main.c:572
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a294b0)
Location: drivers/xen/xenbus/xenbus_probe.c:471
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81a39320)
Location: drivers/regulator/core.c:658
Inline: False
```
```
In drivers/base/memory.c (ffffffff81b158f0)
Location: drivers/base/memory.c:145
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52500)
Location: drivers/nvdimm/dimm_devs.c:301
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81cec6b0)
Location: drivers/watchdog/watchdog_dev.c:558
Inline: True
```
```
In drivers/md/md.c (ffffffff81cef600)
Location: drivers/md/md.c:2871
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81d7b000)
Location: drivers/remoteproc/remoteproc_sysfs.c:178
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:358
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff81fd9f70)
Location: net/rfkill/core.c:780
Inline: False
```
**Symbols:**

```
ffffffff810eba90-ffffffff810ebaf7: state_show (STB_LOCAL)
ffffffff81180700-ffffffff81180789: state_show (STB_LOCAL)
ffffffff81a294b0-ffffffff81a294ec: state_show (STB_LOCAL)
ffffffff81a39320-ffffffff81a394c8: state_show (STB_LOCAL)
ffffffff81b158f0-ffffffff81b15964: state_show (STB_LOCAL)
ffffffff81b52500-ffffffff81b5256a: state_show (STB_LOCAL)
ffffffff81cec6b0-ffffffff81cec702: state_show (STB_LOCAL)
ffffffff81cef600-ffffffff81cef89a: state_show (STB_LOCAL)
ffffffff81d7b000-ffffffff81d7b060: state_show (STB_LOCAL)
ffffffff81d83380-ffffffff81d83487: state_show (STB_LOCAL)
ffffffff820aa4df-ffffffff820aa4f8: state_show.cold (STB_LOCAL)
ffffffff81fd9f70-ffffffff81fd9fb5: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810f7770)
Location: kernel/cpu.c:2697
Inline: False
```
```
In kernel/power/main.c (ffffffff811914d0)
Location: kernel/power/main.c:640
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a72bb0)
Location: drivers/xen/xenbus/xenbus_probe.c:471
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81a82f00)
Location: drivers/regulator/core.c:724
Inline: False
```
```
In drivers/base/memory.c (ffffffff81b64660)
Location: drivers/base/memory.c:140
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba5a20)
Location: drivers/nvdimm/dimm_devs.c:301
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff81c9e5d0)
Location: drivers/usb/core/port.c:163
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d553d0)
Location: drivers/watchdog/watchdog_dev.c:578
Inline: True
```
```
In drivers/md/md.c (ffffffff81d583c0)
Location: drivers/md/md.c:2845
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81de91c0)
Location: drivers/remoteproc/remoteproc_sysfs.c:178
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:368
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff82055c30)
Location: net/rfkill/core.c:780
Inline: False
```
**Symbols:**

```
ffffffff810f7770-ffffffff810f77d7: state_show (STB_LOCAL)
ffffffff811914d0-ffffffff81191559: state_show (STB_LOCAL)
ffffffff81a72bb0-ffffffff81a72bec: state_show (STB_LOCAL)
ffffffff81a82f00-ffffffff81a830a8: state_show (STB_LOCAL)
ffffffff81b64660-ffffffff81b646d4: state_show (STB_LOCAL)
ffffffff81ba5a20-ffffffff81ba5a8a: state_show (STB_LOCAL)
ffffffff81c9e5d0-ffffffff81c9e60c: state_show (STB_LOCAL)
ffffffff81d553d0-ffffffff81d55422: state_show (STB_LOCAL)
ffffffff81d583c0-ffffffff81d58662: state_show (STB_LOCAL)
ffffffff81de91c0-ffffffff81de9220: state_show (STB_LOCAL)
ffffffff81df17c0-ffffffff81df18d2: state_show (STB_LOCAL)
ffffffff8212b9ca-ffffffff8212b9e3: state_show.cold (STB_LOCAL)
ffffffff82055c30-ffffffff82055c72: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t state_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff81100b20)
Location: kernel/cpu.c:2751
Inline: False
```
```
In kernel/power/main.c (ffffffff8119fe90)
Location: kernel/power/main.c:624
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac4d10)
Location: drivers/xen/xenbus/xenbus_probe.c:471
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81ad56b0)
Location: drivers/regulator/core.c:726
Inline: False
```
```
In drivers/base/memory.c (ffffffff81bb81e0)
Location: drivers/base/memory.c:141
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bf9ca0)
Location: drivers/nvdimm/dimm_devs.c:303
Inline: False
```
```
In drivers/usb/core/port.c (ffffffff81d531d0)
Location: drivers/usb/core/port.c:163
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c2a0)
Location: drivers/watchdog/watchdog_dev.c:578
Inline: True
```
```
In drivers/md/md.c (ffffffff81e0f240)
Location: drivers/md/md.c:2967
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81e9f400)
Location: drivers/remoteproc/remoteproc_sysfs.c:178
Inline: False
```
```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:368
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff82129790)
Location: net/rfkill/core.c:797
Inline: False
```
**Symbols:**

```
ffffffff81100b20-ffffffff81100b87: state_show (STB_LOCAL)
ffffffff8119fe90-ffffffff8119ff19: state_show (STB_LOCAL)
ffffffff81ac4d10-ffffffff81ac4d4c: state_show (STB_LOCAL)
ffffffff81ad56b0-ffffffff81ad5858: state_show (STB_LOCAL)
ffffffff81bb81e0-ffffffff81bb8254: state_show (STB_LOCAL)
ffffffff81bf9ca0-ffffffff81bf9d0a: state_show (STB_LOCAL)
ffffffff81d531d0-ffffffff81d5320c: state_show (STB_LOCAL)
ffffffff81e0c2a0-ffffffff81e0c2f2: state_show (STB_LOCAL)
ffffffff81e0f240-ffffffff81e0f4e0: state_show (STB_LOCAL)
ffffffff81e9f400-ffffffff81e9f460: state_show (STB_LOCAL)
ffffffff81ea7e10-ffffffff81ea7f22: state_show (STB_LOCAL)
ffffffff8220d65f-ffffffff8220d678: state_show.cold (STB_LOCAL)
ffffffff82129790-ffffffff82129802: state_show (STB_LOCAL)
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
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffff80001016ed28)
Location: kernel/power/main.c:552
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffff800010838900)
Location: drivers/xen/xenbus/xenbus_probe.c:405
Inline: False
```
```
In drivers/base/memory.c (ffff800010910890)
Location: drivers/base/memory.c:129
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffff800010953890)
Location: drivers/nvdimm/dimm_devs.c:331
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adf260)
Location: drivers/watchdog/watchdog_dev.c:525
Inline: True
```
```
In drivers/md/md.c (ffff800010ae2b78)
Location: drivers/md/md.c:2802
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffff800010b82b40)
Location: drivers/remoteproc/remoteproc_sysfs.c:78
Inline: False
```
```
In drivers/extcon/extcon.c (ffff800010b87db8)
Location: drivers/extcon/extcon.c:348
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffff800010d6b570)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
ffff80001016ed28-ffff80001016edac: state_show (STB_LOCAL)
ffff800010838900-ffff800010838948: state_show (STB_LOCAL)
ffff800010910890-ffff800010910960: state_show (STB_LOCAL)
ffff800010953890-ffff800010953914: state_show (STB_LOCAL)
ffff800010adf260-ffff800010adf2d4: state_show (STB_LOCAL)
ffff800010ae2b78-ffff800010ae2e48: state_show (STB_LOCAL)
ffff800010b82b40-ffff800010b82b98: state_show (STB_LOCAL)
ffff800010b87db8-ffff800010b87e8c: state_show (STB_LOCAL)
ffff800010d6b570-ffff800010d6b5c8: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c03ba000)
Location: kernel/power/main.c:552
Inline: False
```
```
In drivers/usb/gadget/udc/core.c (c0b72de8)
Location: drivers/usb/gadget/udc/core.c:1499
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (c0bc0f98)
Location: drivers/watchdog/watchdog_dev.c:525
Inline: True
```
```
In drivers/md/md.c (c0bc40b0)
Location: drivers/md/md.c:2802
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (c0c65ee8)
Location: drivers/remoteproc/remoteproc_sysfs.c:78
Inline: False
```
```
In drivers/extcon/extcon.c (c0c6c80c)
Location: drivers/extcon/extcon.c:348
Inline: False
```
```
In net/rfkill/core.c (c0e699f4)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
c03ba000-c03ba094: state_show (STB_LOCAL)
c0b72de8-c0b72e24: state_show (STB_LOCAL)
c0bc0f98-c0bc1004: state_show (STB_LOCAL)
c0bc40b0-c0bc4380: state_show (STB_LOCAL)
c0c65ee8-c0c65f28: state_show (STB_LOCAL)
c0c6c80c-c0c6c8b8: state_show (STB_LOCAL)
c0e699f4-c0e69a34: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (c0000000001c68e0)
Location: kernel/power/main.c:552
Inline: False
```
```
In drivers/base/memory.c (c0000000009b1810)
Location: drivers/base/memory.c:129
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a00610)
Location: drivers/nvdimm/dimm_devs.c:331
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc7030)
Location: drivers/watchdog/watchdog_dev.c:525
Inline: True
```
```
In drivers/md/md.c (c000000000bca9c0)
Location: drivers/md/md.c:2802
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (c000000000c5fc60)
Location: drivers/remoteproc/remoteproc_sysfs.c:78
Inline: False
```
```
In drivers/extcon/extcon.c (c000000000c66e20)
Location: drivers/extcon/extcon.c:348
Inline: False
```
```
In net/rfkill/core.c (c000000000ea8da0)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
c0000000001c68e0-c0000000001c698c: state_show (STB_LOCAL)
c0000000009b1810-c0000000009b1900: state_show (STB_LOCAL)
c000000000a00610-c000000000a006e8: state_show (STB_LOCAL)
c000000000bc7030-c000000000bc7090: state_show (STB_LOCAL)
c000000000bca9c0-c000000000bcad24: state_show (STB_LOCAL)
c000000000c5fc60-c000000000c5fcc0: state_show (STB_LOCAL)
c000000000c66e20-c000000000c66f48: state_show (STB_LOCAL)
c000000000ea8da0-c000000000ea8dfc: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffe00010d6f8)
Location: kernel/power/main.c:552
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c313c)
Location: drivers/nvdimm/dimm_devs.c:331
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7228)
Location: drivers/watchdog/watchdog_dev.c:525
Inline: True
```
```
In drivers/md/md.c (ffffffe0006d975a)
Location: drivers/md/md.c:2802
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffe00073099e)
Location: drivers/extcon/extcon.c:348
Inline: False
```
```
In net/rfkill/core.c (ffffffe00089ded2)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
ffffffe00010d6f8-ffffffe00010d714: state_show (STB_LOCAL)
ffffffe0006d7228-ffffffe0006d7308: state_show (STB_LOCAL)
ffffffe0006d975a-ffffffe0006d99f2: state_show (STB_LOCAL)
ffffffe00073099e-ffffffe000730a4c: state_show (STB_LOCAL)
ffffffe00089ded2-ffffffe00089df22: state_show (STB_LOCAL)
ffffffe0005c313c-ffffffe0005c31b8: state_show (STB_LOCAL)
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
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811013a0)
Location: kernel/power/main.c:552
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81633ba0)
Location: drivers/xen/xenbus/xenbus_probe.c:406
Inline: False
```
```
In drivers/base/memory.c (ffffffff816e2f40)
Location: drivers/base/memory.c:129
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81707720)
Location: drivers/nvdimm/dimm_devs.c:331
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81834440)
Location: drivers/watchdog/watchdog_dev.c:525
Inline: True
```
```
In drivers/md/md.c (ffffffff818365a0)
Location: drivers/md/md.c:2802
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81897cd0)
Location: drivers/remoteproc/remoteproc_sysfs.c:78
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8189c650)
Location: drivers/extcon/extcon.c:348
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff81a3aa70)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
ffffffff811013a0-ffffffff811013d7: state_show (STB_LOCAL)
ffffffff81633ba0-ffffffff81633bd1: state_show (STB_LOCAL)
ffffffff816e2f40-ffffffff816e2fc8: state_show (STB_LOCAL)
ffffffff81707720-ffffffff81707783: state_show (STB_LOCAL)
ffffffff81834440-ffffffff81834489: state_show (STB_LOCAL)
ffffffff818365a0-ffffffff81836858: state_show (STB_LOCAL)
ffffffff81897cd0-ffffffff81897d0c: state_show (STB_LOCAL)
ffffffff8189c650-ffffffff8189c6f8: state_show (STB_LOCAL)
ffffffff81a3aa70-ffffffff81a3aab2: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810f1710)
Location: kernel/power/main.c:552
Inline: False
```
```
In drivers/base/memory.c (ffffffff816bd580)
Location: drivers/base/memory.c:129
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816db1a0)
Location: drivers/nvdimm/dimm_devs.c:331
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fbad0)
Location: drivers/watchdog/watchdog_dev.c:525
Inline: True
```
```
In drivers/md/md.c (ffffffff817fdc10)
Location: drivers/md/md.c:2802
Inline: False
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184d550)
Location: drivers/hv/vmbus_drv.c:146
Inline: False
```
```
In net/rfkill/core.c (ffffffff819f7690)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
ffffffff810f1710-ffffffff810f1796: state_show (STB_LOCAL)
ffffffff816bd580-ffffffff816bd608: state_show (STB_LOCAL)
ffffffff816db1a0-ffffffff816db203: state_show (STB_LOCAL)
ffffffff817fbad0-ffffffff817fbb19: state_show (STB_LOCAL)
ffffffff817fdc10-ffffffff817fdec8: state_show (STB_LOCAL)
ffffffff8184d550-ffffffff8184d583: state_show (STB_LOCAL)
ffffffff819f7690-ffffffff819f76d2: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff810fe6e0)
Location: kernel/power/main.c:552
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81661bd0)
Location: drivers/xen/xenbus/xenbus_probe.c:405
Inline: False
```
```
In drivers/base/memory.c (ffffffff817100d0)
Location: drivers/base/memory.c:129
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817464f0)
Location: drivers/nvdimm/dimm_devs.c:331
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81883a70)
Location: drivers/watchdog/watchdog_dev.c:525
Inline: True
```
```
In drivers/md/md.c (ffffffff81885bd0)
Location: drivers/md/md.c:2802
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff818ebd40)
Location: drivers/extcon/extcon.c:348
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff81aa6920)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
ffffffff810fe6e0-ffffffff810fe766: state_show (STB_LOCAL)
ffffffff81661bd0-ffffffff81661c01: state_show (STB_LOCAL)
ffffffff817100d0-ffffffff81710158: state_show (STB_LOCAL)
ffffffff817464f0-ffffffff81746553: state_show (STB_LOCAL)
ffffffff81883a70-ffffffff81883ab9: state_show (STB_LOCAL)
ffffffff81885bd0-ffffffff81885e88: state_show (STB_LOCAL)
ffffffff818ebd40-ffffffff818ebde8: state_show (STB_LOCAL)
ffffffff81aa6920-ffffffff81aa6962: state_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t state_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/main.c (ffffffff811099a0)
Location: kernel/power/main.c:552
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167c1a0)
Location: drivers/xen/xenbus/xenbus_probe.c:405
Inline: False
```
```
In drivers/base/memory.c (ffffffff8172b230)
Location: drivers/base/memory.c:129
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81761930)
Location: drivers/nvdimm/dimm_devs.c:331
Inline: False
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189f530)
Location: drivers/watchdog/watchdog_dev.c:525
Inline: True
```
```
In drivers/md/md.c (ffffffff818a1a90)
Location: drivers/md/md.c:2802
Inline: False
```
```
In drivers/remoteproc/remoteproc_sysfs.c (ffffffff81908430)
Location: drivers/remoteproc/remoteproc_sysfs.c:78
Inline: False
```
```
In drivers/extcon/extcon.c (ffffffff8190cdc0)
Location: drivers/extcon/extcon.c:348
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_sync
```
```
In net/rfkill/core.c (ffffffff81ab2cc0)
Location: net/rfkill/core.c:757
Inline: False
```
**Symbols:**

```
ffffffff811099a0-ffffffff81109a26: state_show (STB_LOCAL)
ffffffff8167c1a0-ffffffff8167c1d1: state_show (STB_LOCAL)
ffffffff8172b230-ffffffff8172b2b8: state_show (STB_LOCAL)
ffffffff81761930-ffffffff81761993: state_show (STB_LOCAL)
ffffffff8189f530-ffffffff8189f579: state_show (STB_LOCAL)
ffffffff818a1a90-ffffffff818a1d48: state_show (STB_LOCAL)
ffffffff81908430-ffffffff8190846c: state_show (STB_LOCAL)
ffffffff8190cdc0-ffffffff8190ce68: state_show (STB_LOCAL)
ffffffff81ab2cc0-ffffffff81ab2d02: state_show (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
