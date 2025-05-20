# Function: <code>tty_driver_kref_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0a35)
Location: drivers/tty/tty_io.c:3458
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff814e0a50-ffffffff814e0a60: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81532145)
Location: drivers/tty/tty_io.c:3454
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81532160-ffffffff81532170: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155e875)
Location: drivers/tty/tty_io.c:3454
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff8155e890-ffffffff8155e8a0: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572f70)
Location: drivers/tty/tty_io.c:3007
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81572f70-ffffffff81573034: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d7b89)
Location: drivers/tty/tty_io.c:3114
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff815d7ba0-ffffffff815d7bb0: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81610905)
Location: drivers/tty/tty_io.c:3135
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81610930-ffffffff81610940: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162d825)
Location: drivers/tty/tty_io.c:3290
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff8162d850-ffffffff8162d860: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81661485)
Location: drivers/tty/tty_io.c:3294
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81661450-ffffffff81661474: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81683ad5)
Location: drivers/tty/tty_io.c:3290
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81683aa0-ffffffff81683ac4: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817352c5)
Location: drivers/tty/tty_io.c:3293
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81735280-ffffffff817352bb: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81754240)
Location: drivers/tty/tty_io.c:3386
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81751470-ffffffff817514ab: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817351e5)
Location: drivers/tty/tty_io.c:3435
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff817351a0-ffffffff817351db: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b8d16)
Location: drivers/tty/tty_io.c:3435
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
Direct callers:
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
ffffffff817b5ba0-ffffffff817b5bdb: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f4e4d)
Location: drivers/tty/tty_io.c:3408
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:release_one_tty
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
**Symbols:**

```
ffffffff818f1460-ffffffff818f14bf: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4d46c)
Location: drivers/tty/tty_io.c:3405
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:release_one_tty
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
**Symbols:**

```
ffffffff81a494b0-ffffffff81a494fe: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a97762)
Location: drivers/tty/tty_io.c:3411
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:release_one_tty
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
**Symbols:**

```
ffffffff81a936e0-ffffffff81a9372e: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81aea1a0)
Location: drivers/tty/tty_io.c:3428
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:release_one_tty
Direct callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/serial/serial_core.c:uart_unregister_driver
  - drivers/tty/serial/serial_core.c:uart_register_driver
  - drivers/tty/serial/kgdb_nmi.c:kgdb_unregister_nmi_console
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/char/ttyprintk.c:ttyprintk_exit
  - drivers/char/ttyprintk.c:ttyprintk_init
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_init
```
**Symbols:**

```
ffffffff81ae6150-ffffffff81ae619e: tty_driver_kref_put (STB_GLOBAL)
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
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084f940)
Location: drivers/tty/tty_io.c:3290
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffff80001084f940-ffff80001084fa28: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095b96c)
Location: drivers/tty/tty_io.c:3290
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
c095b96c-c095ba54: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008efa80)
Location: drivers/tty/tty_io.c:3290
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
c0000000008efa80-c0000000008efbf8: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052deb2)
Location: drivers/tty/tty_io.c:3290
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffe00052dee0-ffffffe00052df08: tty_driver_kref_put (STB_GLOBAL)
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
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81649555)
Location: drivers/tty/tty_io.c:3290
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81649520-ffffffff81649544: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816299b5)
Location: drivers/tty/tty_io.c:3290
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81629980-ffffffff816299a4: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81677915)
Location: drivers/tty/tty_io.c:3290
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff816778e0-ffffffff81677904: tty_driver_kref_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tty_driver_kref_put(struct tty_driver *driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81692e65)
Location: drivers/tty/tty_io.c:3290
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81692e30-ffffffff81692e54: tty_driver_kref_put (STB_GLOBAL)
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
