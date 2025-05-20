# Function: <code>pnp_get_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff814b84b0)
Location: drivers/pnp/resource.c:481
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff814b84b0-ffffffff814b8500: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81508ac3)
Location: drivers/pnp/resource.c:481
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81507f10-ffffffff81507f60: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8152cce3)
Location: drivers/pnp/resource.c:481
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8152c130-ffffffff8152c180: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8153fdaf)
Location: drivers/pnp/resource.c:481
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8153f220-ffffffff8153f270: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815a2ecf)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff815a22d0-ffffffff815a2320: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815dab63)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff815d9f40-ffffffff815d9f90: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815f4433)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff815f3860-ffffffff815f38b0: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8162625c)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81625720-ffffffff81625770: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81647d4c)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81647210-ffffffff81647260: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff816f6b3c)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_dma
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/pnp/manager.c:pnp_assign_mem
  - drivers/pnp/manager.c:pnp_assign_port
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:reserve_resources_of_dev
  - drivers/pnp/system.c:reserve_resources_of_dev
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff816f5fa0-ffffffff816f5ff2: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81713b7c)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_dma
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/pnp/manager.c:pnp_assign_mem
  - drivers/pnp/manager.c:pnp_assign_port
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:reserve_resources_of_dev
  - drivers/pnp/system.c:reserve_resources_of_dev
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81712fe0-ffffffff81713032: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff816f4f28)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff816f43a0-ffffffff816f43f0: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8176f46c)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8176e7e0-ffffffff8176e830: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff818a480c)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff818a3a20-ffffffff818a3a88: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff819ee31c)
Location: drivers/pnp/resource.c:483
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff819ed480-ffffffff819ed4e8: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81a36a8c)
Location: drivers/pnp/resource.c:483
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81a35c00-ffffffff81a35c68: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81a8217c)
Location: drivers/pnp/resource.c:483
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff81a81160-ffffffff81a811c8: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffff8000107b4fb0)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
```
**Symbols:**

```
ffff8000107b44e8-ffff8000107b456c: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/pnp.h:30
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/pnp.h:30
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (0)
Location: include/linux/pnp.h:30
Inline: True
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
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8160ddac)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8160d270-ffffffff8160d2c0: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff816022fc)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff816017c0-ffffffff81601810: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8163bb8c)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff8163b050-ffffffff8163b0a0: pnp_get_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct resource *pnp_get_resource(struct pnp_dev *dev, long unsigned int type, unsigned int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81655edc)
Location: drivers/pnp/resource.c:482
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_dma
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_irq
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_mem
  - drivers/pnp/resource.c:pnp_check_port
  - drivers/pnp/resource.c:pnp_check_port
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/support.c:pnp_is_active
  - drivers/pnp/quirks.c:quirk_system_pci_resources
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/system.c:system_pnp_probe
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_encode_resources
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_pnp_init
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_aux_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/input/serio/i8042.c:i8042_pnp_kbd_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
  - drivers/rtc/rtc-cmos.c:cmos_pnp_probe
```
**Symbols:**

```
ffffffff816553a0-ffffffff816553f0: pnp_get_resource (STB_GLOBAL)
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
