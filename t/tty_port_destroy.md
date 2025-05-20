# Function: <code>tty_port_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff814eb250)
Location: drivers/tty/tty_port.c:131
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff814eb250-ffffffff814eb26d: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8153c120)
Location: drivers/tty/tty_port.c:131
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8153c0d0-ffffffff8153c0ed: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81568780)
Location: drivers/tty/tty_port.c:131
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81568730-ffffffff8156874d: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8157beca)
Location: drivers/tty/tty_port.c:244
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8157be70-ffffffff8157be8d: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff815e0900)
Location: drivers/tty/tty_port.c:245
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff815e08b0-ffffffff815e08cd: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81619ba0)
Location: drivers/tty/tty_port.c:245
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81619b50-ffffffff81619b6d: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81636e10)
Location: drivers/tty/tty_port.c:245
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81636dc0-ffffffff81636ddd: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8166b0a4)
Location: drivers/tty/tty_port.c:245
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8166b050-ffffffff8166b06f: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8168d740)
Location: drivers/tty/tty_port.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8168d6f0-ffffffff8168d70f: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173f630)
Location: drivers/tty/tty_port.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8173f5d0-ffffffff8173f5f1: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8175b560)
Location: drivers/tty/tty_port.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8175b500-ffffffff8175b521: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8173f400)
Location: drivers/tty/tty_port.c:247
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8173f3a0-ffffffff8173f3c1: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff817bfc50)
Location: drivers/tty/tty_port.c:247
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff817bfbf0-ffffffff817bfc11: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff818fc32b)
Location: drivers/tty/tty_port.c:258
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff818fc2d0-ffffffff818fc2f8: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81a5591b)
Location: drivers/tty/tty_port.c:279
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81a558b0-ffffffff81a558d8: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81a9fefb)
Location: drivers/tty/tty_port.c:279
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81a9fe90-ffffffff81a9feb8: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81af294b)
Location: drivers/tty/tty_port.c:279
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81af28e0-ffffffff81af2908: tty_port_destroy (STB_GLOBAL)
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
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffff80001085e130)
Location: drivers/tty/tty_port.c:246
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffff80001085e130-ffff80001085e164: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (c0965bf4)
Location: drivers/tty/tty_port.c:246
Inline: True
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
c0965bf4-c0965c1c: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (c0000000008fd9b8)
Location: drivers/tty/tty_port.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
Direct callers:
  - drivers/tty/hvc/hvsi.c:hvsi_console_init
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
c0000000008fd8d0-c0000000008fd91c: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffe000536eee)
Location: drivers/tty/tty_port.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffe000536e72-ffffffe000536ea6: tty_port_destroy (STB_GLOBAL)
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
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff816531c0)
Location: drivers/tty/tty_port.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81653170-ffffffff8165318f: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff816335b0)
Location: drivers/tty/tty_port.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81633560-ffffffff8163357f: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff81681580)
Location: drivers/tty/tty_port.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81681530-ffffffff8168154f: tty_port_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tty_port_destroy(struct tty_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_port.c (ffffffff8169bbd0)
Location: drivers/tty/tty_port.c:246
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_destructor
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_cleanup
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8169bb80-ffffffff8169bb9f: tty_port_destroy (STB_GLOBAL)
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
