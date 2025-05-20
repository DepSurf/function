# Function: <code>tty_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0620)
Location: drivers/tty/tty_io.c:3480
Inline: False
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
ffffffff814e0620-ffffffff814e081a: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81531f30)
Location: drivers/tty/tty_io.c:3476
Inline: False
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
ffffffff81531f30-ffffffff81532132: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155e620)
Location: drivers/tty/tty_io.c:3476
Inline: False
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
ffffffff8155e620-ffffffff8155e822: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815747c0)
Location: drivers/tty/tty_io.c:3029
Inline: False
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
ffffffff815747c0-ffffffff815749a6: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d7940)
Location: drivers/tty/tty_io.c:3136
Inline: False
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
ffffffff815d7940-ffffffff815d7b26: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816106b0)
Location: drivers/tty/tty_io.c:3157
Inline: False
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
ffffffff816106b0-ffffffff816108a7: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162d4b0)
Location: drivers/tty/tty_io.c:3312
Inline: False
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
ffffffff8162d4b0-ffffffff8162d6a7: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816610e0)
Location: drivers/tty/tty_io.c:3316
Inline: False
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
ffffffff816610e0-ffffffff816612c2: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81683730)
Location: drivers/tty/tty_io.c:3312
Inline: False
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
ffffffff81683730-ffffffff81683912: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81734aa0)
Location: drivers/tty/tty_io.c:3315
Inline: False
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
ffffffff81734aa0-ffffffff81734c76: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817508e0)
Location: drivers/tty/tty_io.c:3408
Inline: False
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
ffffffff817508e0-ffffffff81750ab6: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81734760)
Location: drivers/tty/tty_io.c:3457
Inline: False
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
ffffffff81734760-ffffffff81734936: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b50c0)
Location: drivers/tty/tty_io.c:3444
Inline: False
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
ffffffff817b50c0-ffffffff817b5296: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f0fd0)
Location: drivers/tty/tty_io.c:3420
Inline: False
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
ffffffff818f0fd0-ffffffff818f11b9: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a49150)
Location: drivers/tty/tty_io.c:3417
Inline: False
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
ffffffff81a49150-ffffffff81a49339: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a93380)
Location: drivers/tty/tty_io.c:3423
Inline: False
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
ffffffff81a93380-ffffffff81a93569: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae5e00)
Location: drivers/tty/tty_io.c:3440
Inline: False
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
ffffffff81ae5e00-ffffffff81ae5fe9: tty_register_driver (STB_GLOBAL)
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
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084fba8)
Location: drivers/tty/tty_io.c:3312
Inline: False
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
ffff80001084fba8-ffff80001084fd8c: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095bc38)
Location: drivers/tty/tty_io.c:3312
Inline: False
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
c095bc38-c095be28: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008f1f70)
Location: drivers/tty/tty_io.c:3312
Inline: False
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
c0000000008f1f70-c0000000008f2218: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052e366)
Location: drivers/tty/tty_io.c:3312
Inline: False
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
ffffffe00052e366-ffffffe00052e4ee: tty_register_driver (STB_GLOBAL)
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
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816491b0)
Location: drivers/tty/tty_io.c:3312
Inline: False
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
ffffffff816491b0-ffffffff81649392: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81629610)
Location: drivers/tty/tty_io.c:3312
Inline: False
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
ffffffff81629610-ffffffff816297f2: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81677570)
Location: drivers/tty/tty_io.c:3312
Inline: False
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
ffffffff81677570-ffffffff81677752: tty_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_register_driver(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81691db0)
Location: drivers/tty/tty_io.c:3312
Inline: False
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
ffffffff81691db0-ffffffff81691f92: tty_register_driver (STB_GLOBAL)
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
