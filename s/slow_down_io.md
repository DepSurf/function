# Function: <code>slow_down_io</code>

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
In drivers/video/console/vgacon.c (ffffffff8145d6ea)
Location: arch/x86/include/asm/paravirt.h:284
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814779c5)
Location: arch/x86/include/asm/paravirt.h:284
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814ad07d)
Location: arch/x86/include/asm/paravirt.h:284
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815074d8)
Location: arch/x86/include/asm/paravirt.h:284
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81630020)
Location: arch/x86/include/asm/paravirt.h:284
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff816d53ac)
Location: arch/x86/include/asm/paravirt.h:284
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_set_oneshot
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
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
In drivers/video/console/vgacon.c (ffffffff814ac23e)
Location: arch/x86/include/asm/paravirt.h:283
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814c5f02)
Location: arch/x86/include/asm/paravirt.h:283
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff814fc996)
Location: arch/x86/include/asm/paravirt.h:283
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81558cd9)
Location: arch/x86/include/asm/paravirt.h:283
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81690c80)
Location: arch/x86/include/asm/paravirt.h:283
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff8173965d)
Location: arch/x86/include/asm/paravirt.h:283
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff814ce66e)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814e7f59)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff8151f61e)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815854e7)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bed30)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff8176c88d)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff814d94c3)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814f3b23)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81530b89)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159acfa)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816d35ee)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff8178ac0d)
Location: arch/x86/include/asm/paravirt.h:274
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff815196f3)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815341e3)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81591b99)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815ffedf)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8173fcae)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff8180125d)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff81550389)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81569c84)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815c8f6f)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816390c7)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81780659)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff8184ae7d)
Location: arch/x86/include/asm/paravirt.h:266
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff815676d9)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815816e4)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff815e253f)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816573d9)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817a6e79)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81877d6d)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff81597efc)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815b1d8a)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81614008)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168d4cf)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817e6089)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff818bc5ed)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff815b929c)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815d2d0a)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81635495)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816afa1f)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81816f49)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff818ef0bd)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff81663a4b)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167c8aa)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816e12d6)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761c19)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818e7fc7)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff819c2c9d)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff816846db)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8169c63a)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816ff036)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177d04e)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f0fa7)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff819c30bd)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff8166766b)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167f442)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff816e18b2)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8176047e)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d47a7)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff819a74fd)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff816da8ab)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff816f4401)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81759d12)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e43ee)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8196f077)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81a549fd)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff8180353d)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81821092)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81f29679)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81923367)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81acab8a)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81bc3f3d)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff81931cfd)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81951132)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff820d54a9)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7fc83)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c551ca)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81d695dd)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff8197616d)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff819975fa)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff82143ba4)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acb19c)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbc74a)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81dd4acd)
Location: arch/x86/include/asm/paravirt.h:53
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff819c01dd)
Location: arch/x86/include/asm/paravirt.h:57
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vgacon_blank
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff822262c4)
Location: arch/x86/include/asm/paravirt.h:57
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1fa6c)
Location: arch/x86/include/asm/paravirt.h:57
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d714ba)
Location: arch/x86/include/asm/paravirt.h:57
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81e8cc1d)
Location: arch/x86/include/asm/paravirt.h:57
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815ad3ec)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c6d1a)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81604c85)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8167548f)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817cf329)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff8189048d)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff8159c58c)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff815efdf3)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8165456f)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817ad259)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff8184974d)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff815ad97c)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c72aa)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81629775)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a385f)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8180bdc9)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff818e3eed)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
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
In drivers/video/console/vgacon.c (ffffffff815c742c)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vga_set_palette
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815e0e4a)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
```
```
In drivers/acpi/processor_idle.c (ffffffff81643615)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816bdcef)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81825ed9)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81900b3d)
Location: arch/x86/include/asm/paravirt.h:40
Inline: True
Inline callers:
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_next_event
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_periodic
  - drivers/clocksource/i8253.c:pit_set_oneshot
```
</details>
</li>
</ul>

## Differences
