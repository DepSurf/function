# Function: <code>console_list_lock</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void console_list_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff83eaa6f5)
Location: kernel/printk/printk.c:249
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
Direct callers:
  - fs/proc/consoles.c:c_start
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:uart_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
```
**Symbols:**

```
ffffffff8118d3c0-ffffffff8118d3dd: console_list_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void console_list_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff836cf6b5)
Location: kernel/printk/printk.c:251
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
Direct callers:
  - fs/proc/consoles.c:c_start
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
```
**Symbols:**

```
ffffffff8119eb90-ffffffff8119ebad: console_list_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void console_list_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff83900ac5)
Location: kernel/printk/printk.c:245
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_late_init
  - kernel/printk/printk.c:unregister_console
  - kernel/printk/printk.c:register_console
  - kernel/printk/printk.c:console_start
  - kernel/printk/printk.c:console_stop
  - kernel/printk/printk.c:resume_console
  - kernel/printk/printk.c:suspend_console
Direct callers:
  - fs/proc/consoles.c:c_start
  - drivers/tty/tty_io.c:show_cons_active
  - drivers/tty/hvc/hvc_console.c:hvc_alloc
  - drivers/tty/hvc/hvc_console.c:hvc_instantiate
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:serial_core_add_one_port
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/tty/serial/serial_core.c:console_show
  - drivers/tty/serial/serial_core.c:uart_poll_init
  - drivers/tty/serial/earlycon.c:setup_earlycon
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/kgdboc.c:kgdboc_earlycon_init
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - drivers/firmware/efi/earlycon.c:efi_earlycon_unmap_fb
  - drivers/firmware/efi/earlycon.c:efi_earlycon_remap_fb
```
**Symbols:**

```
ffffffff811add50-ffffffff811add6d: console_list_lock (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
