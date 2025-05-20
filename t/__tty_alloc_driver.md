# Function: <code>__tty_alloc_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e08e0)
Location: drivers/tty/tty_io.c:3368
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff814e08e0-ffffffff814e0a2f: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81532d50)
Location: drivers/tty/tty_io.c:3364
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81532d50-ffffffff81532ea4: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155f480)
Location: drivers/tty/tty_io.c:3364
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8155f480-ffffffff8155f5d4: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815749b0)
Location: drivers/tty/tty_io.c:2922
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff815749b0-ffffffff81574b11: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d9180)
Location: drivers/tty/tty_io.c:3029
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff815d9180-ffffffff815d92e1: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81612120)
Location: drivers/tty/tty_io.c:3050
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff81612120-ffffffff81612274: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162f1c0)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff8162f1c0-ffffffff8162f314: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81663060)
Location: drivers/tty/tty_io.c:3209
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff81663060-ffffffff816631c3: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816856d0)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff816856d0-ffffffff81685833: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81737030)
Location: drivers/tty/tty_io.c:3208
Inline: True
Direct callers:
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_init
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff81737030-ffffffff8173718d: __tty_alloc_driver.part.0 (STB_LOCAL)
ffffffff81737190-ffffffff817371b5: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817533f0)
Location: drivers/tty/tty_io.c:3301
Inline: True
Direct callers:
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_init
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
**Symbols:**

```
ffffffff817533f0-ffffffff8175354d: __tty_alloc_driver.part.0 (STB_LOCAL)
ffffffff81753550-ffffffff81753575: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81735c80)
Location: drivers/tty/tty_io.c:3350
Inline: True
Direct callers:
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe
```
**Symbols:**

```
ffffffff81735c80-ffffffff81735dea: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b6640)
Location: drivers/tty/tty_io.c:3350
Inline: True
Direct callers:
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe
```
**Symbols:**

```
ffffffff817b6640-ffffffff817b67aa: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f3880)
Location: drivers/tty/tty_io.c:3317
Inline: True
Direct callers:
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
**Symbols:**

```
ffffffff818f3880-ffffffff818f39ce: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4bde0)
Location: drivers/tty/tty_io.c:3315
Inline: True
Direct callers:
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
**Symbols:**

```
ffffffff81a4bde0-ffffffff81a4bf27: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a96000)
Location: drivers/tty/tty_io.c:3321
Inline: True
Direct callers:
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
**Symbols:**

```
ffffffff81a96000-ffffffff81a96147: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae8ca0)
Location: drivers/tty/tty_io.c:3338
Inline: True
Direct callers:
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:unix98_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/pty.c:legacy_pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
**Symbols:**

```
ffffffff81ae8ca0-ffffffff81ae8e1e: __tty_alloc_driver (STB_GLOBAL)
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
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010851120)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffff800010851120-ffff800010851260: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095dab4)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
c095dab4-c095dc20: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008f2220)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvsi.c:hvsi_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
c0000000008f2220-c0000000008f2428: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052f2b0)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffe00052f2b0-ffffffe00052f3d6: __tty_alloc_driver (STB_GLOBAL)
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
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8164b150)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8164b150-ffffffff8164b2b3: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162b5a0)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff8162b5a0-ffffffff8162b703: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81679510)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff81679510-ffffffff81679673: __tty_alloc_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct tty_driver *__tty_alloc_driver(unsigned int lines, struct module *owner, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81693b70)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/pty.c:pty_init
  - drivers/tty/vt/vt.c:vty_init
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff81693b70-ffffffff81693cd3: __tty_alloc_driver (STB_GLOBAL)
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
