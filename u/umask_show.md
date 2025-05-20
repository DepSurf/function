# Function: <code>umask_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007eb0)
Location: arch/x86/events/amd/core.c:453
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff810082b0)
Location: arch/x86/events/amd/uncore.c:246
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100aae0)
Location: arch/x86/events/intel/core.c:2748
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81011030)
Location: arch/x86/events/intel/knc.c:273
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81013270)
Location: arch/x86/events/intel/p6.c:184
Inline: False
```
**Symbols:**

```
ffffffff81007eb0-ffffffff81007ed8: umask_show (STB_LOCAL)
ffffffff810082b0-ffffffff810082d8: umask_show (STB_LOCAL)
ffffffff8100aae0-ffffffff8100ab08: umask_show (STB_LOCAL)
ffffffff81011030-ffffffff81011058: umask_show (STB_LOCAL)
ffffffff81013270-ffffffff81013298: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810080b0)
Location: arch/x86/events/amd/core.c:453
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff810087e0)
Location: arch/x86/events/amd/uncore.c:248
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100ac70)
Location: arch/x86/events/intel/core.c:3031
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81010970)
Location: arch/x86/events/intel/knc.c:275
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81012bc0)
Location: arch/x86/events/intel/p6.c:184
Inline: False
```
**Symbols:**

```
ffffffff810080b0-ffffffff810080d8: umask_show (STB_LOCAL)
ffffffff810087e0-ffffffff81008808: umask_show (STB_LOCAL)
ffffffff8100ac70-ffffffff8100ac98: umask_show (STB_LOCAL)
ffffffff81010970-ffffffff81010998: umask_show (STB_LOCAL)
ffffffff81012bc0-ffffffff81012be8: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810080d0)
Location: arch/x86/events/amd/core.c:453
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008820)
Location: arch/x86/events/amd/uncore.c:248
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100acb0)
Location: arch/x86/events/intel/core.c:3046
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81010b20)
Location: arch/x86/events/intel/knc.c:275
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81012cb0)
Location: arch/x86/events/intel/p6.c:184
Inline: False
```
**Symbols:**

```
ffffffff810080d0-ffffffff810080f8: umask_show (STB_LOCAL)
ffffffff81008820-ffffffff81008848: umask_show (STB_LOCAL)
ffffffff8100acb0-ffffffff8100acd8: umask_show (STB_LOCAL)
ffffffff81010b20-ffffffff81010b48: umask_show (STB_LOCAL)
ffffffff81012cb0-ffffffff81012cd8: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007db0)
Location: arch/x86/events/amd/core.c:453
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff810084d0)
Location: arch/x86/events/amd/uncore.c:287
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100aaa0)
Location: arch/x86/events/intel/core.c:3199
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f160)
Location: arch/x86/events/intel/knc.c:275
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81011240)
Location: arch/x86/events/intel/p6.c:184
Inline: False
```
**Symbols:**

```
ffffffff81007db0-ffffffff81007dd8: umask_show (STB_LOCAL)
ffffffff810084d0-ffffffff810084f8: umask_show (STB_LOCAL)
ffffffff8100aaa0-ffffffff8100aac8: umask_show (STB_LOCAL)
ffffffff8100f160-ffffffff8100f188: umask_show (STB_LOCAL)
ffffffff81011240-ffffffff81011268: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008230)
Location: arch/x86/events/amd/core.c:453
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008960)
Location: arch/x86/events/amd/uncore.c:287
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100af90)
Location: arch/x86/events/intel/core.c:3203
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff8100f880)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff810119c0)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
**Symbols:**

