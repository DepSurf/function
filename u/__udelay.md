# Function: <code>__udelay</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff813f6500)
Location: arch/x86/lib/delay.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff813f6500-ffffffff813f6531: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8143d0d0)
Location: arch/x86/lib/delay.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff8143d0d0-ffffffff8143d103: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8145a050)
Location: arch/x86/lib/delay.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff8145a050-ffffffff8145a083: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff818fbd70)
Location: arch/x86/lib/delay.c:178
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
**Symbols:**

```
ffffffff818fbd70-ffffffff818fbdb1: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81982bd0)
Location: arch/x86/lib/delay.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:write_new_fid
```
**Symbols:**

```
ffffffff81982bd0-ffffffff81982c17: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff819df140)
Location: arch/x86/lib/delay.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff819df140-ffffffff819df187: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a1a070)
Location: arch/x86/lib/delay.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff81a1a070-ffffffff81a1a0b7: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a89d40)
Location: arch/x86/lib/delay.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff81a89d40-ffffffff81a89d57: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81ac1000)
Location: arch/x86/lib/delay.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff81ac1000-ffffffff81ac1017: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff815fd490)
Location: arch/x86/lib/delay.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff815fd490-ffffffff815fd4a7: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff816221c0)
Location: arch/x86/lib/delay.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/usb/early/xhci-dbc.c:handshake
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff816221c0-ffffffff816221d7: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81605aa0)
Location: arch/x86/lib/delay.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff81605aa0-ffffffff81605ab7: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81674390)
Location: arch/x86/lib/delay.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff81674390-ffffffff816743a7: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8178ea80)
Location: arch/x86/lib/delay.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - kernel/rcu/srcutree.c:try_check_zero
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff8178ea80-ffffffff8178ea9d: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8204c410)
Location: arch/x86/lib/delay.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - kernel/rcu/srcutree.c:try_check_zero
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff8204c410-ffffffff8204c42d: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff820cad20)
Location: arch/x86/lib/delay.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:send_init_sequence
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - kernel/rcu/srcutree.c:try_check_zero
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff820cad20-ffffffff820cad3d: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff821a5550)
Location: arch/x86/lib/delay.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - kernel/rcu/srcutree.c:try_check_zero
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_delay_helper
  - drivers/base/regmap/regmap.c:_regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:_regmap_range_multi_paged_reg_write
  - drivers/spi/spi.c:spi_delay_exec
  - drivers/spi/spi-mem.c:spi_mem_poll_status
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/net/phy/mdio_device.c:mdio_device_reset
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:core_voltage_pre_transition
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff821a5550-ffffffff821a556d: __udelay (STB_GLOBAL)
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
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/lib/delay.c (ffff800010d82870)
Location: arch/arm64/lib/delay.c:49
Inline: False
Direct callers:
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/clk/actions/owl-pll.c:owl_pll_set_rate
  - drivers/clk/rockchip/clk-pll.c:rockchip_rk3066_pll_set_params
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_notifier_cb
  - drivers/clk/sunxi-ng/ccu_mux.c:ccu_mux_notifier_cb
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/iommu/arm-smmu.c:__arm_smmu_tlb_sync
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
**Symbols:**

```
ffff800010d82870-ffff800010d828b4: __udelay (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a5fe50)
Location: arch/x86/lib/delay.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff81a5fe50-ffffffff81a5fe67: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a1cf20)
Location: arch/x86/lib/delay.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
  - drivers/hv/connection.c:vmbus_post_msg
```
**Symbols:**

```
ffffffff81a1cf20-ffffffff81a1cf37: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81acc240)
Location: arch/x86/lib/delay.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff81acc240-ffffffff81acc257: __udelay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __udelay(long unsigned int usecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81ad8720)
Location: arch/x86/lib/delay.c:179
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:wakeup_secondary_cpu_via_init
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - drivers/acpi/osl.c:acpi_os_stall
  - drivers/acpi/ec.c:ec_guard
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/apei/erst.c:erst_exec_stall
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_do_set_voltage
  - drivers/regulator/core.c:_regulator_enable_delay
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
  - drivers/cpufreq/powernow-k8.c:write_new_fid
  - drivers/clocksource/acpi_pm.c:init_acpi_pm_clocksource
```
**Symbols:**

```
ffffffff81ad8720-ffffffff81ad8737: __udelay (STB_GLOBAL)
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
