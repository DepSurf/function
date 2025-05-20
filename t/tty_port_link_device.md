# Function: <code>tty_port_link_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff814eb040)
Location: drivers/tty/tty_port.c:46
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/tty_port.c:tty_port_register_device_attr
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff814eb040-ffffffff814eb06f: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8153bed0)
Location: drivers/tty/tty_port.c:46
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8153bed0-ffffffff8153beff: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81568530)
Location: drivers/tty/tty_port.c:46
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81568530-ffffffff8156855f: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8157bc9b)
Location: drivers/tty/tty_port.c:86
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr
Direct callers:
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8157bc60-ffffffff8157bc81: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff815e05f0)
Location: drivers/tty/tty_port.c:87
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff815e05f0-ffffffff815e0610: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81619630)
Location: drivers/tty/tty_port.c:87
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81619630-ffffffff81619650: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff816368a0)
Location: drivers/tty/tty_port.c:87
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff816368a0-ffffffff816368c0: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_port.c (0)
Location: drivers/tty/tty_port.c:87
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8166b93d-ffffffff8166b950: tty_port_link_device.cold (STB_LOCAL)
ffffffff8166ad70-ffffffff8166ad91: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8168d4d5)
Location: drivers/tty/tty_port.c:88
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8168d440-ffffffff8168d461: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173fba5)
Location: drivers/tty/tty_port.c:88
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8173f4c0-ffffffff8173f4e1: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8175bade)
Location: drivers/tty/tty_port.c:88
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8175b3f0-ffffffff8175b411: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173f9fe)
Location: drivers/tty/tty_port.c:89
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8173f290-ffffffff8173f2b1: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff817c019e)
Location: drivers/tty/tty_port.c:89
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff817bfa20-ffffffff817bfa41: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff818fc86e)
Location: drivers/tty/tty_port.c:98
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff818fc040-ffffffff818fc079: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81a55eee)
Location: drivers/tty/tty_port.c:119
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81a555c0-ffffffff81a555f9: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81aa04ce)
Location: drivers/tty/tty_port.c:119
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
Direct callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81a9fba0-ffffffff81a9fbd9: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81af2f2a)
Location: drivers/tty/tty_port.c:117
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
Direct callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81af25f0-ffffffff81af2629: tty_port_link_device (STB_GLOBAL)
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
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffff80001085de08)
Location: drivers/tty/tty_port.c:88
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffff80001085de08-ffff80001085de64: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (c0965994)
Location: drivers/tty/tty_port.c:88
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
c0965994-c09659dc: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (c0000000008fd3d0)
Location: drivers/tty/tty_port.c:88
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/hvc/hvsi.c:hvsi_init
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
c0000000008fd3d0-c0000000008fd404: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffe000536b40)
Location: drivers/tty/tty_port.c:88
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffe000536b40-ffffffe000536b92: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81652f55)
Location: drivers/tty/tty_port.c:88
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81652ec0-ffffffff81652ee1: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81633395)
Location: drivers/tty/tty_port.c:88
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81633300-ffffffff81633321: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81681315)
Location: drivers/tty/tty_port.c:88
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81681280-ffffffff816812a1: tty_port_link_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tty_port_link_device(struct tty_port *port, struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8169b965)
Location: drivers/tty/tty_port.c:88
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_register_device_attr_serdev
  - drivers/tty/tty_port.c:tty_port_register_device_attr
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8169b8d0-ffffffff8169b8f1: tty_port_link_device (STB_GLOBAL)
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
