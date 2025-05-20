# Function: <code>console_is_registered</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6fec9)
Location: include/linux/console.h:249
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a788cc)
Location: include/linux/console.h:249
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
```
```
In drivers/tty/serial/earlycon.c (ffffffff83eedcbb)
Location: include/linux/console.h:249
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83eee3b3)
Location: include/linux/console.h:249
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81c9deb7)
Location: include/linux/console.h:249
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
```
In drivers/firmware/efi/earlycon.c (ffffffff83f0a9ab)
Location: include/linux/console.h:249
Inline: True
Inline callers:
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba678)
Location: include/linux/console.h:296
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac3378)
Location: include/linux/console.h:296
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
```
```
In drivers/tty/serial/earlycon.c (ffffffff837139ab)
Location: include/linux/console.h:296
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83713ff3)
Location: include/linux/console.h:296
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81d05227)
Location: include/linux/console.h:296
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
```
In drivers/firmware/efi/earlycon.c (ffffffff83730acb)
Location: include/linux/console.h:296
Inline: True
Inline callers:
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0d3c3)
Location: include/linux/console.h:425
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b16228)
Location: include/linux/console.h:425
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
```
```
In drivers/tty/serial/earlycon.c (ffffffff8394740b)
Location: include/linux/console.h:425
Inline: True
Inline callers:
  - drivers/tty/serial/earlycon.c:setup_earlycon
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83947a53)
Location: include/linux/console.h:425
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81dbade7)
Location: include/linux/console.h:425
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
```
```
In drivers/firmware/efi/earlycon.c (ffffffff8396502b)
Location: include/linux/console.h:425
Inline: True
Inline callers:
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
