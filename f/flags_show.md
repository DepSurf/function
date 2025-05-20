# Function: <code>flags_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81736220)
Location: net/core/net-sysfs.c:318
Inline: False
```
**Symbols:**

```
ffffffff81736220-ffffffff8173623a: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817a23d0)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffff817a23d0-ffffffff817a23ea: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817d0cf0)
Location: net/core/net-sysfs.c:321
Inline: False
```
**Symbols:**

```
ffffffff817d0cf0-ffffffff817d0d0a: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817f03d0)
Location: net/core/net-sysfs.c:322
Inline: False
```
**Symbols:**

```
ffffffff817f03d0-ffffffff817f03ea: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81697b60)
Location: drivers/nvdimm/dimm_devs.c:334
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff8186b9d0)
Location: net/core/net-sysfs.c:326
Inline: False
```
**Symbols:**

```
ffffffff81697b60-ffffffff81697bcd: flags_show (STB_LOCAL)
ffffffff8186b9d0-ffffffff8186b9ea: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816d3cc0)
Location: drivers/nvdimm/dimm_devs.c:335
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff818bc140)
Location: net/core/net-sysfs.c:347
Inline: False
```
**Symbols:**

```
ffffffff816d3cc0-ffffffff816d3d2d: flags_show (STB_LOCAL)
ffffffff818bc140-ffffffff818bc15a: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5400)
Location: drivers/nvdimm/dimm_devs.c:323
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff818e2f50)
Location: net/core/net-sysfs.c:348
Inline: False
```
**Symbols:**

```
ffffffff816f5400-ffffffff816f546d: flags_show (STB_LOCAL)
ffffffff818e2f50-ffffffff818e2f6a: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:320
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81932560)
Location: net/core/net-sysfs.c:343
Inline: False
```
**Symbols:**

```
ffffffff8172ec90-ffffffff8172ecf4: flags_show (STB_LOCAL)
ffffffff817300d6-ffffffff817300e8: flags_show.cold (STB_LOCAL)
ffffffff81932560-ffffffff8193257a: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81752fc0)
Location: drivers/nvdimm/dimm_devs.c:320
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff819650a0)
Location: net/core/net-sysfs.c:343
Inline: False
```
**Symbols:**

```
ffffffff81752fc0-ffffffff8175302d: flags_show (STB_LOCAL)
ffffffff819650a0-ffffffff819650ba: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817575b0)
Location: drivers/tty/serial/serial_core.c:2673
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81811980)
Location: drivers/nvdimm/dimm_devs.c:310
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81a38f90)
Location: net/core/net-sysfs.c:355
Inline: False
```
**Symbols:**

```
ffffffff817575b0-ffffffff81757611: flags_show (STB_LOCAL)
ffffffff81811980-ffffffff818119ea: flags_show (STB_LOCAL)
ffffffff81a38f90-ffffffff81a38fea: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817726c0)
Location: drivers/tty/serial/serial_core.c:2680
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81820a30)
Location: drivers/nvdimm/dimm_devs.c:310
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81a3ab80)
Location: net/core/net-sysfs.c:356
Inline: False
```
**Symbols:**

```
ffffffff817726c0-ffffffff8177271c: flags_show (STB_LOCAL)
ffffffff81820a30-ffffffff81820a9a: flags_show (STB_LOCAL)
ffffffff81a3ab80-ffffffff81a3abda: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81691df0)
Location: drivers/acpi/dock.c:502
Inline: False
```
```
In drivers/tty/serial/serial_core.c (ffffffff81756150)
Location: drivers/tty/serial/serial_core.c:2677
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81803d30)
Location: drivers/nvdimm/dimm_devs.c:310
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81a224e0)
Location: net/core/net-sysfs.c:356
Inline: False
```
**Symbols:**

```
ffffffff81691df0-ffffffff81691e1b: flags_show (STB_LOCAL)
ffffffff81756150-ffffffff817561ac: flags_show (STB_LOCAL)
ffffffff81803d30-ffffffff81803d9a: flags_show (STB_LOCAL)
ffffffff81a224e0-ffffffff81a22536: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81707900)
Location: drivers/acpi/dock.c:502
Inline: False
```
```
In drivers/tty/serial/serial_core.c (ffffffff817d9880)
Location: drivers/tty/serial/serial_core.c:2692
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e0b0)
Location: drivers/nvdimm/dimm_devs.c:310
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81ad6480)
Location: net/core/net-sysfs.c:376
Inline: False
```
**Symbols:**

```
ffffffff81707900-ffffffff8170792b: flags_show (STB_LOCAL)
ffffffff817d9880-ffffffff817d98dc: flags_show (STB_LOCAL)
ffffffff8188e0b0-ffffffff8188e11a: flags_show (STB_LOCAL)
ffffffff81ad6480-ffffffff81ad64d6: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81835ce0)
Location: drivers/acpi/dock.c:501
Inline: False
```
```
In drivers/tty/serial/serial_core.c (ffffffff819181f0)
Location: drivers/tty/serial/serial_core.c:2739
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7690)
Location: drivers/nvdimm/dimm_devs.c:290
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81c568f0)
Location: net/core/net-sysfs.c:378
Inline: False
```
**Symbols:**

```
ffffffff81835ce0-ffffffff81835d10: flags_show (STB_LOCAL)
ffffffff819181f0-ffffffff81918268: flags_show (STB_LOCAL)
ffffffff819d7690-ffffffff819d76f3: flags_show (STB_LOCAL)
ffffffff81c568f0-ffffffff81c56953: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff81969cb0)
Location: drivers/acpi/dock.c:501
Inline: False
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a73bb0)
Location: drivers/tty/serial/serial_core.c:2873
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52480)
Location: drivers/nvdimm/dimm_devs.c:290
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81e0c880)
Location: net/core/net-sysfs.c:378
Inline: False
```
**Symbols:**

```
ffffffff81969cb0-ffffffff81969ce0: flags_show (STB_LOCAL)
ffffffff81a73bb0-ffffffff81a73c28: flags_show (STB_LOCAL)
ffffffff81b52480-ffffffff81b524e3: flags_show (STB_LOCAL)
ffffffff81e0c880-ffffffff81e0c8e3: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff819b0270)
Location: drivers/acpi/dock.c:501
Inline: False
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abe240)
Location: drivers/tty/serial/serial_core.c:2905
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba59a0)
Location: drivers/nvdimm/dimm_devs.c:290
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81e7f8d0)
Location: net/core/net-sysfs.c:378
Inline: False
```
**Symbols:**

```
ffffffff819b0270-ffffffff819b02a0: flags_show (STB_LOCAL)
ffffffff81abe240-ffffffff81abe2b8: flags_show (STB_LOCAL)
ffffffff81ba59a0-ffffffff81ba5a03: flags_show (STB_LOCAL)
ffffffff81e7f8d0-ffffffff81e7f933: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/dock.c (ffffffff819fa720)
Location: drivers/acpi/dock.c:501
Inline: False
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b11030)
Location: drivers/tty/serial/serial_core.c:2941
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bf9c20)
Location: drivers/nvdimm/dimm_devs.c:292
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81f40850)
Location: net/core/net-sysfs.c:390
Inline: False
```
**Symbols:**

```
ffffffff819fa720-ffffffff819fa750: flags_show (STB_LOCAL)
ffffffff81b11030-ffffffff81b11095: flags_show (STB_LOCAL)
ffffffff81bf9c20-ffffffff81bf9c83: flags_show (STB_LOCAL)
ffffffff81f40850-ffffffff81f408b3: flags_show (STB_LOCAL)
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
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff800010953808)
Location: drivers/nvdimm/dimm_devs.c:320
Inline: False
```
```
In net/core/net-sysfs.c (ffff800010c0ab10)
Location: net/core/net-sysfs.c:343
Inline: False
```
**Symbols:**

```
ffff800010953808-ffff800010953890: flags_show (STB_LOCAL)
ffff800010c0ab10-ffff800010c0ab4c: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c0d240f0)
Location: net/core/net-sysfs.c:343
Inline: False
```
**Symbols:**

```
c0d240f0-c0d24118: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a00580)
Location: drivers/nvdimm/dimm_devs.c:320
Inline: False
```
```
In net/core/net-sysfs.c (c000000000cf5700)
Location: net/core/net-sysfs.c:343
Inline: False
```
**Symbols:**

```
c000000000a00580-c000000000a00608: flags_show (STB_LOCAL)
c000000000cf5700-c000000000cf5720: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c30ba)
Location: drivers/nvdimm/dimm_devs.c:320
Inline: False
```
```
In net/core/net-sysfs.c (ffffffe000787ff8)
Location: net/core/net-sysfs.c:343
Inline: False
```
**Symbols:**

```
ffffffe000787ff8-ffffffe000788032: flags_show (STB_LOCAL)
ffffffe0005c30ba-ffffffe0005c313c: flags_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817076b0)
Location: drivers/nvdimm/dimm_devs.c:320
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff81905070)
Location: net/core/net-sysfs.c:343
Inline: False
```
**Symbols:**

```
ffffffff817076b0-ffffffff8170771d: flags_show (STB_LOCAL)
ffffffff81905070-ffffffff8190508a: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/nfit/core.c (ffffffff815f3940)
Location: drivers/acpi/nfit/core.c:1605
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816db130)
Location: drivers/nvdimm/dimm_devs.c:320
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff818beea0)
Location: net/core/net-sysfs.c:343
Inline: False
```
**Symbols:**

```
ffffffff815f3940-ffffffff815f3a17: flags_show (STB_LOCAL)
ffffffff816db130-ffffffff816db19d: flags_show (STB_LOCAL)
ffffffff818beea0-ffffffff818beeba: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81746480)
Location: drivers/nvdimm/dimm_devs.c:320
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff819560a0)
Location: net/core/net-sysfs.c:343
Inline: False
```
**Symbols:**

```
ffffffff81746480-ffffffff817464ed: flags_show (STB_LOCAL)
ffffffff819560a0-ffffffff819560ba: flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t flags_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817618c0)
Location: drivers/nvdimm/dimm_devs.c:320
Inline: False
```
```
In net/core/net-sysfs.c (ffffffff819782a0)
Location: net/core/net-sysfs.c:343
Inline: False
```
**Symbols:**

```
ffffffff817618c0-ffffffff8176192d: flags_show (STB_LOCAL)
ffffffff819782a0-ffffffff819782ba: flags_show (STB_LOCAL)
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
