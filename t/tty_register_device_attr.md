# Function: <code>tty_register_device_attr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0360)
Location: drivers/tty/tty_io.c:3278
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr
```
**Symbols:**

```
ffffffff814e0360-ffffffff814e0600: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81531c60)
Location: drivers/tty/tty_io.c:3274
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr
```
**Symbols:**

```
ffffffff81531c60-ffffffff81531f07: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155e350)
Location: drivers/tty/tty_io.c:3274
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr
```
**Symbols:**

```
ffffffff8155e350-ffffffff8155e5f7: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815745a0)
Location: drivers/tty/tty_io.c:2821
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr
  - drivers/tty/tty_port.c:tty_port_register_device_attr
```
**Symbols:**

```
ffffffff815745a0-ffffffff81574791: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d7720)
Location: drivers/tty/tty_io.c:2928
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff815d7720-ffffffff815d7911: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2949
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff816130ee-ffffffff8161310c: tty_register_device_attr.cold.36 (STB_LOCAL)
ffffffff816104b0-ffffffff81610685: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3104
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff8163018e-ffffffff816301ac: tty_register_device_attr.cold.35 (STB_LOCAL)
ffffffff8162d2b0-ffffffff8162d48c: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3108
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81664092-ffffffff816640b1: tty_register_device_attr.cold (STB_LOCAL)
ffffffff81660ee0-ffffffff816610bf: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3104
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr
  - drivers/tty/tty_port.c:tty_port_register_device_attr
```
**Symbols:**

```
ffffffff81686702-ffffffff81686721: tty_register_device_attr.cold (STB_LOCAL)
ffffffff81683530-ffffffff8168370f: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3107
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff817384c2-ffffffff817384df: tty_register_device_attr.cold (STB_LOCAL)
ffffffff81734860-ffffffff81734a7d: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3200
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81c07355-ffffffff81c07372: tty_register_device_attr.cold (STB_LOCAL)
ffffffff817506a0-ffffffff817508bd: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3249
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81bf8fbf-ffffffff81bf8fdc: tty_register_device_attr.cold (STB_LOCAL)
ffffffff81734520-ffffffff8173473d: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3249
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81cf8748-ffffffff81cf8765: tty_register_device_attr.cold (STB_LOCAL)
ffffffff817b4e80-ffffffff817b509d: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3217
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81ec087d-ffffffff81ec0898: tty_register_device_attr.cold (STB_LOCAL)
ffffffff818f0d80-ffffffff818f0f98: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a48ec0)
Location: drivers/tty/tty_io.c:3215
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81a48ec0-ffffffff81a490f3: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a93100)
Location: drivers/tty/tty_io.c:3222
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81a93100-ffffffff81a93330: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae5b50)
Location: drivers/tty/tty_io.c:3239
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffff81ae5b50-ffffffff81ae5daf: tty_register_device_attr (STB_GLOBAL)
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
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084f678)
Location: drivers/tty/tty_io.c:3104
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffff80001084f678-ffff80001084f884: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095b000)
Location: drivers/tty/tty_io.c:3104
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
c095b000-c095b1fc: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008f1ca0)
Location: drivers/tty/tty_io.c:3104
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
c0000000008f1ca0-c0000000008f1f44: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052e152)
Location: drivers/tty/tty_io.c:3104
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
```
**Symbols:**

```
ffffffe00052e152-ffffffe00052e328: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3104
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr
  - drivers/tty/tty_port.c:tty_port_register_device_attr
```
**Symbols:**

```
ffffffff8164c182-ffffffff8164c1a1: tty_register_device_attr.cold (STB_LOCAL)
ffffffff81648fb0-ffffffff8164918f: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3104
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr
  - drivers/tty/tty_port.c:tty_port_register_device_attr
```
**Symbols:**

```
ffffffff8162c5d2-ffffffff8162c5f1: tty_register_device_attr.cold (STB_LOCAL)
ffffffff81629410-ffffffff816295ef: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3104
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr
  - drivers/tty/tty_port.c:tty_port_register_device_attr
```
**Symbols:**

```
ffffffff8167a542-ffffffff8167a561: tty_register_device_attr.cold (STB_LOCAL)
ffffffff81677370-ffffffff8167754f: tty_register_device_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct device *tty_register_device_attr(struct tty_driver *driver, unsigned int index, struct device *device, void *drvdata, const struct attribute_group **attr_grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:3104
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr
  - drivers/tty/tty_port.c:tty_port_register_device_attr
```
**Symbols:**

```
ffffffff81694d0a-ffffffff81694d29: tty_register_device_attr.cold (STB_LOCAL)
ffffffff81691bb0-ffffffff81691d8f: tty_register_device_attr (STB_GLOBAL)
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
