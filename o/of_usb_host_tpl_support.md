# Function: <code>of_usb_host_tpl_support</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb/of.h:31
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/usb/of.h:31
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: include/linux/usb/of.h:31
Inline: True
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
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb/of.h:31
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/usb/of.h:31
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: include/linux/usb/of.h:31
Inline: True
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
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/usb/of.h:31
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/usb/of.h:31
Inline: True
```
```
In drivers/usb/host/ohci-platform.c (0)
Location: include/linux/usb/of.h:31
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool of_usb_host_tpl_support(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/common.c (ffff800010a10610)
Location: drivers/usb/common/common.c:208
Inline: False
```
**Symbols:**

```
ffff800010a10610-ffff800010a10650: of_usb_host_tpl_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool of_usb_host_tpl_support(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/common.c (c0ae8d2c)
Location: drivers/usb/common/common.c:208
Inline: False
```
**Symbols:**

```
c0ae8d2c-c0ae8d5c: of_usb_host_tpl_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool of_usb_host_tpl_support(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/common.c (c000000000ac72f0)
Location: drivers/usb/common/common.c:208
Inline: False
```
**Symbols:**

```
c000000000ac72f0-c000000000ac7338: of_usb_host_tpl_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool of_usb_host_tpl_support(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/common.c (ffffffe000636418)
Location: drivers/usb/common/common.c:208
Inline: False
```
**Symbols:**

```
ffffffe000636418-ffffffe000636450: of_usb_host_tpl_support (STB_GLOBAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
