# Function: <code>tty_port_register_device_attr_serdev</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (0)
Location: drivers/tty/tty_port.c:150
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff8157bd00-ffffffff8157bd10: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff815e06a0)
Location: drivers/tty/tty_port.c:151
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff815e06a0-ffffffff815e0718: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81619940)
Location: drivers/tty/tty_port.c:151
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff81619940-ffffffff816199b8: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81636bb0)
Location: drivers/tty/tty_port.c:151
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff81636bb0-ffffffff81636c28: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8166ae30)
Location: drivers/tty/tty_port.c:151
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff8166ae30-ffffffff8166aea8: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8168d4d0)
Location: drivers/tty/tty_port.c:152
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff8168d4d0-ffffffff8168d545: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173fba5)
Location: drivers/tty/tty_port.c:152
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff8173fc10-ffffffff8173fc85: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8175bade)
Location: drivers/tty/tty_port.c:152
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff8175bb40-ffffffff8175bbb5: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173f9fe)
Location: drivers/tty/tty_port.c:153
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff8173f970-ffffffff8173f9e5: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff817c019e)
Location: drivers/tty/tty_port.c:153
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff817bfa90-ffffffff817bfb05: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff818fc86e)
Location: drivers/tty/tty_port.c:162
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff818fc0f0-ffffffff818fc189: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81a55eee)
Location: drivers/tty/tty_port.c:183
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff81a55690-ffffffff81a55729: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81aa04ce)
Location: drivers/tty/tty_port.c:183
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
Direct callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
```
**Symbols:**

```
ffffffff81a9fc70-ffffffff81a9fd09: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *host, struct device *parent, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81af2f2a)
Location: drivers/tty/tty_port.c:182
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
Direct callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
```
**Symbols:**

```
ffffffff81af26c0-ffffffff81af2754: tty_port_register_device_attr_serdev (STB_GLOBAL)
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
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffff80001085df38)
Location: drivers/tty/tty_port.c:152
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffff80001085df38-ffff80001085dfd8: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (c0965a70)
Location: drivers/tty/tty_port.c:152
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
c0965a70-c0965ae4: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (c0000000008fd500)
Location: drivers/tty/tty_port.c:152
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
c0000000008fd500-c0000000008fd5e4: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffe000536c42)
Location: drivers/tty/tty_port.c:152
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffe000536c42-ffffffe000536cb8: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81652f50)
Location: drivers/tty/tty_port.c:152
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff81652f50-ffffffff81652fc5: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81633390)
Location: drivers/tty/tty_port.c:152
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff81633390-ffffffff816333cd: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81681310)
Location: drivers/tty/tty_port.c:152
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff81681310-ffffffff81681385: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr_serdev(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8169b960)
Location: drivers/tty/tty_port.c:152
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff8169b960-ffffffff8169b9d5: tty_port_register_device_attr_serdev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *host</code>
</li>
<li>
<b>Param added. </b>
<code>struct device *parent</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *device</code>
</li>
<li>
<b>Param reordered. </b>
<code>port, driver, index, device, drvdata, attr_grp</code> ➡️ <code>port, driver, index, host, parent, drvdata, attr_grp</code>
</li>
</ul>
</details>
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
