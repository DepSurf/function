# Function: <code>i2c_smbus_write_byte_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167a980)
Location: drivers/i2c/i2c-core.c:2689
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_i2c_write
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:__adp5520_write
```
**Symbols:**

```
ffffffff8167a980-ffffffff8167a9db: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816de813)
Location: drivers/i2c/i2c-core.c:2894
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_i2c_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
```
**Symbols:**

```
ffffffff816dc0e0-ffffffff816dc13b: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170ebd3)
Location: drivers/i2c/i2c-core.c:3182
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
```
**Symbols:**

```
ffffffff8170c420-ffffffff8170c47b: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81723290)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81723290-ffffffff817232e8: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817946b0)
Location: drivers/i2c/i2c-core-smbus.c:150
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817946b0-ffffffff81794708: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d7210)
Location: drivers/i2c/i2c-core-smbus.c:151
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817d7210-ffffffff817d7268: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fe370)
Location: drivers/i2c/i2c-core-smbus.c:151
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817fe370-ffffffff817fe3c8: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f5a0)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8183f5a0-ffffffff8183f5f9: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870f40)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81870f40-ffffffff81870f99: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81944f80)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_restore
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_resume
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81944f80-ffffffff81944fd9: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194afc0)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_restore
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_resume
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8194afc0-ffffffff8194b019: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192eb00)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_restore
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_resume
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8192eb00-ffffffff8192eb59: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d1d30)
Location: drivers/i2c/i2c-core-smbus.c:157
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_restore
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_resume
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff819d1d30-ffffffff819d1d89: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b34390)
Location: drivers/i2c/i2c-core-smbus.c:158
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_restore
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_resume
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81b34390-ffffffff81b34421: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc93d0)
Location: drivers/i2c/i2c-core-smbus.c:158
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_restore
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_resume
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81cc93d0-ffffffff81cc9461: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d310f0)
Location: drivers/i2c/i2c-core-smbus.c:158
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_restore
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_resume
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81d310f0-ffffffff81d31181: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de70d0)
Location: drivers/i2c/i2c-core-smbus.c:158
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_i2c_smbus_i2c_read_reg16
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_restore
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_restore
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_resume
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81de70d0-ffffffff81de7161: i2c_smbus_write_byte_data (STB_GLOBAL)
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
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4b88)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/stmpe-i2c.c:i2c_reg_write
  - drivers/mfd/tc3589x.c:tc3589x_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffff800010ab4b88-ffff800010ab4c00: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b95db8)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/stmpe-i2c.c:i2c_reg_write
  - drivers/mfd/tc3589x.c:tc3589x_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
```
**Symbols:**

```
c0b95db8-c0b95e38: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b98db0)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/stmpe-i2c.c:i2c_reg_write
  - drivers/mfd/tc3589x.c:tc3589x_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
```
**Symbols:**

```
c000000000b98db0-c000000000b98e2c: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bbfba)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/stmpe-i2c.c:i2c_reg_write
  - drivers/mfd/tc3589x.c:tc3589x_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
```
**Symbols:**

```
ffffffe0006bbfba-ffffffe0006bc006: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff818650d0)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff818650d0-ffffffff81865129: i2c_smbus_write_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s32 i2c_smbus_write_byte_data(const struct i2c_client *client, u8 command, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81880380)
Location: drivers/i2c/i2c-core-smbus.c:149
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_write
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_write
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_write
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_write_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_write_reg
  - drivers/mfd/adp5520.c:__adp5520_write
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_write
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81880380-ffffffff818803d9: i2c_smbus_write_byte_data (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
