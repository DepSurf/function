# Function: <code>put_tty_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0a30)
Location: drivers/tty/tty_io.c:3471
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff814e0a30-ffffffff814e0a4f: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81532140)
Location: drivers/tty/tty_io.c:3467
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81532140-ffffffff8153215f: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155e870)
Location: drivers/tty/tty_io.c:3467
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff8155e870-ffffffff8155e88f: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81573040)
Location: drivers/tty/tty_io.c:3020
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81573040-ffffffff81573050: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d7b80)
Location: drivers/tty/tty_io.c:3127
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff815d7b80-ffffffff815d7ba0: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81610900)
Location: drivers/tty/tty_io.c:3148
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff81610900-ffffffff81610925: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162d820)
Location: drivers/tty/tty_io.c:3303
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff8162d820-ffffffff8162d845: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81661480)
Location: drivers/tty/tty_io.c:3307
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff81661480-ffffffff816614a4: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81683ad0)
Location: drivers/tty/tty_io.c:3303
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff81683ad0-ffffffff81683af4: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817352c0)
Location: drivers/tty/tty_io.c:3306
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_init
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff817352c0-ffffffff817352fb: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81751430)
Location: drivers/tty/tty_io.c:3399
Inline: True
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_init
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_remove
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe
```
**Symbols:**

```
ffffffff81751430-ffffffff8175146b: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817351e0)
Location: drivers/tty/tty_io.c:3448
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_remove
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe
```
**Symbols:**

```
ffffffff817351e0-ffffffff8173521b: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084fb78)
Location: drivers/tty/tty_io.c:3303
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffff80001084fb78-ffff80001084fba4: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095bc1c)
Location: drivers/tty/tty_io.c:3303
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
c095bc1c-c095bc38: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008efc00)
Location: drivers/tty/tty_io.c:3303
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
c0000000008efc00-c0000000008efc14: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052de9c)
Location: drivers/tty/tty_io.c:3303
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffe00052de9c-ffffffe00052dee0: put_tty_driver (STB_GLOBAL)
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
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81649550)
Location: drivers/tty/tty_io.c:3303
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
```
**Symbols:**

```
ffffffff81649550-ffffffff81649574: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816299b0)
Location: drivers/tty/tty_io.c:3303
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff816299b0-ffffffff816299d4: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81677910)
Location: drivers/tty/tty_io.c:3303
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff81677910-ffffffff81677934: put_tty_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_tty_driver(struct tty_driver *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81692e60)
Location: drivers/tty/tty_io.c:3303
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_driver
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_driver
```
**Symbols:**

```
ffffffff81692e60-ffffffff81692e84: put_tty_driver (STB_GLOBAL)
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
