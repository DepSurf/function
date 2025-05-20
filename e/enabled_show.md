# Function: <code>enabled_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810e8970)
Location: kernel/livepatch/core.c:590
Inline: False
```
```
In mm/huge_memory.c (ffffffff811f4240)
Location: mm/huge_memory.c:277
Inline: False
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff815250d0)
Location: drivers/char/tpm/tpm-sysfs.c:116
Inline: False
```
```
In drivers/powercap/powercap_sys.c (ffffffff816f19d0)
Location: drivers/powercap/powercap_sys.c:433
Inline: False
```
**Symbols:**

```
ffffffff810e8970-ffffffff810e8997: enabled_show (STB_LOCAL)
ffffffff811f4240-ffffffff811f42ef: enabled_show (STB_LOCAL)
ffffffff815250d0-ffffffff81525145: enabled_show (STB_LOCAL)
ffffffff816f19d0-ffffffff816f1a80: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810eeec0)
Location: kernel/livepatch/core.c:654
Inline: False
```
```
In mm/huge_memory.c (ffffffff81213aa0)
Location: mm/huge_memory.c:161
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81578100)
Location: drivers/char/tpm/tpm-sysfs.c:116
Inline: False
```
```
In drivers/powercap/powercap_sys.c (ffffffff817569f0)
Location: drivers/powercap/powercap_sys.c:433
Inline: False
```
**Symbols:**

```
ffffffff810eeec0-ffffffff810eeee7: enabled_show (STB_LOCAL)
ffffffff81213aa0-ffffffff81213b4f: enabled_show (STB_LOCAL)
ffffffff81578100-ffffffff81578175: enabled_show (STB_LOCAL)
ffffffff817569f0-ffffffff81756aa0: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f6030)
Location: kernel/livepatch/core.c:649
Inline: False
```
```
In mm/huge_memory.c (ffffffff81225e30)
Location: mm/huge_memory.c:181
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff815a45d0)
Location: drivers/char/tpm/tpm-sysfs.c:116
Inline: False
```
```
In drivers/powercap/powercap_sys.c (ffffffff81782fd0)
Location: drivers/powercap/powercap_sys.c:433
Inline: False
```
**Symbols:**

```
ffffffff810f6030-ffffffff810f6057: enabled_show (STB_LOCAL)
ffffffff81225e30-ffffffff81225edf: enabled_show (STB_LOCAL)
ffffffff815a45d0-ffffffff815a4645: enabled_show (STB_LOCAL)
ffffffff81782fd0-ffffffff81783080: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f7680)
Location: kernel/livepatch/core.c:498
Inline: False
```
```
In mm/huge_memory.c (ffffffff812317f0)
Location: mm/huge_memory.c:148
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff815b8490)
Location: drivers/char/tpm/tpm-sysfs.c:120
Inline: False
```
```
In drivers/powercap/powercap_sys.c (ffffffff817a1d90)
Location: drivers/powercap/powercap_sys.c:433
Inline: False
```
**Symbols:**

```
ffffffff810f7680-ffffffff810f76ab: enabled_show (STB_LOCAL)
ffffffff812317f0-ffffffff8123189f: enabled_show (STB_LOCAL)
ffffffff815b8490-ffffffff815b850d: enabled_show (STB_LOCAL)
ffffffff817a1d90-ffffffff817a1e3e: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81101770)
Location: kernel/livepatch/core.c:512
Inline: False
```
```
In mm/huge_memory.c (ffffffff8124f4a0)
Location: mm/huge_memory.c:148
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8161ef90)
Location: drivers/char/tpm/tpm-sysfs.c:129
Inline: False
```
```
In drivers/powercap/powercap_sys.c (ffffffff81818ec0)
Location: drivers/powercap/powercap_sys.c:433
Inline: False
```
**Symbols:**

```
ffffffff81101770-ffffffff8110179b: enabled_show (STB_LOCAL)
ffffffff8124f4a0-ffffffff8124f54f: enabled_show (STB_LOCAL)
ffffffff8161ef90-ffffffff8161f00d: enabled_show (STB_LOCAL)
ffffffff81818ec0-ffffffff81818f74: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81109bc0)
Location: kernel/livepatch/core.c:509
Inline: False
```
```
In mm/huge_memory.c (ffffffff812732e0)
Location: mm/huge_memory.c:148
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81658d10)
Location: drivers/char/tpm/tpm-sysfs.c:129
Inline: False
```
```
In drivers/powercap/powercap_sys.c (ffffffff81862f80)
Location: drivers/powercap/powercap_sys.c:433
Inline: False
```
**Symbols:**

```
ffffffff81109bc0-ffffffff81109beb: enabled_show (STB_LOCAL)
ffffffff812732e0-ffffffff8127338f: enabled_show (STB_LOCAL)
ffffffff81658d10-ffffffff81658d8d: enabled_show (STB_LOCAL)
ffffffff81862f80-ffffffff8186302f: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81115390)
Location: kernel/livepatch/core.c:509
Inline: False
```
```
In mm/huge_memory.c (ffffffff81287860)
Location: mm/huge_memory.c:158
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8167a3f0)
Location: drivers/char/tpm/tpm-sysfs.c:129
Inline: False
```
```
In drivers/powercap/powercap_sys.c (ffffffff81882710)
Location: drivers/powercap/powercap_sys.c:433
Inline: False
```
**Symbols:**

```
ffffffff81115390-ffffffff811153bb: enabled_show (STB_LOCAL)
ffffffff81287860-ffffffff8128790f: enabled_show (STB_LOCAL)
ffffffff8167a3f0-ffffffff8167a46d: enabled_show (STB_LOCAL)
ffffffff81882710-ffffffff818827bf: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111f1c0)
Location: kernel/livepatch/core.c:354
Inline: False
```
```
In mm/huge_memory.c (ffffffff812a1dd0)
Location: mm/huge_memory.c:163
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816b0cf0)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff818ccd80)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
ffffffff8111f1c0-ffffffff8111f1ec: enabled_show (STB_LOCAL)
ffffffff812a1dd0-ffffffff812a1e7f: enabled_show (STB_LOCAL)
ffffffff816b0cf0-ffffffff816b0d92: enabled_show (STB_LOCAL)
ffffffff818ccd80-ffffffff818cce32: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112b900)
Location: kernel/livepatch/core.c:354
Inline: False
```
```
In mm/huge_memory.c (ffffffff812b3180)
Location: mm/huge_memory.c:163
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816d39f0)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff818ff170)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
ffffffff8112b900-ffffffff8112b92c: enabled_show (STB_LOCAL)
ffffffff812b3180-ffffffff812b322f: enabled_show (STB_LOCAL)
ffffffff816d39f0-ffffffff816d3a92: enabled_show (STB_LOCAL)
ffffffff818ff170-ffffffff818ff222: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8113a040)
Location: kernel/livepatch/core.c:376
Inline: False
```
```
In mm/huge_memory.c (ffffffff812e8530)
Location: mm/huge_memory.c:163
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81787c10)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d61f0)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
ffffffff8113a040-ffffffff8113a06c: enabled_show (STB_LOCAL)
ffffffff812e8530-ffffffff812e85df: enabled_show (STB_LOCAL)
ffffffff81787c10-ffffffff81787cb2: enabled_show (STB_LOCAL)
ffffffff819d61f0-ffffffff819d62a0: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81134b30)
Location: kernel/livepatch/core.c:376
Inline: False
```
```
In mm/huge_memory.c (ffffffff812f3840)
Location: mm/huge_memory.c:163
Inline: False
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff8179ebe0)
Location: drivers/char/tpm/tpm-sysfs.c:117
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819d5610)
Location: drivers/powercap/powercap_sys.c:420
Inline: False
```
**Symbols:**

```
ffffffff81134b30-ffffffff81134b5c: enabled_show (STB_LOCAL)
ffffffff812f3840-ffffffff812f3889: enabled_show (STB_LOCAL)
ffffffff8179ebe0-ffffffff8179ec82: enabled_show (STB_LOCAL)
ffffffff819d5610-ffffffff819d56c0: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81135a00)
Location: kernel/livepatch/core.c:375
Inline: False
```
```
In mm/huge_memory.c (ffffffff812f9ba0)
Location: mm/huge_memory.c:176
Inline: False
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff817817b0)
Location: drivers/char/tpm/tpm-sysfs.c:117
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff819bb6e0)
Location: drivers/powercap/powercap_sys.c:420
Inline: False
```
**Symbols:**

```
ffffffff81135a00-ffffffff81135a2c: enabled_show (STB_LOCAL)
ffffffff812f9ba0-ffffffff812f9be9: enabled_show (STB_LOCAL)
ffffffff817817b0-ffffffff81781852: enabled_show (STB_LOCAL)
ffffffff819bb6e0-ffffffff819bb790: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:375
Inline: False
```
```
In mm/huge_memory.c (ffffffff81343a60)
Location: mm/huge_memory.c:176
Inline: False
```
```
In drivers/acpi/sysfs.c (ffffffff8170eb00)
Location: drivers/acpi/sysfs.c:916
Inline: False
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81807e60)
Location: drivers/char/tpm/tpm-sysfs.c:117
Inline: True
```
```
In drivers/eisa/eisa-bus.c (ffffffff81a1e7c0)
Location: drivers/eisa/eisa-bus.c:166
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: drivers/powercap/powercap_sys.c:420
Inline: False
```
**Symbols:**

```
ffffffff811585d0-ffffffff81158611: enabled_show (STB_LOCAL)
ffffffff81caf956-ffffffff81caf971: enabled_show.cold (STB_LOCAL)
ffffffff81343a60-ffffffff81343aa9: enabled_show (STB_LOCAL)
ffffffff8170eb00-ffffffff8170eb2a: enabled_show (STB_LOCAL)
ffffffff81807e60-ffffffff81807f02: enabled_show (STB_LOCAL)
ffffffff81a1e7c0-ffffffff81a1e7ec: enabled_show (STB_LOCAL)
ffffffff81a6b5a0-ffffffff81a6b65c: enabled_show (STB_LOCAL)
ffffffff81d341dd-ffffffff81d341f7: enabled_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:375
Inline: False
```
```
In mm/huge_memory.c (ffffffff813b8fa0)
Location: mm/huge_memory.c:175
Inline: False
```
```
In drivers/acpi/sysfs.c (ffffffff8183d550)
Location: drivers/acpi/sysfs.c:927
Inline: False
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81947ba0)
Location: drivers/char/tpm/tpm-sysfs.c:117
Inline: False
```
```
In drivers/eisa/eisa-bus.c (ffffffff81b86f90)
Location: drivers/eisa/eisa-bus.c:166
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: drivers/powercap/powercap_sys.c:420
Inline: False
```
**Symbols:**

```
ffffffff81181af0-ffffffff81181b3c: enabled_show (STB_LOCAL)
ffffffff81e605f1-ffffffff81e6060c: enabled_show.cold (STB_LOCAL)
ffffffff813b8fa0-ffffffff813b8ff3: enabled_show (STB_LOCAL)
ffffffff8183d550-ffffffff8183d583: enabled_show (STB_LOCAL)
ffffffff81947ba0-ffffffff81947c67: enabled_show (STB_LOCAL)
ffffffff81b86f90-ffffffff81b86fc5: enabled_show (STB_LOCAL)
ffffffff81bdc000-ffffffff81bdc0c5: enabled_show (STB_LOCAL)
ffffffff81f005d7-ffffffff81f005f1: enabled_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:383
Inline: False
```
```
In mm/huge_memory.c (ffffffff8143b1c0)
Location: mm/huge_memory.c:238
Inline: False
```
```
In drivers/acpi/sysfs.c (ffffffff819730b0)
Location: drivers/acpi/sysfs.c:928
Inline: False
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81aaaf90)
Location: drivers/char/tpm/tpm-sysfs.c:117
Inline: False
```
```
In drivers/eisa/eisa-bus.c (ffffffff81d26450)
Location: drivers/eisa/eisa-bus.c:166
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
ffffffff811bc3e0-ffffffff811bc42c: enabled_show (STB_LOCAL)
ffffffff8205a3c8-ffffffff8205a3e3: enabled_show.cold (STB_LOCAL)
ffffffff8143b1c0-ffffffff8143b213: enabled_show (STB_LOCAL)
ffffffff819730b0-ffffffff819730e3: enabled_show (STB_LOCAL)
ffffffff81aaaf90-ffffffff81aab057: enabled_show (STB_LOCAL)
ffffffff81d26450-ffffffff81d26485: enabled_show (STB_LOCAL)
ffffffff81d870d0-ffffffff81d87195: enabled_show (STB_LOCAL)
ffffffff820aa65b-ffffffff820aa675: enabled_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:398
Inline: False
```
```
In mm/vmscan.c (ffffffff813aa6b0)
Location: mm/vmscan.c:5760
Inline: False
```
```
In mm/huge_memory.c (ffffffff81470b10)
Location: mm/huge_memory.c:239
Inline: False
```
```
In drivers/acpi/sysfs.c (ffffffff819b9780)
Location: drivers/acpi/sysfs.c:945
Inline: False
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81af67b0)
Location: drivers/char/tpm/tpm-sysfs.c:117
Inline: False
```
```
In drivers/eisa/eisa-bus.c (ffffffff81d8f680)
Location: drivers/eisa/eisa-bus.c:166
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
ffffffff811ced80-ffffffff811cedcc: enabled_show (STB_LOCAL)
ffffffff820d8bf6-ffffffff820d8c11: enabled_show.cold (STB_LOCAL)
ffffffff813aa6b0-ffffffff813aa701: enabled_show (STB_LOCAL)
ffffffff81470b10-ffffffff81470b63: enabled_show (STB_LOCAL)
ffffffff819b9780-ffffffff819b97b3: enabled_show (STB_LOCAL)
ffffffff81af67b0-ffffffff81af6877: enabled_show (STB_LOCAL)
ffffffff81d8f680-ffffffff81d8f6b5: enabled_show (STB_LOCAL)
ffffffff81df5540-ffffffff81df5605: enabled_show (STB_LOCAL)
ffffffff8212bb46-ffffffff8212bb60: enabled_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:398
Inline: False
```
```
In mm/vmscan.c (ffffffff813d3f70)
Location: mm/vmscan.c:5105
Inline: False
```
```
In mm/huge_memory.c (ffffffff8149fed0)
Location: mm/huge_memory.c:273
Inline: False
```
```
In drivers/acpi/sysfs.c (ffffffff81a03dc0)
Location: drivers/acpi/sysfs.c:945
Inline: False
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81b49da0)
Location: drivers/char/tpm/tpm-sysfs.c:117
Inline: False
```
```
In drivers/gpu/drm/drm_sysfs.c (ffffffff81cb2590)
Location: drivers/gpu/drm/drm_sysfs.c:252
Inline: False
```
```
In drivers/eisa/eisa-bus.c (ffffffff81e46f90)
Location: drivers/eisa/eisa-bus.c:166
Inline: False
```
```
In drivers/powercap/powercap_sys.c (0)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
ffffffff811e3960-ffffffff811e39ac: enabled_show (STB_LOCAL)
ffffffff821b432f-ffffffff821b434a: enabled_show.cold (STB_LOCAL)
ffffffff813d3f70-ffffffff813d3fc1: enabled_show (STB_LOCAL)
ffffffff8149fed0-ffffffff8149ff23: enabled_show (STB_LOCAL)
ffffffff81a03dc0-ffffffff81a03df3: enabled_show (STB_LOCAL)
ffffffff81b49da0-ffffffff81b49e67: enabled_show (STB_LOCAL)
ffffffff81cb2590-ffffffff81cb25d2: enabled_show (STB_LOCAL)
ffffffff81e46f90-ffffffff81e46fc5: enabled_show (STB_LOCAL)
ffffffff81eabbd0-ffffffff81eabc95: enabled_show (STB_LOCAL)
ffffffff8220d7db-ffffffff8220d7f5: enabled_show.cold (STB_LOCAL)
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
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff8000103540a8)
Location: mm/huge_memory.c:163
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffff8000108be550)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffff800010b8e968)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
ffff8000103540a8-ffff800010354150: enabled_show (STB_LOCAL)
ffff8000108be550-ffff8000108be608: enabled_show (STB_LOCAL)
ffff800010b8e968-ffff800010b8ea3c: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-sysfs.c (c09b7920)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
```
In drivers/powercap/powercap_sys.c (c0c78a0c)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
c09b7920-c09b79e0: enabled_show (STB_LOCAL)
c0c78a0c-c0c78af0: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001eec80)
Location: kernel/livepatch/core.c:354
Inline: False
```
```
In mm/huge_memory.c (c00000000043af70)
Location: mm/huge_memory.c:163
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (c0000000009608f0)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
```
In drivers/powercap/powercap_sys.c (c000000000c6d200)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
c0000000001eec80-c0000000001eecd4: enabled_show (STB_LOCAL)
c00000000043af70-c00000000043b02c: enabled_show (STB_LOCAL)
c0000000009608f0-c0000000009609e4: enabled_show (STB_LOCAL)
c000000000c6d200-c000000000c6d320: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-sysfs.c (ffffffe000570be4)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffe000734860)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
ffffffe000734860-ffffffe0007348dc: enabled_show (STB_LOCAL)
ffffffe000570be4-ffffffe000570c74: enabled_show (STB_LOCAL)
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
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81123ee0)
Location: kernel/livepatch/core.c:354
Inline: False
```
```
In mm/huge_memory.c (ffffffff812ab760)
Location: mm/huge_memory.c:163
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81699440)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
**Symbols:**

