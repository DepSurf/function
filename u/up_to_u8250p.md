# Function: <code>up_to_u8250p</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/serial_8250.h:127
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/serial_8250.h:127
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/serial_8250.h:127
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/serial_8250.h:136
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/serial_8250.h:136
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/serial_8250.h:136
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/serial_8250.h:138
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/serial_8250.h:138
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/serial_8250.h:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/serial_8250.h:138
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/serial_8250.h:138
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/serial_8250.h:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/serial_8250.h:139
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/serial_8250.h:139
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/serial_8250.h:139
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff827268da)
Location: include/linux/serial_8250.h:139
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81636fe5)
Location: include/linux/serial_8250.h:139
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163ba55)
Location: include/linux/serial_8250.h:139
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff828deabe)
Location: include/linux/serial_8250.h:143
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816554f5)
Location: include/linux/serial_8250.h:143
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81659c85)
Location: include/linux/serial_8250.h:143
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff828f93e6)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816896a5)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8168f0f5)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff829022e9)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816abdc5)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff816b0ec5)
Location: include/linux/serial_8250.h:140
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b1975)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff82d1951c)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e9e5)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_defaults
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:do_set_rxtrig
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_show
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff817642a5)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81764ef5)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff830071e5)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81779878)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_defaults
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:do_set_rxtrig
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_show
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff8177f1c5)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8177fdf5)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff83211dcf)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175d1a8)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_defaults
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_show
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81762b25)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81763725)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff832faf78)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e1038)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_defaults
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_show
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff817e6c35)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e7b05)
Location: include/linux/serial_8250.h:144
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/serial_8250.h:142
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/serial_8250.h:142
Inline: True
```
```
In drivers/tty/serial/8250/8250_dwlib.c (0)
Location: include/linux/serial_8250.h:142
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/serial_8250.h:142
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/serial_8250.h:144
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/serial_8250.h:144
Inline: True
```
```
In drivers/tty/serial/8250/8250_dwlib.c (0)
Location: include/linux/serial_8250.h:144
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/serial_8250.h:144
Inline: True
```
```
In drivers/tty/serial/8250/8250_mid.c (0)
Location: include/linux/serial_8250.h:144
Inline: True
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
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_dwlib.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_rt288x.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_mid.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
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
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_dwlib.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_mid.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
```
In drivers/tty/serial/8250/8250_rt288x.c (0)
Location: include/linux/serial_8250.h:172
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffff800011494714)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010886a14)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffff80001088c3e0)
Location: include/linux/serial_8250.h:140
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088d7ac)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
```
In drivers/tty/serial/8250/8250_fsl.c (ffff800010890874)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010890fc4)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_set_ldisc
  - drivers/tty/serial/8250/8250_dw.c:dw8250_handle_irq
  - drivers/tty/serial/8250/8250_dw.c:dw8250_check_lcr
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892560)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_shutdown
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (c1594fc8)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (c0985030)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_dwlib.c (c0989cfc)
Location: include/linux/serial_8250.h:140
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (c0989f9c)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
```
In drivers/tty/serial/8250/8250_fsl.c (c098cf7c)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098d794)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_shutdown
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (c0000000013a7d7c)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092d950)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_dwlib.c (c00000000093503c)
Location: include/linux/serial_8250.h:140
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (c0000000009384ac)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
```
In drivers/tty/serial/8250/8250_fsl.c (c00000000093a938)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffe00002f43a)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551ad0)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffe000555b2e)
Location: include/linux/serial_8250.h:140
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000556ae4)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff828e9ad0)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671835)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81676935)
Location: include/linux/serial_8250.h:140
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816773e5)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff828e0f7f)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650935)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff81655a15)
Location: include/linux/serial_8250.h:140
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816564c5)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff828fd60c)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169fc05)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff816a4d05)
Location: include/linux/serial_8250.h:140
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a57b5)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8290334b)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:early_serial_setup
  - drivers/tty/serial/8250/8250_core.c:univ8250_release_port
  - drivers/tty/serial/8250/8250_core.c:univ8250_config_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ba0c5)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_request_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_release_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_pm
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_divisor
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_threshold_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_rx
  - drivers/tty/serial/8250/8250_port.c:set_io_from_upio
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffff816bf165)
Location: include/linux/serial_8250.h:140
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816bfc15)
Location: include/linux/serial_8250.h:140
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:kt_serial_in
  - drivers/tty/serial/8250/8250_pci.c:kt_handle_break
```
</details>
</li>
</ul>

## Differences
