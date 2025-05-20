# Function: <code>kstrtou8</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81402030)
Location: lib/kstrtox.c:294
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff81402030-ffffffff81402093: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81449b20)
Location: lib/kstrtox.c:294
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff81449b20-ffffffff81449b84: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814684e0)
Location: lib/kstrtox.c:290
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff814684e0-ffffffff81468544: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8146dbe0)
Location: lib/kstrtox.c:292
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff8146dbe0-ffffffff8146dc45: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81499f10)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff81499f10-ffffffff81499f75: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814cf1c0)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff814cf1c0-ffffffff814cf225: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814e3ad0)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff814e3ad0-ffffffff814e3b35: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8150feb0)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff8150feb0-ffffffff8150ff15: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152ddb0)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff8152ddb0-ffffffff8152de15: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81591d2b)
Location: lib/kstrtox.c:293
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtou8_from_user
Direct callers:
  - kernel/params.c:param_set_byte
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff81591ba0-ffffffff81591c04: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815ae86b)
Location: lib/kstrtox.c:289
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtou8_from_user
Direct callers:
  - kernel/params.c:param_set_byte
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff815ae6e0-ffffffff815ae744: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b92ab)
Location: lib/kstrtox.c:296
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtou8_from_user
Direct callers:
  - kernel/params.c:param_set_byte
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff815b9170-ffffffff815b91d4: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8161fb41)
Location: lib/kstrtox.c:297
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtou8_from_user
Direct callers:
  - kernel/params.c:param_set_byte
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff8161fa00-ffffffff8161fa64: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816edfa0)
Location: lib/kstrtox.c:307
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff816edfa0-ffffffff816ee00b: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff817dea70)
Location: lib/kstrtox.c:307
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff817dea70-ffffffff817deadb: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8181e250)
Location: lib/kstrtox.c:307
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_store
```
**Symbols:**

```
ffffffff8181e250-ffffffff8181e2bb: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff818640c0)
Location: lib/kstrtox.c:307
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
  - drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_store
```
**Symbols:**

```
ffffffff818640c0-ffffffff8186412b: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffff80001063a1e8)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffff80001063a1e8-ffff80001063a264: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c07dfd3c)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
c07dfd3c-c07dfdc4: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c0000000007e0f20)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
c0000000007e0f20-c0000000007e0fc0: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffe0004669b8)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffe0004669b8-ffffffe000466a08: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81526390)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff81526390-ffffffff815263f5: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81516670)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff81516670-ffffffff815166d5: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81522420)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff81522420-ffffffff81522485: kstrtou8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kstrtou8(const char *s, unsigned int base, u8 *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8153bda0)
Location: lib/kstrtox.c:293
Inline: False
Direct callers:
  - kernel/params.c:param_set_byte
  - lib/kstrtox.c:kstrtou8_from_user
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_interrupt_pin_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_cache_line_size_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_baseclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_subclass_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_progif_code_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_revid_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_msi_interrupts_store
  - drivers/acpi/sysfs.c:acpi_gpe_set_masked_gpes
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/mfd/ab3100-core.c:ab3100_get_set_reg
  - drivers/usb/core/sysfs.c:usb2_lpm_besl_store
```
**Symbols:**

```
ffffffff8153bda0-ffffffff8153be05: kstrtou8 (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
