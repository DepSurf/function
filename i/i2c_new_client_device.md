# Function: <code>i2c_new_client_device</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:727
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy_device
```
**Symbols:**

```
ffffffff8183da59-ffffffff8183dadd: i2c_new_client_device.cold (STB_LOCAL)
ffffffff8183c9a0-ffffffff8183cc1a: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:732
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy_device
```
**Symbols:**

```
ffffffff8186f418-ffffffff8186f49c: i2c_new_client_device.cold (STB_LOCAL)
ffffffff8186e3a0-ffffffff8186e61a: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:742
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-smbus.c:i2c_new_smbus_alert_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff819433b3-ffffffff81943437: i2c_new_client_device.cold (STB_LOCAL)
ffffffff81942190-ffffffff8194240a: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:870
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-smbus.c:i2c_new_smbus_alert_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81c24a40-ffffffff81c24add: i2c_new_client_device.cold (STB_LOCAL)
ffffffff819484d0-ffffffff81948772: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:914
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-smbus.c:i2c_new_smbus_alert_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81c16b50-ffffffff81c16bc9: i2c_new_client_device.cold (STB_LOCAL)
ffffffff8192be40-ffffffff8192c0f8: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:915
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-smbus.c:i2c_new_smbus_alert_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81d25835-ffffffff81d258ae: i2c_new_client_device.cold (STB_LOCAL)
ffffffff819cf000-ffffffff819cf2b5: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:916
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81ef15db-ffffffff81ef1654: i2c_new_client_device.cold (STB_LOCAL)
ffffffff81b30db0-ffffffff81b31070: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5730)
Location: drivers/i2c/i2c-core-base.c:917
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81cc5730-ffffffff81cc5a5e: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d3c0)
Location: drivers/i2c/i2c-core-base.c:932
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81d2d3c0-ffffffff81d2d6e2: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de32b0)
Location: drivers/i2c/i2c-core-base.c:935
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_encoder_slave.c:drm_i2c_encoder_init
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:new_device_store
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff81de32b0-ffffffff81de362d: i2c_new_client_device (STB_GLOBAL)
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
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab1a78)
Location: drivers/i2c/i2c-core-base.c:732
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
```
**Symbols:**

```
ffff800010ab1a78-ffff800010ab1d2c: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b93188)
Location: drivers/i2c/i2c-core-base.c:732
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy_device
```
**Symbols:**

```
c0b93188-c0b93404: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b94f70)
Location: drivers/i2c/i2c-core-base.c:732
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy_device
```
**Symbols:**

```
c000000000b94f70-c000000000b952d4: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9866)
Location: drivers/i2c/i2c-core-base.c:732
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy_device
```
**Symbols:**

```
ffffffe0006b9866-ffffffe0006b9abc: i2c_new_client_device (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:732
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy_device
```
**Symbols:**

```
ffffffff818635a8-ffffffff8186362c: i2c_new_client_device.cold (STB_LOCAL)
ffffffff81862530-ffffffff818627aa: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct i2c_client *i2c_new_client_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:732
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy_device
```
**Symbols:**

```
ffffffff8187e808-ffffffff8187e88c: i2c_new_client_device.cold (STB_LOCAL)
ffffffff8187d790-ffffffff8187da0a: i2c_new_client_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
