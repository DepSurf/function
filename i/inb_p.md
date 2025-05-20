# Function: <code>inb_p</code>

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
In drivers/video/console/vgacon.c (ffffffff8145d6ce)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff814ad076)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815074f2)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8163001b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff814ab8db)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff814fc992)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81558cf3)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81690c7b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff814cd9e8)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff8151f61a)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81585501)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816bed2b)
Location: arch/x86/include/asm/io.h:316
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff814d99e8)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff81530b85)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8159ad00)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff816d35e9)
Location: arch/x86/include/asm/io.h:340
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff81519c0c)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff81591b95)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815ffeeb)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8173fca9)
Location: arch/x86/include/asm/io.h:348
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff8154f6f5)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff815c8f68)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816390c1)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8178066a)
Location: arch/x86/include/asm/io.h:333
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff81566f65)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff815e2538)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816573d3)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817a6e8a)
Location: arch/x86/include/asm/io.h:342
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff815977a1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff81614004)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8168d4c8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817e609a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff815b8b31)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff81635491)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816afa18)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81816f5a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff81663a57)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff816e12cf)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761c25)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818e7fd9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff816846e7)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff816ff02f)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
  - drivers/acpi/processor_idle.c:acpi_idle_bm_check
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177d05a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f0fb9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff81667677)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff816e18ab)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8176048a)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d47b9)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff816da8b7)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff81759d0b)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e43fa)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8196f089)
Location: arch/x86/include/asm/io.h:334
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff81803543)
Location: arch/x86/include/asm/io.h:305
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff81f29672)
Location: arch/x86/include/asm/io.h:305
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8192336d)
Location: arch/x86/include/asm/io.h:305
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81acab90)
Location: arch/x86/include/asm/io.h:305
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff81931d03)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff820d54a2)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7fc89)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c551d0)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff81976173)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff82143b9d)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acb1a2)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81cbc750)
Location: arch/x86/include/asm/io.h:296
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff819c01e3)
Location: arch/x86/include/asm/io.h:291
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_adjust_height
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_set_cursor_size
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff822262bd)
Location: arch/x86/include/asm/io.h:291
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
  - drivers/acpi/processor_idle.c:acpi_idle_enter_bm
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1fa72)
Location: arch/x86/include/asm/io.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81d714c0)
Location: arch/x86/include/asm/io.h:291
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/tty/serial/8250/8250_port.c (ffff80001088b14c)
Location: include/asm-generic/io.h:530
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffff800010a50a80)
Location: include/asm-generic/io.h:530
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
In drivers/tty/serial/8250/8250_port.c (c0988cf8)
Location: include/asm-generic/io.h:530
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (c0b222fc)
Location: include/asm-generic/io.h:530
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
```
In drivers/rtc/rtc-mc146818-lib.c (c0b8aa18)
Location: include/asm-generic/io.h:530
Inline: True
Inline callers:
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
In drivers/video/console/vgacon.c (ffffffe0004f0978)
Location: include/asm-generic/io.h:530
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_doresize
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000554d00)
Location: include/asm-generic/io.h:530
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffe00066c8e4)
Location: include/asm-generic/io.h:530
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
In drivers/video/console/vgacon.c (ffffffff815acc81)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff81604c81)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81675488)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817cf33a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff8159be21)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff815efdef)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81654568)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff817ad26a)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff815ad211)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff81629771)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a3858)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff8180bdda)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
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
In drivers/video/console/vgacon.c (ffffffff815c6cc1)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_startup
```
```
In drivers/acpi/processor_idle.c (ffffffff81643611)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_enter
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816bdce8)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81825eea)
Location: arch/x86/include/asm/io.h:339
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
  - drivers/usb/host/pci-quirks.c:usb_amd_quirk_pll
```
</details>
</li>
</ul>

## Differences
