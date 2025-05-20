# Function: <code>tty_unregister_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0040)
Location: drivers/tty/tty_io.c:3348
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff814e0040-ffffffff814e008e: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81531870)
Location: drivers/tty/tty_io.c:3344
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81531870-ffffffff815318be: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155dfb0)
Location: drivers/tty/tty_io.c:3344
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff8155dfb0-ffffffff8155dffe: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572f20)
Location: drivers/tty/tty_io.c:2902
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_driver_kref_put
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff81572f20-ffffffff81572f6e: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d72b0)
Location: drivers/tty/tty_io.c:3009
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff815d72b0-ffffffff815d72fe: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81610250)
Location: drivers/tty/tty_io.c:3030
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81610250-ffffffff816102a3: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162d050)
Location: drivers/tty/tty_io.c:3185
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8162d050-ffffffff8162d0a3: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81660cb0)
Location: drivers/tty/tty_io.c:3189
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81660cb0-ffffffff81660d03: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81683300)
Location: drivers/tty/tty_io.c:3185
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81683300-ffffffff81683353: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817341e0)
Location: drivers/tty/tty_io.c:3188
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff817341e0-ffffffff81734233: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81750330)
Location: drivers/tty/tty_io.c:3281
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81750330-ffffffff81750383: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817341b0)
Location: drivers/tty/tty_io.c:3330
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff817341b0-ffffffff81734203: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b4b10)
Location: drivers/tty/tty_io.c:3330
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
```
**Symbols:**

```
ffffffff817b4b10-ffffffff817b4b63: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f0920)
Location: drivers/tty/tty_io.c:3297
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
```
**Symbols:**

```
ffffffff818f0920-ffffffff818f0987: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a48ad0)
Location: drivers/tty/tty_io.c:3295
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
```
**Symbols:**

```
ffffffff81a48ad0-ffffffff81a48b37: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a92d20)
Location: drivers/tty/tty_io.c:3302
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
```
**Symbols:**

```
ffffffff81a92d20-ffffffff81a92d87: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae5770)
Location: drivers/tty/tty_io.c:3319
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
```
**Symbols:**

```
ffffffff81ae5770-ffffffff81ae57d7: tty_unregister_device (STB_GLOBAL)
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
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084f8d8)
Location: drivers/tty/tty_io.c:3185
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_driver_kref_put
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffff80001084f8d8-ffff80001084f940: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095b90c)
Location: drivers/tty/tty_io.c:3185
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_driver_kref_put
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
c095b90c-c095b96c: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ef9c0)
Location: drivers/tty/tty_io.c:3185
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_driver_kref_put
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
c0000000008ef9c0-c0000000008efa78: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052dd4a)
Location: drivers/tty/tty_io.c:3185
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffe00052dd4a-ffffffe00052ddbe: tty_unregister_device (STB_GLOBAL)
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
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81648d80)
Location: drivers/tty/tty_io.c:3185
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
```
**Symbols:**

```
ffffffff81648d80-ffffffff81648dd3: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816291e0)
Location: drivers/tty/tty_io.c:3185
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff816291e0-ffffffff81629233: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81677140)
Location: drivers/tty/tty_io.c:3185
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81677140-ffffffff81677193: tty_unregister_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tty_unregister_device(struct tty_driver *driver, unsigned int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81691860)
Location: drivers/tty/tty_io.c:3185
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:destruct_tty_driver
  - drivers/tty/tty_port.c:tty_port_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81691860-ffffffff816918b3: tty_unregister_device (STB_GLOBAL)
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
