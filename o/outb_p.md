# Function: <code>outb_p</code>

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
In drivers/video/console/vgacon.c (ffffffff8145d6e4)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
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
In drivers/video/fbdev/vesafb.c (ffffffff814779bf)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815074d0)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8163000c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff816d53a5)
Location: arch/x86/include/asm/io.h:316
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
In drivers/video/console/vgacon.c (ffffffff814ac233)
Location: arch/x86/include/asm/io.h:316
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814c5efc)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81558cd1)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81690c6c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81739659)
Location: arch/x86/include/asm/io.h:316
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
In drivers/video/console/vgacon.c (ffffffff814ce663)
Location: arch/x86/include/asm/io.h:316
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814e7f53)
Location: arch/x86/include/asm/io.h:316
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815854df)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bed1c)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff8176c889)
Location: arch/x86/include/asm/io.h:316
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
In drivers/video/console/vgacon.c (ffffffff814d94b8)
Location: arch/x86/include/asm/io.h:340
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814f3b1d)
Location: arch/x86/include/asm/io.h:340
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159ace6)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816d35da)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff8178ac09)
Location: arch/x86/include/asm/io.h:340
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
In drivers/video/console/vgacon.c (ffffffff815196e8)
Location: arch/x86/include/asm/io.h:348
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815341dd)
Location: arch/x86/include/asm/io.h:348
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815ffecb)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8173fc9a)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81801259)
Location: arch/x86/include/asm/io.h:348
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
In drivers/video/console/vgacon.c (ffffffff8155037e)
Location: arch/x86/include/asm/io.h:333
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81569c7e)
Location: arch/x86/include/asm/io.h:333
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816390d3)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8178064a)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff8184ae79)
Location: arch/x86/include/asm/io.h:333
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
In drivers/video/console/vgacon.c (ffffffff815676ce)
Location: arch/x86/include/asm/io.h:342
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815816de)
Location: arch/x86/include/asm/io.h:342
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816573e5)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817a6e6a)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81877d69)
Location: arch/x86/include/asm/io.h:342
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
In drivers/video/console/vgacon.c (ffffffff81597ef1)
Location: arch/x86/include/asm/io.h:339
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815b1d82)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168d4db)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817e607a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff818bc5e9)
Location: arch/x86/include/asm/io.h:339
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
In drivers/video/console/vgacon.c (ffffffff815b9291)
Location: arch/x86/include/asm/io.h:339
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815d2d02)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816afa2b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81816f3a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff818ef0b9)
Location: arch/x86/include/asm/io.h:339
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
In drivers/video/console/vgacon.c (ffffffff81663a4a)
Location: arch/x86/include/asm/io.h:334
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167c8a2)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761c16)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818e7fb8)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff819c2c99)
Location: arch/x86/include/asm/io.h:334
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
In drivers/video/console/vgacon.c (ffffffff816846da)
Location: arch/x86/include/asm/io.h:334
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8169c632)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177d04b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f0f98)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff819c30b9)
Location: arch/x86/include/asm/io.h:334
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
In drivers/video/console/vgacon.c (ffffffff8166766a)
Location: arch/x86/include/asm/io.h:334
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167f43a)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8176047b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d4798)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff819a74f9)
Location: arch/x86/include/asm/io.h:334
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
In drivers/video/console/vgacon.c (ffffffff816da8aa)
Location: arch/x86/include/asm/io.h:334
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff816f43f9)
Location: arch/x86/include/asm/io.h:334
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e43eb)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8196f068)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81a549f9)
Location: arch/x86/include/asm/io.h:334
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
In drivers/video/console/vgacon.c (ffffffff8180353c)
Location: arch/x86/include/asm/io.h:305
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81821089)
Location: arch/x86/include/asm/io.h:305
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81923363)
Location: arch/x86/include/asm/io.h:305
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81acab7b)
Location: arch/x86/include/asm/io.h:305
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81bc3f39)
Location: arch/x86/include/asm/io.h:305
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
In drivers/video/console/vgacon.c (ffffffff81931cfc)
Location: arch/x86/include/asm/io.h:296
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81951129)
Location: arch/x86/include/asm/io.h:296
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7fc7f)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c551bb)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81d695d9)
Location: arch/x86/include/asm/io.h:296
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
In drivers/video/console/vgacon.c (ffffffff8197616c)
Location: arch/x86/include/asm/io.h:296
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff819975f1)
Location: arch/x86/include/asm/io.h:296
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acb198)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbc73b)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81dd4ac9)
Location: arch/x86/include/asm/io.h:296
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
In drivers/video/console/vgacon.c (ffffffff819c01dc)
Location: arch/x86/include/asm/io.h:291
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
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1fa68)
Location: arch/x86/include/asm/io.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d714ab)
Location: arch/x86/include/asm/io.h:291
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81e8cc19)
Location: arch/x86/include/asm/io.h:291
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff80001088b114)
Location: include/asm-generic/io.h:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a50a74)
Location: include/asm-generic/io.h:554
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/tty/serial/8250/8250_port.c (c0988cd8)
Location: include/asm-generic/io.h:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (c0b222e4)
Location: include/asm-generic/io.h:554
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/rtc/rtc-mc146818-lib.c (c0b8a9f8)
Location: include/asm-generic/io.h:554
Inline: True
Inline callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffe0004f0d40)
Location: include/asm-generic/io.h:554
Inline: True
Inline callers:
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
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000554d1e)
Location: include/asm-generic/io.h:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffe00066c8ce)
Location: include/asm-generic/io.h:554
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff815ad3e1)
Location: arch/x86/include/asm/io.h:339
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c6d12)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8167549b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817cf31a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81890489)
Location: arch/x86/include/asm/io.h:339
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
In drivers/video/console/vgacon.c (ffffffff8159c581)
Location: arch/x86/include/asm/io.h:339
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
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8165457b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817ad24a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81849749)
Location: arch/x86/include/asm/io.h:339
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
In drivers/video/console/vgacon.c (ffffffff815ad971)
Location: arch/x86/include/asm/io.h:339
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c72a2)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a386b)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8180bdba)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff818e3ee9)
Location: arch/x86/include/asm/io.h:339
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
In drivers/video/console/vgacon.c (ffffffff815c7421)
Location: arch/x86/include/asm/io.h:339
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
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815e0e42)
Location: arch/x86/include/asm/io.h:339
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816bdcfb)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81825eca)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/clocksource/i8253.c (ffffffff81900b39)
Location: arch/x86/include/asm/io.h:339
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
