# Function: <code>type_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81034a90)
Location: arch/x86/kernel/ksysfs.c:116
Inline: False
```
```
In kernel/events/core.c (ffffffff811793c0)
Location: kernel/events/core.c:7515
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff8146b3c0)
Location: drivers/video/backlight/backlight.c:199
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff814d3e60)
Location: drivers/xen/sys-hypervisor.c:41
Inline: False
```
```
In drivers/regulator/core.c (ffffffff814dba40)
Location: drivers/regulator/core.c:548
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff815523d0)
Location: drivers/base/cacheinfo.c:270
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff81619320)
Location: drivers/usb/core/endpoint.c:58
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81663b00)
Location: drivers/input/serio/serio.c:374
Inline: False
```
```
In drivers/thermal/thermal_core.c (ffffffff816839a0)
Location: drivers/thermal/thermal_core.c:591
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff816c1840)
Location: drivers/mmc/core/bus.c:31
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff816d0440)
Location: drivers/firmware/memmap.c:389
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff816d4990)
Location: drivers/firmware/efi/runtime-map.c:38
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81736190)
Location: net/core/net-sysfs.c:112
Inline: False
```
```
In net/rfkill/core.c (ffffffff81811600)
Location: net/rfkill/core.c:620
Inline: False
```
**Symbols:**

```
ffffffff81034a90-ffffffff81034b36: type_show (STB_LOCAL)
ffffffff811793c0-ffffffff811793e9: type_show (STB_LOCAL)
ffffffff8146b3c0-ffffffff8146b3ed: type_show (STB_LOCAL)
ffffffff814d3e60-ffffffff814d3e7a: type_show (STB_LOCAL)
ffffffff814dba40-ffffffff814dbaa7: type_show (STB_LOCAL)
ffffffff815523d0-ffffffff81552447: type_show (STB_LOCAL)
ffffffff81619320-ffffffff81619352: type_show (STB_LOCAL)
ffffffff81663b00-ffffffff81663b26: type_show (STB_LOCAL)
ffffffff816839a0-ffffffff816839c3: type_show (STB_LOCAL)
ffffffff816c1840-ffffffff816c18b5: type_show (STB_LOCAL)
ffffffff816d0440-ffffffff816d0468: type_show (STB_LOCAL)
ffffffff816d4990-ffffffff816d49b6: type_show (STB_LOCAL)
ffffffff81736190-ffffffff817361aa: type_show (STB_LOCAL)
ffffffff81811600-ffffffff8181162c: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81033c70)
Location: arch/x86/kernel/ksysfs.c:116
Inline: False
```
```
In kernel/events/core.c (ffffffff81189bb0)
Location: kernel/events/core.c:8521
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff814b9710)
Location: drivers/video/backlight/backlight.c:208
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81524440)
Location: drivers/xen/sys-hypervisor.c:41
Inline: False
```
```
In drivers/regulator/core.c (ffffffff8152af90)
Location: drivers/regulator/core.c:524
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff815a4370)
Location: drivers/base/cacheinfo.c:270
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff816794d0)
Location: drivers/usb/core/endpoint.c:58
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff816c3d00)
Location: drivers/input/serio/serio.c:374
Inline: False
```
```
In drivers/thermal/thermal_core.c (ffffffff816e5000)
Location: drivers/thermal/thermal_core.c:591
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff81724470)
Location: drivers/mmc/core/bus.c:31
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff817337d0)
Location: drivers/firmware/memmap.c:389
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff81738350)
Location: drivers/firmware/efi/runtime-map.c:38
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff817a2340)
Location: net/core/net-sysfs.c:112
Inline: False
```
```
In net/rfkill/core.c (ffffffff81883d00)
Location: net/rfkill/core.c:616
Inline: False
```
**Symbols:**

```
ffffffff81033c70-ffffffff81033d16: type_show (STB_LOCAL)
ffffffff81189bb0-ffffffff81189bd9: type_show (STB_LOCAL)
ffffffff814b9710-ffffffff814b973d: type_show (STB_LOCAL)
ffffffff81524440-ffffffff8152445a: type_show (STB_LOCAL)
ffffffff8152af90-ffffffff8152aff7: type_show (STB_LOCAL)
ffffffff815a4370-ffffffff815a43e7: type_show (STB_LOCAL)
ffffffff816794d0-ffffffff81679502: type_show (STB_LOCAL)
ffffffff816c3d00-ffffffff816c3d26: type_show (STB_LOCAL)
ffffffff816e5000-ffffffff816e5023: type_show (STB_LOCAL)
ffffffff81724470-ffffffff817244e5: type_show (STB_LOCAL)
ffffffff817337d0-ffffffff817337f8: type_show (STB_LOCAL)
ffffffff81738350-ffffffff81738376: type_show (STB_LOCAL)
ffffffff817a2340-ffffffff817a235a: type_show (STB_LOCAL)
ffffffff81883d00-ffffffff81883d2a: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff810338a0)
Location: arch/x86/kernel/ksysfs.c:116
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff810e5fd0)
Location: kernel/irq/irqdesc.c:187
Inline: False
```
```
In kernel/events/core.c (ffffffff81198f80)
Location: kernel/events/core.c:8710
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff814db710)
Location: drivers/video/backlight/backlight.c:208
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81550900)
Location: drivers/xen/sys-hypervisor.c:41
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81557590)
Location: drivers/regulator/core.c:525
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff815d2970)
Location: drivers/base/cacheinfo.c:401
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff816a71b0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff816f1cc0)
Location: drivers/input/serio/serio.c:374
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81718ae0)
Location: drivers/thermal/thermal_sysfs.c:29
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff817573f0)
Location: drivers/mmc/core/bus.c:31
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff817667a0)
Location: drivers/firmware/memmap.c:389
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff8176b4f0)
Location: drivers/firmware/efi/runtime-map.c:34
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff817d0c60)
Location: net/core/net-sysfs.c:112
Inline: False
```
```
In net/rfkill/core.c (ffffffff818b85a0)
Location: net/rfkill/core.c:616
Inline: False
```
**Symbols:**

```
ffffffff810338a0-ffffffff81033946: type_show (STB_LOCAL)
ffffffff810e5fd0-ffffffff810e603b: type_show (STB_LOCAL)
ffffffff81198f80-ffffffff81198fa9: type_show (STB_LOCAL)
ffffffff814db710-ffffffff814db73a: type_show (STB_LOCAL)
ffffffff81550900-ffffffff8155091a: type_show (STB_LOCAL)
ffffffff81557590-ffffffff815575f7: type_show (STB_LOCAL)
ffffffff815d2970-ffffffff815d29e8: type_show (STB_LOCAL)
ffffffff816a71b0-ffffffff816a71e2: type_show (STB_LOCAL)
ffffffff816f1cc0-ffffffff816f1ce6: type_show (STB_LOCAL)
ffffffff81718ae0-ffffffff81718b03: type_show (STB_LOCAL)
ffffffff817573f0-ffffffff81757465: type_show (STB_LOCAL)
ffffffff817667a0-ffffffff817667c8: type_show (STB_LOCAL)
ffffffff8176b4f0-ffffffff8176b516: type_show (STB_LOCAL)
ffffffff817d0c60-ffffffff817d0c7a: type_show (STB_LOCAL)
ffffffff818b85a0-ffffffff818b85ca: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81031a20)
Location: arch/x86/kernel/ksysfs.c:116
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff810e5620)
Location: kernel/irq/irqdesc.c:199
Inline: False
```
```
In kernel/events/core.c (ffffffff811a1130)
Location: kernel/events/core.c:8921
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff814e7250)
Location: drivers/video/backlight/backlight.c:213
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81565040)
Location: drivers/xen/sys-hypervisor.c:41
Inline: False
```
```
In drivers/regulator/core.c (ffffffff8156bc60)
Location: drivers/regulator/core.c:525
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff815e7500)
Location: drivers/base/cacheinfo.c:401
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff816bc510)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff817075b0)
Location: drivers/input/serio/serio.c:374
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81730d80)
Location: drivers/thermal/thermal_sysfs.c:29
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff81775290)
Location: drivers/mmc/core/bus.c:33
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff81784fc0)
Location: drivers/firmware/memmap.c:389
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff81789930)
Location: drivers/firmware/efi/runtime-map.c:34
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff817f04d0)
Location: net/core/net-sysfs.c:113
Inline: False
```
```
In net/rfkill/core.c (ffffffff818deef0)
Location: net/rfkill/core.c:674
Inline: False
```
**Symbols:**

```
ffffffff81031a20-ffffffff81031ac6: type_show (STB_LOCAL)
ffffffff810e5620-ffffffff810e568b: type_show (STB_LOCAL)
ffffffff811a1130-ffffffff811a1159: type_show (STB_LOCAL)
ffffffff814e7250-ffffffff814e727a: type_show (STB_LOCAL)
ffffffff81565040-ffffffff8156505a: type_show (STB_LOCAL)
ffffffff8156bc60-ffffffff8156bcc7: type_show (STB_LOCAL)
ffffffff815e7500-ffffffff815e7578: type_show (STB_LOCAL)
ffffffff816bc510-ffffffff816bc542: type_show (STB_LOCAL)
ffffffff817075b0-ffffffff817075d9: type_show (STB_LOCAL)
ffffffff81730d80-ffffffff81730da3: type_show (STB_LOCAL)
ffffffff81775290-ffffffff81775305: type_show (STB_LOCAL)
ffffffff81784fc0-ffffffff81784fe8: type_show (STB_LOCAL)
ffffffff81789930-ffffffff81789956: type_show (STB_LOCAL)
ffffffff817f04d0-ffffffff817f04ea: type_show (STB_LOCAL)
ffffffff818deef0-ffffffff818def1a: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81033cc0)
Location: arch/x86/kernel/ksysfs.c:116
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff810ed8e0)
Location: kernel/irq/irqdesc.c:197
Inline: False
```
```
In kernel/events/core.c (ffffffff811b4c80)
Location: kernel/events/core.c:8937
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff8151bd40)
Location: drivers/video/backlight/backlight.c:213
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff815c91e0)
Location: drivers/xen/sys-hypervisor.c:41
Inline: False
```
```
In drivers/regulator/core.c (ffffffff815cfe90)
Location: drivers/regulator/core.c:525
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff8164e8d0)
Location: drivers/base/cacheinfo.c:414
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff81727ee0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81778790)
Location: drivers/input/serio/serio.c:374
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817a1e10)
Location: drivers/thermal/thermal_sysfs.c:29
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff817eb570)
Location: drivers/mmc/core/bus.c:33
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff817fb330)
Location: drivers/firmware/memmap.c:389
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff817ffd80)
Location: drivers/firmware/efi/runtime-map.c:34
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff8186bad0)
Location: net/core/net-sysfs.c:114
Inline: False
```
```
In net/rfkill/core.c (ffffffff81964c80)
Location: net/rfkill/core.c:674
Inline: False
```
**Symbols:**

```
ffffffff81033cc0-ffffffff81033d6b: type_show (STB_LOCAL)
ffffffff810ed8e0-ffffffff810ed94b: type_show (STB_LOCAL)
ffffffff811b4c80-ffffffff811b4ca9: type_show (STB_LOCAL)
ffffffff8151bd40-ffffffff8151bd6a: type_show (STB_LOCAL)
ffffffff815c91e0-ffffffff815c91fa: type_show (STB_LOCAL)
ffffffff815cfe90-ffffffff815cfef7: type_show (STB_LOCAL)
ffffffff8164e8d0-ffffffff8164e948: type_show (STB_LOCAL)
ffffffff81727ee0-ffffffff81727f12: type_show (STB_LOCAL)
ffffffff81778790-ffffffff817787b9: type_show (STB_LOCAL)
ffffffff817a1e10-ffffffff817a1e33: type_show (STB_LOCAL)
ffffffff817eb570-ffffffff817eb5e5: type_show (STB_LOCAL)
ffffffff817fb330-ffffffff817fb358: type_show (STB_LOCAL)
ffffffff817ffd80-ffffffff817ffda6: type_show (STB_LOCAL)
ffffffff8186bad0-ffffffff8186baea: type_show (STB_LOCAL)
ffffffff81964c80-ffffffff81964caa: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81034ff0)
Location: arch/x86/kernel/ksysfs.c:116
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff810f5d20)
Location: kernel/irq/irqdesc.c:197
Inline: False
```
```
In kernel/events/core.c (ffffffff811d3ae0)
Location: kernel/events/core.c:9459
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff815519f0)
Location: drivers/video/backlight/backlight.c:213
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81601a80)
Location: drivers/xen/sys-hypervisor.c:41
Inline: False
```
```
In drivers/regulator/core.c (ffffffff8160aa40)
Location: drivers/regulator/core.c:595
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff8168a030)
Location: drivers/base/cacheinfo.c:404
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff81766d40)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff817b94f0)
Location: drivers/input/serio/serio.c:374
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817e9300)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff818346d0)
Location: drivers/mmc/core/bus.c:33
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff81844a80)
Location: drivers/firmware/memmap.c:389
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff818494e0)
Location: drivers/firmware/efi/runtime-map.c:34
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff818bc240)
Location: net/core/net-sysfs.c:114
Inline: False
```
```
In net/rfkill/core.c (ffffffff819be520)
Location: net/rfkill/core.c:688
Inline: False
```
**Symbols:**

```
ffffffff81034ff0-ffffffff8103509b: type_show (STB_LOCAL)
ffffffff810f5d20-ffffffff810f5d8b: type_show (STB_LOCAL)
ffffffff811d3ae0-ffffffff811d3b09: type_show (STB_LOCAL)
ffffffff815519f0-ffffffff81551a1a: type_show (STB_LOCAL)
ffffffff81601a80-ffffffff81601a9a: type_show (STB_LOCAL)
ffffffff8160aa40-ffffffff8160aaa7: type_show (STB_LOCAL)
ffffffff8168a030-ffffffff8168a0a8: type_show (STB_LOCAL)
ffffffff81766d40-ffffffff81766d72: type_show (STB_LOCAL)
ffffffff817b94f0-ffffffff817b9519: type_show (STB_LOCAL)
ffffffff817e9300-ffffffff817e9323: type_show (STB_LOCAL)
ffffffff818346d0-ffffffff81834747: type_show (STB_LOCAL)
ffffffff81844a80-ffffffff81844aa8: type_show (STB_LOCAL)
ffffffff818494e0-ffffffff81849506: type_show (STB_LOCAL)
ffffffff818bc240-ffffffff818bc25a: type_show (STB_LOCAL)
ffffffff819be520-ffffffff819be54a: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff810361d0)
Location: arch/x86/kernel/ksysfs.c:116
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff811014b0)
Location: kernel/irq/irqdesc.c:197
Inline: False
```
```
In kernel/events/core.c (ffffffff811e3eb0)
Location: kernel/events/core.c:9502
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff81569280)
Location: drivers/video/backlight/backlight.c:213
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8161cb70)
Location: drivers/xen/sys-hypervisor.c:41
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81623710)
Location: drivers/regulator/core.c:786
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff816a9530)
Location: drivers/base/cacheinfo.c:398
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff8178b2c0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff817e0900)
Location: drivers/input/serio/serio.c:370
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff818151b0)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff81860660)
Location: drivers/mmc/core/bus.c:33
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff81870aa0)
Location: drivers/firmware/memmap.c:390
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff81875750)
Location: drivers/firmware/efi/runtime-map.c:34
Inline: False
```
```
In drivers/nvmem/core.c (ffffffff81886220)
Location: drivers/nvmem/core.c:94
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff818e2ec0)
Location: net/core/net-sysfs.c:115
Inline: False
```
```
In net/rfkill/core.c (ffffffff819f56c0)
Location: net/rfkill/core.c:690
Inline: False
```
**Symbols:**

```
ffffffff810361d0-ffffffff8103627b: type_show (STB_LOCAL)
ffffffff811014b0-ffffffff8110151b: type_show (STB_LOCAL)
ffffffff811e3eb0-ffffffff811e3ed9: type_show (STB_LOCAL)
ffffffff81569280-ffffffff815692aa: type_show (STB_LOCAL)
ffffffff8161cb70-ffffffff8161cb8a: type_show (STB_LOCAL)
ffffffff81623710-ffffffff81623777: type_show (STB_LOCAL)
ffffffff816a9530-ffffffff816a95a8: type_show (STB_LOCAL)
ffffffff8178b2c0-ffffffff8178b2f2: type_show (STB_LOCAL)
ffffffff817e0900-ffffffff817e0929: type_show (STB_LOCAL)
ffffffff818151b0-ffffffff818151d3: type_show (STB_LOCAL)
ffffffff81860660-ffffffff818606d7: type_show (STB_LOCAL)
ffffffff81870aa0-ffffffff81870ac8: type_show (STB_LOCAL)
ffffffff81875750-ffffffff81875776: type_show (STB_LOCAL)
ffffffff81886220-ffffffff8188624d: type_show (STB_LOCAL)
ffffffff818e2ec0-ffffffff818e2eda: type_show (STB_LOCAL)
ffffffff819f56c0-ffffffff819f56ea: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81038330)
Location: arch/x86/kernel/ksysfs.c:115
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff81109cb0)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff811fb080)
Location: kernel/events/core.c:9805
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff81599b10)
Location: drivers/video/backlight/backlight.c:214
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8164fdb0)
Location: drivers/xen/sys-hypervisor.c:38
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81655a10)
Location: drivers/regulator/core.c:768
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff816e2b10)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff817c98c0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff818211d0)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff818573d0)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff818a4380)
Location: drivers/mmc/core/bus.c:30
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff818b4d50)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff818b9940)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/nvmem-sysfs.c (ffffffff818d1f20)
Location: drivers/nvmem/nvmem-sysfs.c:18
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff819324d0)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (ffffffff81a64db0)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
ffffffff81038330-ffffffff810383df: type_show (STB_LOCAL)
ffffffff81109cb0-ffffffff81109d1a: type_show (STB_LOCAL)
ffffffff811fb080-ffffffff811fb0a6: type_show (STB_LOCAL)
ffffffff81599b10-ffffffff81599b3b: type_show (STB_LOCAL)
ffffffff8164fdb0-ffffffff8164fdca: type_show (STB_LOCAL)
ffffffff81655a10-ffffffff81655a74: type_show (STB_LOCAL)
ffffffff816e2b10-ffffffff816e2b85: type_show (STB_LOCAL)
ffffffff817c98c0-ffffffff817c9901: type_show (STB_LOCAL)
ffffffff818211d0-ffffffff818211fa: type_show (STB_LOCAL)
ffffffff818573d0-ffffffff818573f3: type_show (STB_LOCAL)
ffffffff818a4380-ffffffff818a43f4: type_show (STB_LOCAL)
ffffffff818b4d50-ffffffff818b4d78: type_show (STB_LOCAL)
ffffffff818b9940-ffffffff818b9967: type_show (STB_LOCAL)
ffffffff818d1f20-ffffffff818d1f4e: type_show (STB_LOCAL)
ffffffff819324d0-ffffffff819324ea: type_show (STB_LOCAL)
ffffffff81a64db0-ffffffff81a64ddb: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81038b00)
Location: arch/x86/kernel/ksysfs.c:115
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff81116080)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff81208150)
Location: kernel/events/core.c:9921
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff815baeb0)
Location: drivers/video/backlight/backlight.c:220
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81672350)
Location: drivers/xen/sys-hypervisor.c:38
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81677f40)
Location: drivers/regulator/core.c:774
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff81706cc0)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff817fa400)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81852640)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81888e80)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff818d6800)
Location: drivers/mmc/core/bus.c:30
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff818e7670)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff818ec3e0)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/nvmem-sysfs.c (ffffffff819042d0)
Location: drivers/nvmem/nvmem-sysfs.c:18
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81965010)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (ffffffff81a9b790)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
ffffffff81038b00-ffffffff81038baf: type_show (STB_LOCAL)
ffffffff81116080-ffffffff811160ea: type_show (STB_LOCAL)
ffffffff81208150-ffffffff81208176: type_show (STB_LOCAL)
ffffffff815baeb0-ffffffff815baedb: type_show (STB_LOCAL)
ffffffff81672350-ffffffff8167236a: type_show (STB_LOCAL)
ffffffff81677f40-ffffffff81677fa4: type_show (STB_LOCAL)
ffffffff81706cc0-ffffffff81706d35: type_show (STB_LOCAL)
ffffffff817fa400-ffffffff817fa441: type_show (STB_LOCAL)
ffffffff81852640-ffffffff8185266a: type_show (STB_LOCAL)
ffffffff81888e80-ffffffff81888ea3: type_show (STB_LOCAL)
ffffffff818d6800-ffffffff818d6874: type_show (STB_LOCAL)
ffffffff818e7670-ffffffff818e7698: type_show (STB_LOCAL)
ffffffff818ec3e0-ffffffff818ec407: type_show (STB_LOCAL)
ffffffff819042d0-ffffffff819042fe: type_show (STB_LOCAL)
ffffffff81965010-ffffffff8196502a: type_show (STB_LOCAL)
ffffffff81a9b790-ffffffff81a9b7bb: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff8103b610)
Location: arch/x86/kernel/ksysfs.c:120
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff81121d30)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff81230e50)
Location: kernel/events/core.c:10469
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff81664d70)
Location: drivers/video/backlight/backlight.c:220
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81722a20)
Location: drivers/xen/sys-hypervisor.c:38
Inline: False
```
```
In drivers/regulator/core.c (ffffffff817280f0)
Location: drivers/regulator/core.c:777
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757770)
Location: drivers/tty/serial/serial_core.c:2629
Inline: False
```
```
In drivers/base/cacheinfo.c (ffffffff817c19b0)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff818ca620)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff819244f0)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81957890)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff819a90e0)
Location: drivers/mmc/core/bus.c:30
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff819baad0)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff819bfc00)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/core.c (ffffffff819d9c80)
Location: drivers/nvmem/core.c:105
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81a38ff0)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (ffffffff81b96f20)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
ffffffff8103b610-ffffffff8103b731: type_show (STB_LOCAL)
ffffffff81121d30-ffffffff81121d9a: type_show (STB_LOCAL)
ffffffff81230e50-ffffffff81230e76: type_show (STB_LOCAL)
ffffffff81664d70-ffffffff81664d9b: type_show (STB_LOCAL)
ffffffff81722a20-ffffffff81722a3a: type_show (STB_LOCAL)
ffffffff817280f0-ffffffff81728154: type_show (STB_LOCAL)
ffffffff81757770-ffffffff817577d1: type_show (STB_LOCAL)
ffffffff817c19b0-ffffffff817c1a25: type_show (STB_LOCAL)
ffffffff818ca620-ffffffff818ca663: type_show (STB_LOCAL)
ffffffff819244f0-ffffffff8192451a: type_show (STB_LOCAL)
ffffffff81957890-ffffffff819578b3: type_show (STB_LOCAL)
ffffffff819a90e0-ffffffff819a9154: type_show (STB_LOCAL)
ffffffff819baad0-ffffffff819baaf8: type_show (STB_LOCAL)
ffffffff819bfc00-ffffffff819bfc27: type_show (STB_LOCAL)
ffffffff819d9c80-ffffffff819d9cae: type_show (STB_LOCAL)
ffffffff81a38ff0-ffffffff81a3904b: type_show (STB_LOCAL)
ffffffff81b96f20-ffffffff81b96f4b: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff8103bdc0)
Location: arch/x86/kernel/ksysfs.c:120
Inline: False
```
```
In kernel/reboot.c (ffffffff810d3190)
Location: kernel/reboot.c:692
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff8111dd90)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff8123aa60)
Location: kernel/events/core.c:10751
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff81685a00)
Location: drivers/video/backlight/backlight.c:270
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff8173f680)
Location: drivers/xen/sys-hypervisor.c:38
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81744ca0)
Location: drivers/regulator/core.c:800
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81772850)
Location: drivers/tty/serial/serial_core.c:2636
Inline: False
```
```
In drivers/base/cacheinfo.c (ffffffff817d6bc0)
Location: drivers/base/cacheinfo.c:401
Inline: False
```
```
In drivers/usb/core/endpoint.c (ffffffff818d5730)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff8192c2a0)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8195ceb0)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff819abfd0)
Location: drivers/mmc/core/bus.c:30
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff819bce40)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff819c0ba0)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/core.c (ffffffff819d8f30)
Location: drivers/nvmem/core.c:189
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81a3ae20)
Location: net/core/net-sysfs.c:111
Inline: False
```
```
In net/rfkill/core.c (ffffffff81ba6bc0)
Location: net/rfkill/core.c:690
Inline: False
```
**Symbols:**

```
ffffffff8103bdc0-ffffffff8103bee1: type_show (STB_LOCAL)
ffffffff810d3190-ffffffff810d31c9: type_show (STB_LOCAL)
ffffffff8111dd90-ffffffff8111ddfa: type_show (STB_LOCAL)
ffffffff8123aa60-ffffffff8123aa86: type_show (STB_LOCAL)
ffffffff81685a00-ffffffff81685a2b: type_show (STB_LOCAL)
ffffffff8173f680-ffffffff8173f69a: type_show (STB_LOCAL)
ffffffff81744ca0-ffffffff81744d04: type_show (STB_LOCAL)
ffffffff81772850-ffffffff817728ac: type_show (STB_LOCAL)
ffffffff817d6bc0-ffffffff817d6c16: type_show (STB_LOCAL)
ffffffff818d5730-ffffffff818d5773: type_show (STB_LOCAL)
ffffffff8192c2a0-ffffffff8192c2ca: type_show (STB_LOCAL)
ffffffff8195ceb0-ffffffff8195ced3: type_show (STB_LOCAL)
ffffffff819abfd0-ffffffff819ac044: type_show (STB_LOCAL)
ffffffff819bce40-ffffffff819bce68: type_show (STB_LOCAL)
ffffffff819c0ba0-ffffffff819c0bc7: type_show (STB_LOCAL)
ffffffff819d8f30-ffffffff819d8f5e: type_show (STB_LOCAL)
ffffffff81a3ae20-ffffffff81a3ae7b: type_show (STB_LOCAL)
ffffffff81ba6bc0-ffffffff81ba6bee: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff8103d760)
Location: arch/x86/kernel/ksysfs.c:120
Inline: False
```
```
In kernel/reboot.c (ffffffff810d4e80)
Location: kernel/reboot.c:692
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff8111dfb0)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff8123f230)
Location: kernel/events/core.c:10881
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff81668800)
Location: drivers/video/backlight/backlight.c:270
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff81691d10)
Location: drivers/acpi/dock.c:550
Inline: False
```
```
In drivers/acpi/bgrt.c (ffffffff816e9640)
Location: drivers/acpi/bgrt.c:28
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff817230d0)
Location: drivers/xen/sys-hypervisor.c:38
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81728640)
Location: drivers/regulator/core.c:801
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff817562e0)
Location: drivers/tty/serial/serial_core.c:2633
Inline: False
```
```
In drivers/base/cacheinfo.c (ffffffff817ba680)
Location: drivers/base/cacheinfo.c:401
Inline: False
```
```
In drivers/usb/core/endpoint.c (ffffffff818b8cf0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff8190f7a0)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819404b0)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff81990410)
Location: drivers/mmc/core/bus.c:30
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff819a15e0)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff819a52a0)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/core.c (ffffffff819bf080)
Location: drivers/nvmem/core.c:189
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81a22240)
Location: net/core/net-sysfs.c:111
Inline: False
```
```
In net/rfkill/core.c (ffffffff81b95d50)
Location: net/rfkill/core.c:691
Inline: False
```
**Symbols:**

```
ffffffff8103d760-ffffffff8103d881: type_show (STB_LOCAL)
ffffffff810d4e80-ffffffff810d4eb9: type_show (STB_LOCAL)
ffffffff8111dfb0-ffffffff8111e01a: type_show (STB_LOCAL)
ffffffff8123f230-ffffffff8123f256: type_show (STB_LOCAL)
ffffffff81668800-ffffffff8166882b: type_show (STB_LOCAL)
ffffffff81691d10-ffffffff81691d67: type_show (STB_LOCAL)
ffffffff816e9640-ffffffff816e9668: type_show (STB_LOCAL)
ffffffff817230d0-ffffffff817230ea: type_show (STB_LOCAL)
ffffffff81728640-ffffffff817286a4: type_show (STB_LOCAL)
ffffffff817562e0-ffffffff8175633c: type_show (STB_LOCAL)
ffffffff817ba680-ffffffff817ba6d4: type_show (STB_LOCAL)
ffffffff818b8cf0-ffffffff818b8d33: type_show (STB_LOCAL)
ffffffff8190f7a0-ffffffff8190f7ca: type_show (STB_LOCAL)
ffffffff819404b0-ffffffff819404d3: type_show (STB_LOCAL)
ffffffff81990410-ffffffff81990484: type_show (STB_LOCAL)
ffffffff819a15e0-ffffffff819a1608: type_show (STB_LOCAL)
ffffffff819a52a0-ffffffff819a52c7: type_show (STB_LOCAL)
ffffffff819bf080-ffffffff819bf0ae: type_show (STB_LOCAL)
ffffffff81a22240-ffffffff81a22297: type_show (STB_LOCAL)
ffffffff81b95d50-ffffffff81b95d7e: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff810433b0)
Location: arch/x86/kernel/ksysfs.c:135
Inline: False
```
```
In kernel/reboot.c (ffffffff810e8070)
Location: kernel/reboot.c:771
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff8113e430)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff81279da0)
Location: kernel/events/core.c:10993
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff816dbb10)
Location: drivers/video/backlight/backlight.c:270
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff81707820)
Location: drivers/acpi/dock.c:550
Inline: False
```
```
In drivers/acpi/bgrt.c (ffffffff81762c90)
Location: drivers/acpi/bgrt.c:28
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff817a1f30)
Location: drivers/xen/sys-hypervisor.c:38
Inline: False
```
```
In drivers/regulator/core.c (ffffffff817a76e0)
Location: drivers/regulator/core.c:791
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff817d9a10)
Location: drivers/tty/serial/serial_core.c:2648
Inline: False
```
```
In drivers/base/cacheinfo.c (ffffffff81844410)
Location: drivers/base/cacheinfo.c:402
Inline: False
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81919700)
Location: drivers/net/wwan/wwan_core.c:257
Inline: False
```
```
In drivers/usb/core/endpoint.c (ffffffff8194e7b0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff819b05a0)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff819e4dd0)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff81a3bc30)
Location: drivers/mmc/core/bus.c:30
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81a4e580)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff81a525f0)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/core.c (ffffffff81a6e530)
Location: drivers/nvmem/core.c:190
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81ad68c0)
Location: net/core/net-sysfs.c:111
Inline: False
```
```
In net/rfkill/core.c (ffffffff81c625a0)
Location: net/rfkill/core.c:691
Inline: False
```
**Symbols:**

```
ffffffff810433b0-ffffffff810434f6: type_show (STB_LOCAL)
ffffffff810e8070-ffffffff810e80a9: type_show (STB_LOCAL)
ffffffff8113e430-ffffffff8113e49a: type_show (STB_LOCAL)
ffffffff81279da0-ffffffff81279dc6: type_show (STB_LOCAL)
ffffffff816dbb10-ffffffff816dbb57: type_show (STB_LOCAL)
ffffffff81707820-ffffffff81707877: type_show (STB_LOCAL)
ffffffff81762c90-ffffffff81762cb3: type_show (STB_LOCAL)
ffffffff817a1f30-ffffffff817a1f4a: type_show (STB_LOCAL)
ffffffff817a76e0-ffffffff817a7744: type_show (STB_LOCAL)
ffffffff817d9a10-ffffffff817d9a6c: type_show (STB_LOCAL)
ffffffff81844410-ffffffff81844464: type_show (STB_LOCAL)
ffffffff81919700-ffffffff8191974a: type_show (STB_LOCAL)
ffffffff8194e7b0-ffffffff8194e7f3: type_show (STB_LOCAL)
ffffffff819b05a0-ffffffff819b05ca: type_show (STB_LOCAL)
ffffffff819e4dd0-ffffffff819e4df3: type_show (STB_LOCAL)
ffffffff81a3bc30-ffffffff81a3bca4: type_show (STB_LOCAL)
ffffffff81a4e580-ffffffff81a4e5a8: type_show (STB_LOCAL)
ffffffff81a525f0-ffffffff81a52617: type_show (STB_LOCAL)
ffffffff81a6e530-ffffffff81a6e57a: type_show (STB_LOCAL)
ffffffff81ad68c0-ffffffff81ad6917: type_show (STB_LOCAL)
ffffffff81c625a0-ffffffff81c625ea: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff8104b2e0)
Location: arch/x86/kernel/ksysfs.c:135
Inline: False
```
```
In kernel/reboot.c (ffffffff81102490)
Location: kernel/reboot.c:1143
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff81161120)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff812cd160)
Location: kernel/events/core.c:10929
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff818057f0)
Location: drivers/video/backlight/backlight.c:270
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff81835bd0)
Location: drivers/acpi/dock.c:549
Inline: False
```
```
In drivers/acpi/bgrt.c (ffffffff818968d0)
Location: drivers/acpi/bgrt.c:28
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff818dc030)
Location: drivers/xen/sys-hypervisor.c:37
Inline: False
```
```
In drivers/regulator/core.c (ffffffff818e1d20)
Location: drivers/regulator/core.c:792
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81918400)
Location: drivers/tty/serial/serial_core.c:2695
Inline: False
```
```
In drivers/base/cacheinfo.c (ffffffff81988750)
Location: drivers/base/cacheinfo.c:402
Inline: False
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6e750)
Location: drivers/net/wwan/wwan_core.c:323
Inline: False
```
```
In drivers/usb/core/endpoint.c (ffffffff81aa77a0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81b0f340)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81b4a070)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff81ba8c10)
Location: drivers/mmc/core/bus.c:31
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81bbd080)
Location: drivers/firmware/memmap.c:382
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff81bc1740)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/core.c (ffffffff81bdf440)
Location: drivers/nvmem/core.c:195
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81c56c10)
Location: net/core/net-sysfs.c:113
Inline: False
```
```
In net/rfkill/core.c (ffffffff81e04e00)
Location: net/rfkill/core.c:691
Inline: False
```
**Symbols:**

```
ffffffff8104b2e0-ffffffff8104b43a: type_show (STB_LOCAL)
ffffffff81102490-ffffffff811024d3: type_show (STB_LOCAL)
ffffffff81161120-ffffffff8116118b: type_show (STB_LOCAL)
ffffffff812cd160-ffffffff812cd197: type_show (STB_LOCAL)
ffffffff818057f0-ffffffff81805842: type_show (STB_LOCAL)
ffffffff81835bd0-ffffffff81835c44: type_show (STB_LOCAL)
ffffffff818968d0-ffffffff818968fd: type_show (STB_LOCAL)
ffffffff818dc030-ffffffff818dc050: type_show (STB_LOCAL)
ffffffff818e1d20-ffffffff818e1d9c: type_show (STB_LOCAL)
ffffffff81918400-ffffffff81918478: type_show (STB_LOCAL)
ffffffff81988750-ffffffff819887bc: type_show (STB_LOCAL)
ffffffff81a6e750-ffffffff81a6e7a4: type_show (STB_LOCAL)
ffffffff81aa77a0-ffffffff81aa77ed: type_show (STB_LOCAL)
ffffffff81b0f340-ffffffff81b0f373: type_show (STB_LOCAL)
ffffffff81b4a070-ffffffff81b4a09d: type_show (STB_LOCAL)
ffffffff81ba8c10-ffffffff81ba8cb0: type_show (STB_LOCAL)
ffffffff81bbd080-ffffffff81bbd0b4: type_show (STB_LOCAL)
ffffffff81bc1740-ffffffff81bc1772: type_show (STB_LOCAL)
ffffffff81bdf440-ffffffff81bdf495: type_show (STB_LOCAL)
ffffffff81c56c10-ffffffff81c56c74: type_show (STB_LOCAL)
ffffffff81e04e00-ffffffff81e04e55: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81057010)
Location: arch/x86/kernel/ksysfs.c:135
Inline: False
```
```
In arch/x86/platform/efi/runtime-map.c (ffffffff810d9c30)
Location: arch/x86/platform/efi/runtime-map.c:33
Inline: False
```
```
In kernel/reboot.c (ffffffff811277a0)
Location: kernel/reboot.c:1160
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff81194730)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff81335230)
Location: kernel/events/core.c:11268
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff81934160)
Location: drivers/video/backlight/backlight.c:270
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff81969b80)
Location: drivers/acpi/dock.c:549
Inline: False
```
```
In drivers/acpi/bgrt.c (ffffffff819de8e0)
Location: drivers/acpi/bgrt.c:28
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81a2f250)
Location: drivers/xen/sys-hypervisor.c:37
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81a36fd0)
Location: drivers/regulator/core.c:792
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a73e00)
Location: drivers/tty/serial/serial_core.c:2829
Inline: False
```
```
In drivers/base/cacheinfo.c (ffffffff81af7030)
Location: drivers/base/cacheinfo.c:454
Inline: False
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c017d0)
Location: drivers/net/wwan/wwan_core.c:328
Inline: False
```
```
In drivers/usb/core/endpoint.c (ffffffff81c2e680)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81c9f740)
Location: drivers/input/serio/serio.c:355
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81ce18e0)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff81d4b570)
Location: drivers/mmc/core/bus.c:31
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81d62b10)
Location: drivers/firmware/memmap.c:382
Inline: False
```
```
In drivers/nvmem/core.c (ffffffff81d8aa70)
Location: drivers/nvmem/core.c:195
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81e0c700)
Location: net/core/net-sysfs.c:113
Inline: False
```
```
In net/rfkill/core.c (ffffffff81fda010)
Location: net/rfkill/core.c:691
Inline: False
```
**Symbols:**

```
ffffffff81057010-ffffffff8105716a: type_show (STB_LOCAL)
ffffffff810d9c30-ffffffff810d9c62: type_show (STB_LOCAL)
ffffffff811277a0-ffffffff811277e3: type_show (STB_LOCAL)
ffffffff81194730-ffffffff8119479b: type_show (STB_LOCAL)
ffffffff81335230-ffffffff81335267: type_show (STB_LOCAL)
ffffffff81934160-ffffffff819341b2: type_show (STB_LOCAL)
ffffffff81969b80-ffffffff81969bf4: type_show (STB_LOCAL)
ffffffff819de8e0-ffffffff819de90d: type_show (STB_LOCAL)
ffffffff81a2f250-ffffffff81a2f270: type_show (STB_LOCAL)
ffffffff81a36fd0-ffffffff81a3704c: type_show (STB_LOCAL)
ffffffff81a73e00-ffffffff81a73e78: type_show (STB_LOCAL)
ffffffff81af7030-ffffffff81af709c: type_show (STB_LOCAL)
ffffffff81c017d0-ffffffff81c01824: type_show (STB_LOCAL)
ffffffff81c2e680-ffffffff81c2e6cd: type_show (STB_LOCAL)
ffffffff81c9f740-ffffffff81c9f773: type_show (STB_LOCAL)
ffffffff81ce18e0-ffffffff81ce190d: type_show (STB_LOCAL)
ffffffff81d4b570-ffffffff81d4b610: type_show (STB_LOCAL)
ffffffff81d62b10-ffffffff81d62b44: type_show (STB_LOCAL)
ffffffff81d8aa70-ffffffff81d8aac5: type_show (STB_LOCAL)
ffffffff81e0c700-ffffffff81e0c764: type_show (STB_LOCAL)
ffffffff81fda010-ffffffff81fda065: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81058010)
Location: arch/x86/kernel/ksysfs.c:135
Inline: False
```
```
In arch/x86/platform/efi/runtime-map.c (ffffffff810e51c0)
Location: arch/x86/platform/efi/runtime-map.c:33
Inline: False
```
```
In kernel/reboot.c (ffffffff81134c40)
Location: kernel/reboot.c:1160
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff811a5f90)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In kernel/events/core.c (ffffffff81365f70)
Location: kernel/events/core.c:11310
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff81978620)
Location: drivers/video/backlight/backlight.c:270
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff819b0140)
Location: drivers/acpi/dock.c:549
Inline: False
```
```
In drivers/acpi/bgrt.c (ffffffff81a265f0)
Location: drivers/acpi/bgrt.c:28
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81a78a60)
Location: drivers/xen/sys-hypervisor.c:40
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81a80aa0)
Location: drivers/regulator/core.c:858
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abe490)
Location: drivers/tty/serial/serial_core.c:2861
Inline: False
```
```
In drivers/base/cacheinfo.c (ffffffff81b452e0)
Location: drivers/base/cacheinfo.c:656
Inline: False
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c66d10)
Location: drivers/net/wwan/wwan_core.c:332
Inline: False
```
```
In drivers/usb/core/endpoint.c (ffffffff81c958e0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81d06a80)
Location: drivers/input/serio/serio.c:355
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81d49b50)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff81db5e20)
Location: drivers/mmc/core/bus.c:31
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81dcdbe0)
Location: drivers/firmware/memmap.c:382
Inline: False
```
```
In drivers/nvmem/core.c (ffffffff81df9470)
Location: drivers/nvmem/core.c:203
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81e7fb50)
Location: net/core/net-sysfs.c:113
Inline: False
```
```
In net/rfkill/core.c (ffffffff82055cd0)
Location: net/rfkill/core.c:691
Inline: False
```
**Symbols:**

```
ffffffff81058010-ffffffff8105816a: type_show (STB_LOCAL)
ffffffff810e51c0-ffffffff810e51f2: type_show (STB_LOCAL)
ffffffff81134c40-ffffffff81134c83: type_show (STB_LOCAL)
ffffffff811a5f90-ffffffff811a5ffb: type_show (STB_LOCAL)
ffffffff81365f70-ffffffff81365fa7: type_show (STB_LOCAL)
ffffffff81978620-ffffffff81978672: type_show (STB_LOCAL)
ffffffff819b0140-ffffffff819b01b4: type_show (STB_LOCAL)
ffffffff81a265f0-ffffffff81a2661d: type_show (STB_LOCAL)
ffffffff81a78a60-ffffffff81a78a80: type_show (STB_LOCAL)
ffffffff81a80aa0-ffffffff81a80b1c: type_show (STB_LOCAL)
ffffffff81abe490-ffffffff81abe508: type_show (STB_LOCAL)
ffffffff81b452e0-ffffffff81b4534a: type_show (STB_LOCAL)
ffffffff81c66d10-ffffffff81c66d64: type_show (STB_LOCAL)
ffffffff81c958e0-ffffffff81c9592d: type_show (STB_LOCAL)
ffffffff81d06a80-ffffffff81d06ab3: type_show (STB_LOCAL)
ffffffff81d49b50-ffffffff81d49b7d: type_show (STB_LOCAL)
ffffffff81db5e20-ffffffff81db5ec0: type_show (STB_LOCAL)
ffffffff81dcdbe0-ffffffff81dcdc14: type_show (STB_LOCAL)
ffffffff81df9470-ffffffff81df94c5: type_show (STB_LOCAL)
ffffffff81e7fb50-ffffffff81e7fbb4: type_show (STB_LOCAL)
ffffffff82055cd0-ffffffff82055d25: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff8105f2b0)
Location: arch/x86/kernel/ksysfs.c:135
Inline: False
```
```
In arch/x86/platform/efi/runtime-map.c (ffffffff810ed580)
Location: arch/x86/platform/efi/runtime-map.c:33
Inline: False
```
```
In kernel/reboot.c (ffffffff8113fc30)
Location: kernel/reboot.c:1183
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff811b5a80)
Location: kernel/irq/irqdesc.c:230
Inline: False
```
```
In kernel/events/core.c (ffffffff8138f090)
Location: kernel/events/core.c:11380
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff819c2710)
Location: drivers/video/backlight/backlight.c:270
Inline: False
```
```
In drivers/acpi/dock.c (ffffffff819fa5f0)
Location: drivers/acpi/dock.c:549
Inline: False
```
```
In drivers/acpi/bgrt.c (ffffffff81a714f0)
Location: drivers/acpi/bgrt.c:28
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81acad80)
Location: drivers/xen/sys-hypervisor.c:40
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81ad2fb0)
Location: drivers/regulator/core.c:860
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b11230)
Location: drivers/tty/serial/serial_core.c:2897
Inline: False
```
```
In drivers/base/cacheinfo.c (ffffffff81b9d360)
Location: drivers/base/cacheinfo.c:663
Inline: False
```
```
In drivers/usb/core/endpoint.c (ffffffff81d4a3a0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81dbc6b0)
Location: drivers/input/serio/serio.c:355
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81e00960)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff81e6e270)
Location: drivers/mmc/core/bus.c:31
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81e86720)
Location: drivers/firmware/memmap.c:382
Inline: False
```
```
In drivers/nvmem/core.c (ffffffff81eafbd0)
Location: drivers/nvmem/core.c:177
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81f40550)
Location: net/core/net-sysfs.c:114
Inline: False
```
```
In net/rfkill/core.c (ffffffff82128550)
Location: net/rfkill/core.c:703
Inline: False
```
**Symbols:**

```
ffffffff8105f2b0-ffffffff8105f40a: type_show (STB_LOCAL)
ffffffff810ed580-ffffffff810ed5b2: type_show (STB_LOCAL)
ffffffff8113fc30-ffffffff8113fc73: type_show (STB_LOCAL)
ffffffff811b5a80-ffffffff811b5aeb: type_show (STB_LOCAL)
ffffffff8138f090-ffffffff8138f0c7: type_show (STB_LOCAL)
ffffffff819c2710-ffffffff819c2762: type_show (STB_LOCAL)
ffffffff819fa5f0-ffffffff819fa664: type_show (STB_LOCAL)
ffffffff81a714f0-ffffffff81a7151d: type_show (STB_LOCAL)
ffffffff81acad80-ffffffff81acada0: type_show (STB_LOCAL)
ffffffff81ad2fb0-ffffffff81ad302c: type_show (STB_LOCAL)
ffffffff81b11230-ffffffff81b11295: type_show (STB_LOCAL)
ffffffff81b9d360-ffffffff81b9d3ca: type_show (STB_LOCAL)
ffffffff81d4a3a0-ffffffff81d4a3ed: type_show (STB_LOCAL)
ffffffff81dbc6b0-ffffffff81dbc6e3: type_show (STB_LOCAL)
ffffffff81e00960-ffffffff81e0098d: type_show (STB_LOCAL)
ffffffff81e6e270-ffffffff81e6e310: type_show (STB_LOCAL)
ffffffff81e86720-ffffffff81e86754: type_show (STB_LOCAL)
ffffffff81eafbd0-ffffffff81eafc25: type_show (STB_LOCAL)
ffffffff81f40550-ffffffff81f405b4: type_show (STB_LOCAL)
ffffffff82128550-ffffffff821285a5: type_show (STB_LOCAL)
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
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff8000101778b0)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffff8000102918c0)
Location: kernel/events/core.c:9921
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffff800010741d18)
Location: drivers/video/backlight/backlight.c:220
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffff80001083cf68)
Location: drivers/xen/sys-hypervisor.c:38
Inline: False
```
```
In drivers/regulator/core.c (ffff800010840f88)
Location: drivers/regulator/core.c:774
Inline: True
```
```
In drivers/base/cacheinfo.c (ffff8000108f4160)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffff800010a2b990)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffff800010a920d0)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffff800010ad6688)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffff800010b30868)
Location: drivers/mmc/core/bus.c:30
Inline: True
```
```
In drivers/firmware/memmap.c (ffff800010b4e1c8)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/nvmem/nvmem-sysfs.c (ffff800010ba05c0)
Location: drivers/nvmem/nvmem-sysfs.c:18
Inline: False
```
```
In net/core/net-sysfs.c (ffff800010c0ad60)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (ffff800010d6b648)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
ffff8000101778b0-ffff800010177978: type_show (STB_LOCAL)
ffff8000102918c0-ffff8000102918f4: type_show (STB_LOCAL)
ffff800010741d18-ffff800010741d68: type_show (STB_LOCAL)
ffff80001083cf68-ffff80001083cfa8: type_show (STB_LOCAL)
ffff800010840f88-ffff800010841034: type_show (STB_LOCAL)
ffff8000108f4160-ffff8000108f4224: type_show (STB_LOCAL)
ffff800010a2b990-ffff800010a2ba18: type_show (STB_LOCAL)
ffff800010a920d0-ffff800010a92110: type_show (STB_LOCAL)
ffff800010ad6688-ffff800010ad66c8: type_show (STB_LOCAL)
ffff800010b30868-ffff800010b30944: type_show (STB_LOCAL)
ffff800010b4e1c8-ffff800010b4e20c: type_show (STB_LOCAL)
ffff800010ba05c0-ffff800010ba060c: type_show (STB_LOCAL)
ffff800010c0ad60-ffff800010c0ad9c: type_show (STB_LOCAL)
ffff800010d6b648-ffff800010d6b694: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c9168)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (c04c28a0)
Location: kernel/events/core.c:9921
Inline: False
```
```
In drivers/video/backlight/backlight.c (c08c6758)
Location: drivers/video/backlight/backlight.c:220
Inline: False
```
```
In drivers/regulator/core.c (c094a320)
Location: drivers/regulator/core.c:774
Inline: True
```
```
In drivers/base/cacheinfo.c (c09e077c)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (c0b01328)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (c0b75f5c)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (c0bb6ce4)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (c0c0b5ec)
Location: drivers/mmc/core/bus.c:30
Inline: True
```
```
In drivers/firmware/memmap.c (c0c351a4)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/nvmem/nvmem-sysfs.c (c0c8221c)
Location: drivers/nvmem/nvmem-sysfs.c:18
Inline: False
```
```
In net/core/net-sysfs.c (c0d241a4)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (c0e69a98)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
c03c9168-c03c91e0: type_show (STB_LOCAL)
c04c28a0-c04c28cc: type_show (STB_LOCAL)
c08c6758-c08c6794: type_show (STB_LOCAL)
c094a320-c094a384: type_show (STB_LOCAL)
c09e077c-c09e0838: type_show (STB_LOCAL)
c0b01328-c0b01378: type_show (STB_LOCAL)
c0b75f5c-c0b75f90: type_show (STB_LOCAL)
c0bb6ce4-c0bb6d14: type_show (STB_LOCAL)
c0c0b5ec-c0c0b6b4: type_show (STB_LOCAL)
c0c351a4-c0c351d4: type_show (STB_LOCAL)
c0c8221c-c0c82254: type_show (STB_LOCAL)
c0d241a4-c0d241cc: type_show (STB_LOCAL)
c0e69a98-c0e69ad0: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *k, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/cacheinfo.c (c00000000002a200)
Location: arch/powerpc/kernel/cacheinfo.c:601
Inline: False
```
```
In kernel/irq/irqdesc.c (c0000000001d1470)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (c00000000033fd40)
Location: kernel/events/core.c:9921
Inline: False
```
```
In drivers/video/backlight/backlight.c (c0000000008a1fe0)
Location: drivers/video/backlight/backlight.c:220
Inline: False
```
```
In drivers/regulator/core.c (c0000000008daec0)
Location: drivers/regulator/core.c:774
Inline: True
```
```
In drivers/base/cacheinfo.c (c00000000098e0a0)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (c000000000ae8950)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (c000000000b6e7a0)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (c000000000bbc9a0)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (c000000000c2a2a0)
Location: drivers/mmc/core/bus.c:30
Inline: True
```
```
In drivers/nvmem/nvmem-sysfs.c (c000000000c745d0)
Location: drivers/nvmem/nvmem-sysfs.c:18
Inline: False
```
```
In net/core/net-sysfs.c (c000000000cf5660)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (c000000000ea8ea0)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
c00000000002a200-c00000000002a258: type_show (STB_LOCAL)
c0000000001d1470-c0000000001d1540: type_show (STB_LOCAL)
c00000000033fd40-c00000000033fd8c: type_show (STB_LOCAL)
c0000000008a1fe0-c0000000008a2038: type_show (STB_LOCAL)
c0000000008daec0-c0000000008daf50: type_show (STB_LOCAL)
c00000000098e0a0-c00000000098e150: type_show (STB_LOCAL)
c000000000ae8950-c000000000ae89e8: type_show (STB_LOCAL)
c000000000b6e7a0-c000000000b6e7ec: type_show (STB_LOCAL)
c000000000bbc9a0-c000000000bbc9e8: type_show (STB_LOCAL)
c000000000c2a2a0-c000000000c2a360: type_show (STB_LOCAL)
c000000000c745d0-c000000000c74624: type_show (STB_LOCAL)
c000000000cf5660-c000000000cf5680: type_show (STB_LOCAL)
c000000000ea8ea0-c000000000ea8ef4: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe00011280c)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffe0001c4240)
Location: kernel/events/core.c:9921
Inline: False
```
```
In drivers/regulator/core.c (ffffffe000522d2a)
Location: drivers/regulator/core.c:774
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffe000585718)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffe00064cd6e)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffe0006a4e76)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d17a2)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffe0007092e2)
Location: drivers/mmc/core/bus.c:30
Inline: True
```
```
In drivers/nvmem/nvmem-sysfs.c (ffffffe0007385c8)
Location: drivers/nvmem/nvmem-sysfs.c:18
Inline: False
```
```
In net/core/net-sysfs.c (ffffffe000787f06)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (ffffffe00089df9c)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
ffffffe00011280c-ffffffe0001128b2: type_show (STB_LOCAL)
ffffffe0001c4240-ffffffe0001c426a: type_show (STB_LOCAL)
ffffffe000522d2a-ffffffe000522dc6: type_show (STB_LOCAL)
ffffffe000585718-ffffffe00058581e: type_show (STB_LOCAL)
ffffffe0006a4e76-ffffffe0006a4eb4: type_show (STB_LOCAL)
ffffffe000787f06-ffffffe000787f40: type_show (STB_LOCAL)
ffffffe00089df9c-ffffffe00089dfe8: type_show (STB_LOCAL)
ffffffe00064cd6e-ffffffe00064cdd4: type_show (STB_LOCAL)
ffffffe0006d17a2-ffffffe0006d17de: type_show (STB_LOCAL)
ffffffe0007092e2-ffffffe00070942c: type_show (STB_LOCAL)
ffffffe0007385c8-ffffffe000738614: type_show (STB_LOCAL)
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
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81038c60)
Location: arch/x86/kernel/ksysfs.c:115
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff8110e660)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff81200770)
Location: kernel/events/core.c:9921
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff815af000)
Location: drivers/video/backlight/backlight.c:220
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81638040)
Location: drivers/xen/sys-hypervisor.c:38
Inline: False
```
```
In drivers/regulator/core.c (ffffffff8163dc30)
Location: drivers/regulator/core.c:774
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff816cc410)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff817b27e0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81807720)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8182ed00)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff8187a1c0)
Location: drivers/mmc/core/bus.c:30
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff8188a3f0)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff8188dfc0)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/nvmem-sysfs.c (ffffffff818a3700)
Location: drivers/nvmem/nvmem-sysfs.c:18
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81904fe0)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (ffffffff81a3ab20)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
ffffffff81038c60-ffffffff81038d0f: type_show (STB_LOCAL)
ffffffff8110e660-ffffffff8110e6ca: type_show (STB_LOCAL)
ffffffff81200770-ffffffff81200796: type_show (STB_LOCAL)
ffffffff815af000-ffffffff815af02b: type_show (STB_LOCAL)
ffffffff81638040-ffffffff8163805a: type_show (STB_LOCAL)
ffffffff8163dc30-ffffffff8163dc94: type_show (STB_LOCAL)
ffffffff816cc410-ffffffff816cc485: type_show (STB_LOCAL)
ffffffff817b27e0-ffffffff817b2821: type_show (STB_LOCAL)
ffffffff81807720-ffffffff8180774a: type_show (STB_LOCAL)
ffffffff8182ed00-ffffffff8182ed23: type_show (STB_LOCAL)
ffffffff8187a1c0-ffffffff8187a234: type_show (STB_LOCAL)
ffffffff8188a3f0-ffffffff8188a418: type_show (STB_LOCAL)
ffffffff8188dfc0-ffffffff8188dfe7: type_show (STB_LOCAL)
ffffffff818a3700-ffffffff818a372e: type_show (STB_LOCAL)
ffffffff81904fe0-ffffffff81904ffa: type_show (STB_LOCAL)
ffffffff81a3ab20-ffffffff81a3ab4b: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81028570)
Location: arch/x86/kernel/ksysfs.c:115
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff810ff340)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff811f34c0)
Location: kernel/events/core.c:9921
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff8159e190)
Location: drivers/video/backlight/backlight.c:220
Inline: False
```
```
In drivers/regulator/core.c (ffffffff8161de20)
Location: drivers/regulator/core.c:774
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff816a7740)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff817a4210)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff817cee30)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff817f6390)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81841d70)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff81846ae0)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/nvmem-sysfs.c (ffffffff8185ee70)
Location: drivers/nvmem/nvmem-sysfs.c:18
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff818bee10)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (ffffffff819f7740)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
ffffffff81028570-ffffffff8102861f: type_show (STB_LOCAL)
ffffffff810ff340-ffffffff810ff3a4: type_show (STB_LOCAL)
ffffffff811f34c0-ffffffff811f34e6: type_show (STB_LOCAL)
ffffffff8159e190-ffffffff8159e1bb: type_show (STB_LOCAL)
ffffffff8161de20-ffffffff8161de84: type_show (STB_LOCAL)
ffffffff816a7740-ffffffff816a77b5: type_show (STB_LOCAL)
ffffffff817a4210-ffffffff817a4251: type_show (STB_LOCAL)
ffffffff817cee30-ffffffff817cee5a: type_show (STB_LOCAL)
ffffffff817f6390-ffffffff817f63b3: type_show (STB_LOCAL)
ffffffff81841d70-ffffffff81841d98: type_show (STB_LOCAL)
ffffffff81846ae0-ffffffff81846b07: type_show (STB_LOCAL)
ffffffff8185ee70-ffffffff8185ee9e: type_show (STB_LOCAL)
ffffffff818bee10-ffffffff818bee2a: type_show (STB_LOCAL)
ffffffff819f7740-ffffffff819f776b: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81038ac0)
Location: arch/x86/kernel/ksysfs.c:115
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff8110c550)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff811fe540)
Location: kernel/events/core.c:9921
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff815af590)
Location: drivers/video/backlight/backlight.c:220
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81666190)
Location: drivers/xen/sys-hypervisor.c:38
Inline: False
```
```
In drivers/regulator/core.c (ffffffff8166bd80)
Location: drivers/regulator/core.c:774
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff816fa980)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff817ef280)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff818467d0)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff8187e330)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff818cb660)
Location: drivers/mmc/core/bus.c:30
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff818dc4d0)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff818e1240)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/nvmem-sysfs.c (ffffffff818f4cf0)
Location: drivers/nvmem/nvmem-sysfs.c:18
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81956010)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (ffffffff81aa69d0)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
ffffffff81038ac0-ffffffff81038b6f: type_show (STB_LOCAL)
ffffffff8110c550-ffffffff8110c5ba: type_show (STB_LOCAL)
ffffffff811fe540-ffffffff811fe566: type_show (STB_LOCAL)
ffffffff815af590-ffffffff815af5bb: type_show (STB_LOCAL)
ffffffff81666190-ffffffff816661aa: type_show (STB_LOCAL)
ffffffff8166bd80-ffffffff8166bde4: type_show (STB_LOCAL)
ffffffff816fa980-ffffffff816fa9f5: type_show (STB_LOCAL)
ffffffff817ef280-ffffffff817ef2c1: type_show (STB_LOCAL)
ffffffff818467d0-ffffffff818467fa: type_show (STB_LOCAL)
ffffffff8187e330-ffffffff8187e353: type_show (STB_LOCAL)
ffffffff818cb660-ffffffff818cb6d4: type_show (STB_LOCAL)
ffffffff818dc4d0-ffffffff818dc4f8: type_show (STB_LOCAL)
ffffffff818e1240-ffffffff818e1267: type_show (STB_LOCAL)
ffffffff818f4cf0-ffffffff818f4d1e: type_show (STB_LOCAL)
ffffffff81956010-ffffffff8195602a: type_show (STB_LOCAL)
ffffffff81aa69d0-ffffffff81aa69fb: type_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t type_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ksysfs.c (ffffffff81039ac0)
Location: arch/x86/kernel/ksysfs.c:115
Inline: False
```
```
In kernel/irq/irqdesc.c (ffffffff81117680)
Location: kernel/irq/irqdesc.c:198
Inline: False
```
```
In kernel/events/core.c (ffffffff8120d5a0)
Location: kernel/events/core.c:9921
Inline: False
```
```
In drivers/video/backlight/backlight.c (ffffffff815c9000)
Location: drivers/video/backlight/backlight.c:220
Inline: False
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81680740)
Location: drivers/xen/sys-hypervisor.c:38
Inline: False
```
```
In drivers/regulator/core.c (ffffffff81686340)
Location: drivers/regulator/core.c:774
Inline: True
```
```
In drivers/base/cacheinfo.c (ffffffff81715220)
Location: drivers/base/cacheinfo.c:403
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff818094c0)
Location: drivers/usb/core/endpoint.c:59
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81861de0)
Location: drivers/input/serio/serio.c:358
Inline: False
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81899d60)
Location: drivers/thermal/thermal_sysfs.c:27
Inline: False
```
```
In drivers/mmc/core/bus.c (ffffffff818e8180)
Location: drivers/mmc/core/bus.c:30
Inline: True
```
```
In drivers/firmware/memmap.c (ffffffff818f8ff0)
Location: drivers/firmware/memmap.c:381
Inline: False
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff818fdce0)
Location: drivers/firmware/efi/runtime-map.c:33
Inline: False
```
```
In drivers/nvmem/nvmem-sysfs.c (ffffffff81915d90)
Location: drivers/nvmem/nvmem-sysfs.c:18
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81978210)
Location: net/core/net-sysfs.c:110
Inline: False
```
```
In net/rfkill/core.c (ffffffff81ab2d70)
Location: net/rfkill/core.c:678
Inline: False
```
**Symbols:**

```
ffffffff81039ac0-ffffffff81039b6f: type_show (STB_LOCAL)
ffffffff81117680-ffffffff811176e1: type_show (STB_LOCAL)
ffffffff8120d5a0-ffffffff8120d5c6: type_show (STB_LOCAL)
ffffffff815c9000-ffffffff815c902b: type_show (STB_LOCAL)
ffffffff81680740-ffffffff8168075a: type_show (STB_LOCAL)
ffffffff81686340-ffffffff816863a4: type_show (STB_LOCAL)
ffffffff81715220-ffffffff81715295: type_show (STB_LOCAL)
ffffffff818094c0-ffffffff81809501: type_show (STB_LOCAL)
ffffffff81861de0-ffffffff81861e0a: type_show (STB_LOCAL)
ffffffff81899d60-ffffffff81899d83: type_show (STB_LOCAL)
ffffffff818e8180-ffffffff818e81f4: type_show (STB_LOCAL)
ffffffff818f8ff0-ffffffff818f9018: type_show (STB_LOCAL)
ffffffff818fdce0-ffffffff818fdd07: type_show (STB_LOCAL)
ffffffff81915d90-ffffffff81915dbe: type_show (STB_LOCAL)
ffffffff81978210-ffffffff8197822a: type_show (STB_LOCAL)
ffffffff81ab2d70-ffffffff81ab2d9b: type_show (STB_LOCAL)
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
<code>struct kobject *k</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kobject *kobj</code>
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
