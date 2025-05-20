# Function: <code>i2c_new_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8167c5a0)
Location: drivers/i2c/i2c-core.c:1035
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/i2c/i2c-core.c:i2c_new_dummy
  - drivers/i2c/i2c-core.c:i2c_new_probed_device
  - drivers/i2c/i2c-core.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
**Symbols:**

```
ffffffff8167c5a0-ffffffff8167c7d0: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816dd270)
Location: drivers/i2c/i2c-core.c:1160
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/i2c/i2c-core.c:i2c_new_probed_device
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
  - drivers/i2c/i2c-core.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core.c:i2c_new_dummy
```
**Symbols:**

```
ffffffff816dd270-ffffffff816dd4aa: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170d5f0)
Location: drivers/i2c/i2c-core.c:1297
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/i2c/i2c-core.c:i2c_new_probed_device
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
  - drivers/i2c/i2c-core.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core.c:i2c_new_dummy
```
**Symbols:**

```
ffffffff8170d5f0-ffffffff8170d82a: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81720a60)
Location: drivers/i2c/i2c-core-base.c:725
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff81720a60-ffffffff81720d97: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81791db0)
Location: drivers/i2c/i2c-core-base.c:736
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff81791db0-ffffffff81792114: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d47d0)
Location: drivers/i2c/i2c-core-base.c:717
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff817d47d0-ffffffff817d4b30: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fb930)
Location: drivers/i2c/i2c-core-base.c:729
Inline: False
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_sysfs_new_device
  - drivers/i2c/i2c-core-base.c:i2c_new_dummy
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
```
**Symbols:**

```
ffffffff817fb930-ffffffff817fbc80: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183d4ca)
Location: drivers/i2c/i2c-core-base.c:818
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff8183cc20-ffffffff8183cc3f: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186eeca)
Location: drivers/i2c/i2c-core-base.c:823
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff8186e620-ffffffff8186e63f: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab283c)
Location: drivers/i2c/i2c-core-base.c:823
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-of.c:of_i2c_register_device
```
**Symbols:**

```
ffff800010ab1d30-ffff800010ab1d6c: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b93f14)
Location: drivers/i2c/i2c-core-base.c:823
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-of.c:of_i2c_register_device
```
**Symbols:**

```
c0b93404-c0b93428: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b961dc)
Location: drivers/i2c/i2c-core-base.c:823
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-of.c:of_i2c_register_device
```
**Symbols:**

```
c000000000b952e0-c000000000b9531c: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006ba4ee)
Location: drivers/i2c/i2c-core-base.c:823
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-of.c:of_i2c_register_device
```
**Symbols:**

```
ffffffe0006b9abc-ffffffe0006b9b02: i2c_new_device (STB_GLOBAL)
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
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186305a)
Location: drivers/i2c/i2c-core-base.c:823
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff818627b0-ffffffff818627cf: i2c_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct i2c_client *i2c_new_device(struct i2c_adapter *adap, const struct i2c_board_info *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187e2ba)
Location: drivers/i2c/i2c-core-base.c:823
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
Direct callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/i2c/i2c-core-smbus.c:i2c_setup_smbus_alert
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
```
**Symbols:**

```
ffffffff8187da10-ffffffff8187da2f: i2c_new_device (STB_GLOBAL)
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
