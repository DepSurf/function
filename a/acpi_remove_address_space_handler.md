# Function: <code>acpi_remove_address_space_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81493c72)
Location: drivers/acpi/acpica/evxfregn.c:172
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
```
**Symbols:**

```
ffffffff81493c72-ffffffff81493d52: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff814e2a69)
Location: drivers/acpi/acpica/evxfregn.c:140
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
```
**Symbols:**

```
ffffffff814e2a69-ffffffff814e2b4a: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81505422)
Location: drivers/acpi/acpica/evxfregn.c:140
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
```
**Symbols:**

```
ffffffff81505422-ffffffff81505503: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815159f4)
Location: drivers/acpi/acpica/evxfregn.c:140
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff815159f4-ffffffff81515ad5: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff8156048d)
Location: drivers/acpi/acpica/evxfregn.c:140
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff8156048d-ffffffff815606c5: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81597144)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff81597144-ffffffff8159737c: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815af848)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff815af848-ffffffff815afa80: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815e10d7)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff815e10d7-ffffffff815e1317: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff8160246c)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff8160246c-ffffffff816026ac: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff816ae700)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_regions
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff816ae700-ffffffff816ae941: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff816cc03f)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_regions
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff816cc03f-ffffffff816cc28e: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff816ae00b)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff816ae00b-ffffffff816ae25a: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81724dca)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff81724dca-ffffffff81725019: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81855430)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff81855430-ffffffff81855685: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff819901d0)
Location: drivers/acpi/acpica/evxfregn.c:136
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff819901d0-ffffffff81990478: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff819d6c70)
Location: drivers/acpi/acpica/evxfregn.c:136
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_detach_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff819d6c70-ffffffff819d6f18: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff81a21930)
Location: drivers/acpi/acpica/evxfregn.c:136
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_detach_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/intel_pmic_xpower.c:intel_xpower_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff81a21930-ffffffff81a21bd8: acpi_remove_address_space_handler (STB_GLOBAL)
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
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffff80001078342c)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffff80001078342c-ffff800010783530: acpi_remove_address_space_handler (STB_GLOBAL)
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
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815e989e)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
```
**Symbols:**

```
ffffffff815e989e-ffffffff815e9983: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815d4ec1)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
```
**Symbols:**

```
ffffffff815d4ec1-ffffffff815d4fa6: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff815f674c)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff815f674c-ffffffff815f698c: acpi_remove_address_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_remove_address_space_handler(acpi_handle device, acpi_adr_space_type space_id, acpi_adr_space_handler handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfregn.c (ffffffff816105fc)
Location: drivers/acpi/acpica/evxfregn.c:106
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_remove
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_remove
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/acpi_cmos_rtc.c:acpi_remove_cmos_rtc_space_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_remove_space_handler
```
**Symbols:**

```
ffffffff816105fc-ffffffff8161083c: acpi_remove_address_space_handler (STB_GLOBAL)
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
