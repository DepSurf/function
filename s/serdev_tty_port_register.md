# Function: <code>serdev_tty_port_register</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (0)
Location: include/linux/serdev.h:313
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff8160a3a0)
Location: drivers/tty/serdev/serdev-ttyport.c:236
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
ffffffff8160a3a0-ffffffff8160a492: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81643ce0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
ffffffff81643ce0-ffffffff81643ddf: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81661fb0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
ffffffff81661fb0-ffffffff816620af: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
ffffffff81697c9a-ffffffff81697cbe: serdev_tty_port_register.cold (STB_LOCAL)
ffffffff81697b50-ffffffff81697c3d: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
ffffffff816ba81a-ffffffff816ba83e: serdev_tty_port_register.cold (STB_LOCAL)
ffffffff816ba6e0-ffffffff816ba7be: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
```
**Symbols:**

```
ffffffff8176ec8a-ffffffff8176ecae: serdev_tty_port_register.cold (STB_LOCAL)
ffffffff8176eb50-ffffffff8176ec2e: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
```
**Symbols:**

```
ffffffff81c084c1-ffffffff81c084e5: serdev_tty_port_register.cold (STB_LOCAL)
ffffffff81789450-ffffffff8178952e: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
```
**Symbols:**

```
ffffffff81bfa086-ffffffff81bfa0aa: serdev_tty_port_register.cold (STB_LOCAL)
ffffffff8176cd30-ffffffff8176ce0e: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
```
**Symbols:**

```
ffffffff81cfa960-ffffffff81cfa984: serdev_tty_port_register.cold (STB_LOCAL)
ffffffff817f2470-ffffffff817f254e: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
```
**Symbols:**

```
ffffffff81ec2c02-ffffffff81ec2c26: serdev_tty_port_register.cold (STB_LOCAL)
ffffffff81932cc0-ffffffff81932dba: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81a918d0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
```
**Symbols:**

```
ffffffff81a918d0-ffffffff81a919fc: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81add140)
Location: drivers/tty/serdev/serdev-ttyport.c:276
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
```
**Symbols:**

```
ffffffff81add140-ffffffff81add26b: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *host, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffff81b30540)
Location: drivers/tty/serdev/serdev-ttyport.c:276
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
```
**Symbols:**

```
ffffffff81b30540-ffffffff81b30677: serdev_tty_port_register (STB_GLOBAL)
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
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffff8000108aa928)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
ffff8000108aa928-ffff8000108aaa10: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (c09a6c74)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
c09a6c74-c09a6d54: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (c000000000942000)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
c000000000942000-c0000000009421ac: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (ffffffe00055f97e)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
ffffffe00055f97e-ffffffe00055fa42: serdev_tty_port_register (STB_GLOBAL)
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
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
ffffffff8168027a-ffffffff8168029e: serdev_tty_port_register.cold (STB_LOCAL)
ffffffff81680140-ffffffff8168021e: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (0)
Location: include/linux/serdev.h:318
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
ffffffff816ae65a-ffffffff816ae67e: serdev_tty_port_register.cold (STB_LOCAL)
ffffffff816ae520-ffffffff816ae5fe: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct device *serdev_tty_port_register(struct tty_port *port, struct device *parent, struct tty_driver *drv, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serdev/serdev-ttyport.c (0)
Location: drivers/tty/serdev/serdev-ttyport.c:264
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
```
**Symbols:**

```
ffffffff816c8aba-ffffffff816c8ade: serdev_tty_port_register.cold (STB_LOCAL)
ffffffff816c8980-ffffffff816c8a5e: serdev_tty_port_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param reordered. </b>
<code>port, parent, drv, idx</code> ➡️ <code>port, host, parent, drv, idx</code>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
