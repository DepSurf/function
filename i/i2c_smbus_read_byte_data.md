# Function: <code>i2c_smbus_read_byte_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167a910)
Location: drivers/i2c/i2c-core.c:2668
Inline: False
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff8167a910-ffffffff8167a973: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dc070)
Location: drivers/i2c/i2c-core.c:2873
Inline: False
Direct callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_i2c_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:acpi_i2c_space_handler
```
**Symbols:**

```
ffffffff816dc070-ffffffff816dc0d3: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170c3b0)
Location: drivers/i2c/i2c-core.c:3161
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/htc-i2cpld.c:htcpld_handler
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/i2c/i2c-core.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8170c3b0-ffffffff8170c413: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81723220)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81723220-ffffffff81723281: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81794640)
Location: drivers/i2c/i2c-core-smbus.c:129
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81794640-ffffffff817946a1: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817d71a0)
Location: drivers/i2c/i2c-core-smbus.c:130
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817d71a0-ffffffff817d7201: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff817fe300)
Location: drivers/i2c/i2c-core-smbus.c:130
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff817fe300-ffffffff817fe361: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8183f530)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8183f530-ffffffff8183f592: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81870ed0)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81870ed0-ffffffff81870f32: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81945522)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_freeze
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81944f10-ffffffff81944f72: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8194b562)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_freeze
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8194af50-ffffffff8194afb2: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff8192f0a2)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_freeze
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff8192ea90-ffffffff8192eaf2: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff819d22d2)
Location: drivers/i2c/i2c-core-smbus.c:136
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_freeze
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff819d1cc0-ffffffff819d1d22: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81b34ac9)
Location: drivers/i2c/i2c-core-smbus.c:137
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_freeze
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81b342f0-ffffffff81b3438a: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81cc9b99)
Location: drivers/i2c/i2c-core-smbus.c:137
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_freeze
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81cc9320-ffffffff81cc93ba: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81d319ca)
Location: drivers/i2c/i2c-core-smbus.c:137
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_freeze
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81d31040-ffffffff81d310da: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81de79aa)
Location: drivers/i2c/i2c-core-smbus.c:137
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_freeze
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8998.c:max8998_freeze
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/adp5520.c:adp5520_suspend
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_irq_thread
  - drivers/mfd/adp5520.c:adp5520_clr_bits
  - drivers/mfd/adp5520.c:adp5520_set_bits
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81de7020-ffffffff81de70ba: i2c_smbus_read_byte_data (STB_GLOBAL)
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
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffff800010ab4b08)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/stmpe-i2c.c:i2c_reg_read
  - drivers/mfd/tc3589x.c:tc3589x_reg_read
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffff800010ab4b08-ffff800010ab4b88: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c0b95d38)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/stmpe-i2c.c:i2c_reg_read
  - drivers/mfd/tc3589x.c:tc3589x_reg_read
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
c0b95d38-c0b95db8: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (c000000000b98d30)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/stmpe-i2c.c:i2c_reg_read
  - drivers/mfd/tc3589x.c:tc3589x_reg_read
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
c000000000b98d30-c000000000b98db0: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006bbf70)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/stmpe-i2c.c:i2c_reg_read
  - drivers/mfd/tc3589x.c:tc3589x_reg_read
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
```
**Symbols:**

```
ffffffe0006bbf70-ffffffe0006bbfba: i2c_smbus_read_byte_data (STB_GLOBAL)
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
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81865060)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81865060-ffffffff818650c2: i2c_smbus_read_byte_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s32 i2c_smbus_read_byte_data(const struct i2c_client *client, u8 command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-smbus.c (ffffffff81880310)
Location: drivers/i2c/i2c-core-smbus.c:128
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_regmap_reg_read
  - drivers/base/regmap/regmap-i2c.c:regmap_smbus_byte_reg_read
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set_ni
  - drivers/mfd/da903x.c:da9034_init_chip
  - drivers/mfd/da903x.c:da9030_read_status
  - drivers/mfd/da903x.c:da9030_init_chip
  - drivers/mfd/da903x.c:da903x_update
  - drivers/mfd/da903x.c:da903x_clr_bits
  - drivers/mfd/da903x.c:da903x_set_bits
  - drivers/mfd/da903x.c:da903x_read
  - drivers/mfd/max8925-i2c.c:max8925_set_bits
  - drivers/mfd/max8925-i2c.c:max8925_bulk_read
  - drivers/mfd/max8925-i2c.c:max8925_reg_read
  - drivers/mfd/max8997.c:max8997_update_reg
  - drivers/mfd/max8997.c:max8997_read_reg
  - drivers/mfd/max8998.c:max8998_update_reg
  - drivers/mfd/max8998.c:max8998_read_reg
  - drivers/mfd/adp5520.c:__adp5520_read
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_byte_reg_read
  - drivers/i2c/i2c-core-smbus.c:i2c_smbus_read_i2c_block_data_or_emulated
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
**Symbols:**

```
ffffffff81880310-ffffffff81880372: i2c_smbus_read_byte_data (STB_GLOBAL)
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
