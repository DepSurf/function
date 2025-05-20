# Function: <code>tty_port_register_device_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff814eb0b0)
Location: drivers/tty/tty_port.c:88
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff814eb0b0-ffffffff814eb0f5: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8153bf40)
Location: drivers/tty/tty_port.c:88
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff8153bf40-ffffffff8153bf85: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff815685a0)
Location: drivers/tty/tty_port.c:88
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
```
**Symbols:**

```
ffffffff815685a0-ffffffff815685e5: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8157bc90)
Location: drivers/tty/tty_port.c:127
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff8157bc90-ffffffff8157bcd0: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff815e0677)
Location: drivers/tty/tty_port.c:128
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff815e0610-ffffffff815e0655: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81619905)
Location: drivers/tty/tty_port.c:128
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff816198b0-ffffffff816198f5: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81636b75)
Location: drivers/tty/tty_port.c:128
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81636b20-ffffffff81636b65: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8166adf5)
Location: drivers/tty/tty_port.c:128
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff8166ada0-ffffffff8166ade5: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8168d470)
Location: drivers/tty/tty_port.c:129
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff8168d470-ffffffff8168d4ad: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173fb25)
Location: drivers/tty/tty_port.c:129
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff8173fb60-ffffffff8173fb9d: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8175baa1)
Location: drivers/tty/tty_port.c:129
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff8175ba50-ffffffff8175ba8d: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173f901)
Location: drivers/tty/tty_port.c:130
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff8173f930-ffffffff8173f96d: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff817c0161)
Location: drivers/tty/tty_port.c:130
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff817bfa50-ffffffff817bfa8d: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff818fc811)
Location: drivers/tty/tty_port.c:139
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff818fc080-ffffffff818fc0e7: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81a55e81)
Location: drivers/tty/tty_port.c:160
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81a55610-ffffffff81a55677: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81aa0461)
Location: drivers/tty/tty_port.c:160
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81a9fbf0-ffffffff81a9fc57: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81af2eb1)
Location: drivers/tty/tty_port.c:158
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81af2640-ffffffff81af26a7: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffff80001085df00)
Location: drivers/tty/tty_port.c:129
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffff80001085de68-ffff80001085ded8: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (c0965a40)
Location: drivers/tty/tty_port.c:129
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
c09659dc-c0965a28: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (c0000000008fd4b8)
Location: drivers/tty/tty_port.c:129
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
c0000000008fd410-c0000000008fd488: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffe000536c12)
Location: drivers/tty/tty_port.c:129
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffe000536b92-ffffffe000536bf0: tty_port_register_device_attr (STB_GLOBAL)
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
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81652ef0)
Location: drivers/tty/tty_port.c:129
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81652ef0-ffffffff81652f2d: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81633330)
Location: drivers/tty/tty_port.c:129
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81633330-ffffffff8163336d: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff816812b0)
Location: drivers/tty/tty_port.c:129
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff816812b0-ffffffff816812ed: tty_port_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *tty_port_register_device_attr(struct tty_port *port, struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8169b900)
Location: drivers/tty/tty_port.c:129
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff8169b900-ffffffff8169b93d: tty_port_register_device_attr (STB_GLOBAL)
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
