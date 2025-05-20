# Function: <code>__tty_insert_flip_string_flags</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t __tty_insert_flip_string_flags(struct tty_port *port, const u8 *chars, const u8 *flags, bool mutable_flags, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_buffer.c (0)
Location: drivers/tty/tty_buffer.c:299
Inline: False
Direct callers:
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_and_push_buffer
  - drivers/tty/vt/keyboard.c:fn_send_intr
  - drivers/tty/vt/keyboard.c:puts_queue
  - drivers/tty/vt/keyboard.c:put_queue
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:mouse_report
  - drivers/tty/hvc/hvc_console.c:__hvc_poll
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/serial_core.c:uart_insert_char
  - drivers/tty/serial/8250/8250_dma.c:__dma_rx_complete
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_receiver
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
```
**Symbols:**

```
ffffffff821f3d20-ffffffff821f3d43: __tty_insert_flip_string_flags.cold (STB_LOCAL)
ffffffff81af1a40-ffffffff81af1b70: __tty_insert_flip_string_flags (STB_GLOBAL)
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
</ul>