```
ffffffff81123ee0-ffffffff81123f0c: enabled_show (STB_LOCAL)
ffffffff812ab760-ffffffff812ab80f: enabled_show (STB_LOCAL)
ffffffff81699440-ffffffff816994e2: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81116940)
Location: kernel/livepatch/core.c:354
Inline: False
```
```
In mm/huge_memory.c (ffffffff8129d060)
Location: mm/huge_memory.c:163
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff81676e30)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
**Symbols:**

```
ffffffff81116940-ffffffff8111696c: enabled_show (STB_LOCAL)
ffffffff8129d060-ffffffff8129d10f: enabled_show (STB_LOCAL)
ffffffff81676e30-ffffffff81676ed2: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81121dd0)
Location: kernel/livepatch/core.c:354
Inline: False
```
```
In mm/huge_memory.c (ffffffff812a9570)
Location: mm/huge_memory.c:163
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816c76b0)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff818efb90)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
ffffffff81121dd0-ffffffff81121dfc: enabled_show (STB_LOCAL)
ffffffff812a9570-ffffffff812a961f: enabled_show (STB_LOCAL)
ffffffff816c76b0-ffffffff816c7752: enabled_show (STB_LOCAL)
ffffffff818efb90-ffffffff818efc42: enabled_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t enabled_show(struct kobject *kobj, struct kobj_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112e3e0)
Location: kernel/livepatch/core.c:354
Inline: False
```
```
In mm/huge_memory.c (ffffffff812b9b10)
Location: mm/huge_memory.c:163
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffff816e1ba0)
Location: drivers/char/tpm/tpm-sysfs.c:128
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffff81910c10)
Location: drivers/powercap/powercap_sys.c:421
Inline: False
```
**Symbols:**

```
ffffffff8112e3e0-ffffffff8112e40c: enabled_show (STB_LOCAL)
ffffffff812b9b10-ffffffff812b9bbf: enabled_show (STB_LOCAL)
ffffffff816e1ba0-ffffffff816e1c42: enabled_show (STB_LOCAL)
ffffffff81910c10-ffffffff81910cc2: enabled_show (STB_LOCAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
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