```
ffffffff81008230-ffffffff81008258: umask_show (STB_LOCAL)
ffffffff81008960-ffffffff81008988: umask_show (STB_LOCAL)
ffffffff8100af90-ffffffff8100afb8: umask_show (STB_LOCAL)
ffffffff8100f880-ffffffff8100f8a8: umask_show (STB_LOCAL)
ffffffff810119c0-ffffffff810119e8: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810089f0)
Location: arch/x86/events/amd/core.c:453
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009090)
Location: arch/x86/events/amd/uncore.c:288
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100b8b0)
Location: arch/x86/events/intel/core.c:3222
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff810101c0)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81012390)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
**Symbols:**

```
ffffffff810089f0-ffffffff81008a18: umask_show (STB_LOCAL)
ffffffff81009090-ffffffff810090b8: umask_show (STB_LOCAL)
ffffffff8100b8b0-ffffffff8100b8d8: umask_show (STB_LOCAL)
ffffffff810101c0-ffffffff810101e8: umask_show (STB_LOCAL)
ffffffff81012390-ffffffff810123b8: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008910)
Location: arch/x86/events/amd/core.c:453
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff810090f0)
Location: arch/x86/events/amd/uncore.c:296
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100b970)
Location: arch/x86/events/intel/core.c:3437
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff810107e0)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81012a10)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
**Symbols:**

```
ffffffff81008910-ffffffff81008938: umask_show (STB_LOCAL)
ffffffff810090f0-ffffffff81009118: umask_show (STB_LOCAL)
ffffffff8100b970-ffffffff8100b998: umask_show (STB_LOCAL)
ffffffff810107e0-ffffffff81010808: umask_show (STB_LOCAL)
ffffffff81012a10-ffffffff81012a38: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008b70)
Location: arch/x86/events/amd/core.c:705
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009580)
Location: arch/x86/events/amd/uncore.c:295
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100c0f0)
Location: arch/x86/events/intel/core.c:3581
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff810119a0)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81013db0)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
**Symbols:**

```
ffffffff81008b70-ffffffff81008b98: umask_show (STB_LOCAL)
ffffffff81009580-ffffffff810095a8: umask_show (STB_LOCAL)
ffffffff8100c0f0-ffffffff8100c118: umask_show (STB_LOCAL)
ffffffff810119a0-ffffffff810119c8: umask_show (STB_LOCAL)
ffffffff81013db0-ffffffff81013dd8: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008e90)
Location: arch/x86/events/amd/core.c:725
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009980)
Location: arch/x86/events/amd/uncore.c:292
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100c500)
Location: arch/x86/events/intel/core.c:3589
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81012160)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81014560)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
**Symbols:**

```
ffffffff81008e90-ffffffff81008eb8: umask_show (STB_LOCAL)
ffffffff81009980-ffffffff810099a8: umask_show (STB_LOCAL)
ffffffff8100c500-ffffffff8100c528: umask_show (STB_LOCAL)
ffffffff81012160-ffffffff81012188: umask_show (STB_LOCAL)
ffffffff81014560-ffffffff81014588: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009fd0)
Location: arch/x86/events/amd/core.c:716
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff8100a8e0)
Location: arch/x86/events/amd/uncore.c:310
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100d6b0)
Location: arch/x86/events/intel/core.c:3620
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81013560)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81015b80)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101f6a0)
Location: arch/x86/events/zhaoxin/core.c:438
Inline: False
```
**Symbols:**

```
ffffffff81009fd0-ffffffff81009ff8: umask_show (STB_LOCAL)
ffffffff8100a8e0-ffffffff8100a908: umask_show (STB_LOCAL)
ffffffff8100d6b0-ffffffff8100d6d8: umask_show (STB_LOCAL)
ffffffff81013560-ffffffff81013588: umask_show (STB_LOCAL)
ffffffff81015b80-ffffffff81015ba8: umask_show (STB_LOCAL)
ffffffff8101f6a0-ffffffff8101f6c8: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008e50)
Location: arch/x86/events/amd/core.c:716
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100c710)
Location: arch/x86/events/intel/core.c:3963
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81013110)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81016020)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81020140)
Location: arch/x86/events/zhaoxin/core.c:438
Inline: False
```
**Symbols:**

