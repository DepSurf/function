# Function: <code>assign_bit</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8151447a)
Location: include/linux/bitops.h:237
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff815188c2)
Location: include/linux/bitops.h:237
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff81529bda)
Location: include/linux/bitops.h:218
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8152e32f)
Location: include/linux/bitops.h:218
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff81558df2)
Location: include/linux/bitops.h:218
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8155dad0)
Location: include/linux/bitops.h:218
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8157a392)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8157eb40)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/gpio/gpiolib.c (ffffffff8160fb13)
Location: include/linux/bitops.h:240
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:linehandle_set_config
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/pci/bus.c (ffffffff8161f4ae)
Location: include/linux/bitops.h:240
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff816241d0)
Location: include/linux/bitops.h:240
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/gpio/gpiolib.c (ffffffff81637010)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a925)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
```
```
In drivers/pci/bus.c (ffffffff81645c9e)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff81649d90)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/tty/tty_io.c (ffffffff81753fe0)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/tty_port.c (ffffffff8175c117)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/vt/keyboard.c (ffffffff81764979)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8176f9cb)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff817766a6)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_do_autoconfig
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/gpio/gpiolib.c (ffffffff8161a930)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161e4b5)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
```
```
In drivers/pci/bus.c (ffffffff816289de)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8162c949)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/tty/tty_io.c (ffffffff81737e92)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/tty_port.c (ffffffff8173ffb7)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/vt/keyboard.c (ffffffff817485c3)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817534ab)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175a286)
Location: include/linux/bitops.h:238
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In drivers/gpio/gpiolib.c (ffffffff81689d70)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168da75)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8168fd31)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pci/bus.c (ffffffff8169835e)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8169be10)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/tty/tty_io.c (ffffffff817b8932)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/tty_port.c (ffffffff817c0757)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/vt/keyboard.c (ffffffff817c981b)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d689b)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dd7d5)
Location: include/linux/bitops.h:239
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In kernel/irq/irq_sim.c (ffffffff8116c55b)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
```
```
In drivers/gpio/gpiolib.c (ffffffff817a5413)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aa315)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff817af4d8)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pci/bus.c (ffffffff817b963e)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff817bd72a)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/tty/tty_io.c (ffffffff818f493e)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/tty_port.c (ffffffff818fcf79)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/vt/keyboard.c (ffffffff81906d97)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8191495f)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191c1ca)
Location: include/linux/bitops.h:205
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In kernel/irq/irq_sim.c (ffffffff811a152b)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
```
```
In drivers/gpio/gpiolib.c (ffffffff818bd683)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c2ed5)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c8b58)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pci/bus.c (ffffffff818d423a)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff818d985a)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/tty/tty_io.c (ffffffff81a4d908)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/tty_port.c (ffffffff81a56659)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a61407)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a6fa2f)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a78136)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In kernel/irq/irq_sim.c (ffffffff811b333b)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
```
```
In drivers/gpio/gpiolib.c (ffffffff819007b3)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81905da5)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190bc18)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pci/bus.c (ffffffff81917494)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8191cbaa)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/tty/tty_io.c (ffffffff81a97bd8)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/tty_port.c (ffffffff81aa0c39)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aabac7)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81aba1df)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac2be6)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
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
In kernel/irq/irq_sim.c (ffffffff811c318b)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_sim_set_irqchip_state
```
```
In drivers/gpio/gpiolib.c (ffffffff8194a024)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiod_get_direction
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194d7b5)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
  - drivers/gpio/gpiolib-cdev.c:linehandle_flags_to_desc_flags
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81953938)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:active_low_store
```
```
In drivers/pci/bus.c (ffffffff8195f5a4)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff81964fda)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
```
In drivers/tty/tty_io.c (ffffffff81aea615)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kclose
```
```
In drivers/tty/tty_port.c (ffffffff81af3699)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_open
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/tty_port.c:tty_port_block_til_ready
  - drivers/tty/tty_port.c:tty_port_hangup
  - drivers/tty/tty_port.c:tty_port_shutdown
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afe667)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_keycode
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0cf0f)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:hvc_close
  - drivers/tty/hvc/hvc_console.c:hvc_open
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b14bba)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/tty/serial/serial_core.c:uart_port_activate
  - drivers/tty/serial/serial_core.c:uart_hangup
  - drivers/tty/serial/serial_core.c:uart_tty_port_shutdown
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
```
In net/core/sock.c (ffffffff81ec9c10)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
```
```
In net/core/dev.c (ffffffff81eeb804)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_threaded
```
```
In net/netlink/af_netlink.c (ffffffff81f889e8)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_setsockopt
  - net/netlink/af_netlink.c:netlink_setsockopt
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc2f56)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
```
In net/ipv4/udp.c (ffffffff82008038)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
```
```
In net/ipv4/af_inet.c (ffffffff82019adc)
Location: include/linux/bitops.h:275
Inline: True
```
```
In net/ipv6/af_inet6.c (ffffffff8207f5b9)
Location: include/linux/bitops.h:275
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820ae0ce)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/raw.c (ffffffff820bba3f)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_setsockopt
```
```
In net/mptcp/protocol.c (ffffffff82146fcd)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_connect
```
```
In net/mptcp/sockopt.c (ffffffff8215d9c7)
Location: include/linux/bitops.h:275
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_ip_set
  - net/mptcp/sockopt.c:mptcp_setsockopt_v6
  - net/mptcp/sockopt.c:mptcp_setsockopt_v6
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
In drivers/pci/bus.c (ffff8000106dcc9c)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffff8000106e1640)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (c087889c)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (c087d104)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (c000000000854dc8)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (c00000000085a7a8)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffe0004b5126)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffe0004b909c)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8156e8a2)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff81573060)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8155d012)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff815617c0)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff8156e0e2)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff81572890)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
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
In drivers/pci/bus.c (ffffffff815885c2)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_device
```
```
In drivers/pci/remove.c (ffffffff8158cd70)
Location: include/linux/bitops.h:225
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_bus_device
```
</details>
</li>
</ul>

## Differences
