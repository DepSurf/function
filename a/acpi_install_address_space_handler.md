# Function: <code>acpi_install_address_space_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81493bbf)
Location: drivers/acpi/acpica/evxfregn.c:77
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81493bbf-ffffffff81493c72: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff814e29ce)
Location: drivers/acpi/acpica/evxfregn.c:77
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff814e29ce-ffffffff814e2a69: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81505387)
Location: drivers/acpi/acpica/evxfregn.c:77
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81505387-ffffffff81505422: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81515959)
Location: drivers/acpi/acpica/evxfregn.c:77
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff81515959-ffffffff815159f4: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81560371)
Location: drivers/acpi/acpica/evxfregn.c:77
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff81560371-ffffffff8156048d: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81597028)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff81597028-ffffffff81597144: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815af72c)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff815af72c-ffffffff815af848: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815e0fb8)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff815e0fb8-ffffffff815e10d7: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff8160234d)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff8160234d-ffffffff8160246c: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff816ae5e1)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff816ae5e1-ffffffff816ae700: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff816cbf20)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff816cbf20-ffffffff816cc03f: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff816adeec)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff816adeec-ffffffff816ae00b: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81724cab)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff81724cab-ffffffff81724dca: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81855301)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/acpi_pcc.c:acpi_init_pcc
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff81855301-ffffffff81855430: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81990010)
Location: drivers/acpi/acpica/evxfregn.c:97
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/acpi_pcc.c:acpi_init_pcc
  - drivers/acpi/acpi_ffh.c:acpi_init_ffh
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff81990010-ffffffff8199003c: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff819d6ab0)
Location: drivers/acpi/acpica/evxfregn.c:97
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_attach_handler
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/acpi_pcc.c:acpi_init_pcc
  - drivers/acpi/acpi_ffh.c:acpi_init_ffh
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff819d6ab0-ffffffff819d6adc: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81a21770)
Location: drivers/acpi/acpica/evxfregn.c:97
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_attach_handler
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/acpi_pcc.c:acpi_init_pcc
  - drivers/acpi/acpi_ffh.c:acpi_init_ffh
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff81a21770-ffffffff81a2179c: acpi_install_address_space_handler (STB_GLOBAL)
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
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffff80001078337c)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffff80001078337c-ffff80001078342c: acpi_install_address_space_handler (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815e97f9)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
```
**Symbols:**

```
ffffffff815e97f9-ffffffff815e989e: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815d4e1c)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
```
**Symbols:**

```
ffffffff815d4e1c-ffffffff815d4ec1: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815f662d)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff815f662d-ffffffff815f674c: acpi_install_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler, acpi_adr_space_setup setup, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff816104dd)
Location: drivers/acpi/acpica/evxfregn.c:43
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_install_cmos_rtc_space_handler
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
```
**Symbols:**

```
ffffffff816104dd-ffffffff816105fc: acpi_install_address_space_handler (STB_GLOBAL)
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