```
ffffffff81008e50-ffffffff81008e78: umask_show (STB_LOCAL)
ffffffff8100c710-ffffffff8100c738: umask_show (STB_LOCAL)
ffffffff81013110-ffffffff81013138: umask_show (STB_LOCAL)
ffffffff81016020-ffffffff81016048: umask_show (STB_LOCAL)
ffffffff81020140-ffffffff81020168: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810097f0)
Location: arch/x86/events/amd/core.c:716
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100d130)
Location: arch/x86/events/intel/core.c:4185
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81014320)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81017310)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810224c0)
Location: arch/x86/events/zhaoxin/core.c:438
Inline: False
```
**Symbols:**

```
ffffffff810097f0-ffffffff81009818: umask_show (STB_LOCAL)
ffffffff8100d130-ffffffff8100d158: umask_show (STB_LOCAL)
ffffffff81014320-ffffffff81014348: umask_show (STB_LOCAL)
ffffffff81017310-ffffffff81017338: umask_show (STB_LOCAL)
ffffffff810224c0-ffffffff810224e8: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a7c0)
Location: arch/x86/events/amd/core.c:716
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100d5d0)
Location: arch/x86/events/intel/core.c:4192
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff810156a0)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff810190c0)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81026320)
Location: arch/x86/events/zhaoxin/core.c:438
Inline: False
```
**Symbols:**

```
ffffffff8100a7c0-ffffffff8100a7e8: umask_show (STB_LOCAL)
ffffffff8100d5d0-ffffffff8100d5f8: umask_show (STB_LOCAL)
ffffffff810156a0-ffffffff810156c8: umask_show (STB_LOCAL)
ffffffff810190c0-ffffffff810190e8: umask_show (STB_LOCAL)
ffffffff81026320-ffffffff81026348: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009e40)
Location: arch/x86/events/amd/core.c:1014
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100e770)
Location: arch/x86/events/intel/core.c:4254
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81017700)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff8101b2a0)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a3c0)
Location: arch/x86/events/zhaoxin/core.c:438
Inline: False
```
**Symbols:**

```
ffffffff81009e40-ffffffff81009e71: umask_show (STB_LOCAL)
ffffffff8100e770-ffffffff8100e7a1: umask_show (STB_LOCAL)
ffffffff81017700-ffffffff81017731: umask_show (STB_LOCAL)
ffffffff8101b2a0-ffffffff8101b2d1: umask_show (STB_LOCAL)
ffffffff8102a3c0-ffffffff8102a3f1: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100b930)
Location: arch/x86/events/amd/core.c:989
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff81011d90)
Location: arch/x86/events/intel/core.c:4380
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b940)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff8101f480)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81030f70)
Location: arch/x86/events/zhaoxin/core.c:438
Inline: False
```
**Symbols:**

```
ffffffff8100b930-ffffffff8100b961: umask_show (STB_LOCAL)
ffffffff81011d90-ffffffff81011dc1: umask_show (STB_LOCAL)
ffffffff8101b940-ffffffff8101b971: umask_show (STB_LOCAL)
ffffffff8101f480-ffffffff8101f4b1: umask_show (STB_LOCAL)
ffffffff81030f70-ffffffff81030fa1: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100b0c0)
Location: arch/x86/events/amd/core.c:986
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff81011420)
Location: arch/x86/events/intel/core.c:4489
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff8101b610)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff8101f190)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81030f80)
Location: arch/x86/events/zhaoxin/core.c:438
Inline: False
```
**Symbols:**

