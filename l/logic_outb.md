# Function: <code>logic_outb</code>

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
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void logic_outb(u8 value, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/logic_pio.c (ffff80001063e2f8)
Location: lib/logic_pio.c:297
Inline: True
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:io_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_out
  - drivers/tty/serial/8250/8250_port.c:hub6_serial_in
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:probe_setup_port
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_rs485_config
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_exit_key
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_enter_key
  - drivers/tty/serial/8250/8250_fintek.c:sio_write_mask_reg
  - drivers/tty/serial/8250/8250_fintek.c:sio_write_mask_reg
  - drivers/tty/serial/8250/8250_fintek.c:sio_write_mask_reg
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/char/mem.c:write_port
  - drivers/ata/libata-sff.c:ata_pci_bmdma_clear_simplex
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/uhci-hcd.c:configure_hc
```
**Symbols:**

```
ffff80001063e2f8-ffff80001063e300: logic_outb.part.0 (STB_LOCAL)
ffff80001063e300-ffff80001063e394: logic_outb (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