```
ffffffff8100b0c0-ffffffff8100b0f1: umask_show (STB_LOCAL)
ffffffff81011420-ffffffff81011451: umask_show (STB_LOCAL)
ffffffff8101b610-ffffffff8101b641: umask_show (STB_LOCAL)
ffffffff8101f190-ffffffff8101f1c1: umask_show (STB_LOCAL)
ffffffff81030f80-ffffffff81030fb1: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81010840)
Location: arch/x86/events/amd/core.c:996
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff81016b70)
Location: arch/x86/events/intel/core.c:4569
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81021170)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81025250)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff81037280)
Location: arch/x86/events/zhaoxin/core.c:438
Inline: False
```
**Symbols:**

```
ffffffff81010840-ffffffff81010871: umask_show (STB_LOCAL)
ffffffff81016b70-ffffffff81016ba1: umask_show (STB_LOCAL)
ffffffff81021170-ffffffff810211a1: umask_show (STB_LOCAL)
ffffffff81025250-ffffffff81025281: umask_show (STB_LOCAL)
ffffffff81037280-ffffffff810372b1: umask_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008e90)
Location: arch/x86/events/amd/core.c:725
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009980)
Location: arch/x86/events/amd/uncore.c:292
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100c500)
Location: arch/x86/events/intel/core.c:3589
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81012160)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81014560)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
**Symbols:**

```
ffffffff81008e90-ffffffff81008eb8: umask_show (STB_LOCAL)
ffffffff81009980-ffffffff810099a8: umask_show (STB_LOCAL)
ffffffff8100c500-ffffffff8100c528: umask_show (STB_LOCAL)
ffffffff81012160-ffffffff81012188: umask_show (STB_LOCAL)
ffffffff81014560-ffffffff81014588: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810076a0)
Location: arch/x86/events/amd/core.c:725
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff81008120)
Location: arch/x86/events/amd/uncore.c:292
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100ad30)
Location: arch/x86/events/intel/core.c:3589
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81010f60)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff810137e0)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
**Symbols:**

```
ffffffff810076a0-ffffffff810076c8: umask_show (STB_LOCAL)
ffffffff81008120-ffffffff81008148: umask_show (STB_LOCAL)
ffffffff8100ad30-ffffffff8100ad58: umask_show (STB_LOCAL)
ffffffff81010f60-ffffffff81010f88: umask_show (STB_LOCAL)
ffffffff810137e0-ffffffff81013808: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008e50)
Location: arch/x86/events/amd/core.c:725
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009940)
Location: arch/x86/events/amd/uncore.c:292
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100c4c0)
Location: arch/x86/events/intel/core.c:3589
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81012120)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81014520)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
**Symbols:**

```
ffffffff81008e50-ffffffff81008e78: umask_show (STB_LOCAL)
ffffffff81009940-ffffffff81009968: umask_show (STB_LOCAL)
ffffffff8100c4c0-ffffffff8100c4e8: umask_show (STB_LOCAL)
ffffffff81012120-ffffffff81012148: umask_show (STB_LOCAL)
ffffffff81014520-ffffffff81014548: umask_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t umask_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008fb0)
Location: arch/x86/events/amd/core.c:725
Inline: False
```
```
In arch/x86/events/amd/uncore.c (ffffffff81009aa0)
Location: arch/x86/events/amd/uncore.c:292
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100c6f0)
Location: arch/x86/events/intel/core.c:3589
Inline: False
```
```
In arch/x86/events/intel/knc.c (ffffffff81012340)
Location: arch/x86/events/intel/knc.c:276
Inline: False
```
```
In arch/x86/events/intel/p6.c (ffffffff81014760)
Location: arch/x86/events/intel/p6.c:185
Inline: False
```
**Symbols:**

```
ffffffff81008fb0-ffffffff81008fd8: umask_show (STB_LOCAL)
ffffffff81009aa0-ffffffff81009ac8: umask_show (STB_LOCAL)
ffffffff8100c6f0-ffffffff8100c718: umask_show (STB_LOCAL)
ffffffff81012340-ffffffff81012368: umask_show (STB_LOCAL)
ffffffff81014760-ffffffff81014788: umask_show (STB_LOCAL)
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
