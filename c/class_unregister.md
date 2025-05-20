# Function: <code>class_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8154cc30)
Location: drivers/base/class.c:212
Inline: False
Direct callers:
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/input/input.c:input_exit
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff8154cc30-ffffffff8154ccb1: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8159ea30)
Location: drivers/base/class.c:212
Inline: False
Direct callers:
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff8159ea30-ffffffff8159eaad: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815ccfe0)
Location: drivers/base/class.c:226
Inline: False
Direct callers:
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff815ccfe0-ffffffff815cd070: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815e1b00)
Location: drivers/base/class.c:194
Inline: False
Direct callers:
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/input/input.c:input_exit
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff815e1b00-ffffffff815e1b47: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81648c70)
Location: drivers/base/class.c:194
Inline: False
Direct callers:
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_class.c:firmware_class_exit
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/input/input.c:input_exit
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff81648c70-ffffffff81648cb7: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81684250)
Location: drivers/base/class.c:192
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81684250-ffffffff81684297: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a3f20)
Location: drivers/base/class.c:192
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816a3f20-ffffffff816a3f67: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816dce50)
Location: drivers/base/class.c:198
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816dce50-ffffffff816dce97: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81700f00)
Location: drivers/base/class.c:198
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81700f00-ffffffff81700f47: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817bae70)
Location: drivers/base/class.c:199
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff817bae70-ffffffff817baeba: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817cfa70)
Location: drivers/base/class.c:199
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/core.c:devlink_class_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff817cfa70-ffffffff817cfaba: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817b3480)
Location: drivers/base/class.c:199
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/core.c:devlink_class_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff817b3480-ffffffff817b34ca: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8183c960)
Location: drivers/base/class.c:199
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/core.c:devlink_class_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff8183c960-ffffffff8183c9a7: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8197f400)
Location: drivers/base/class.c:199
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/core.c:devlink_class_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff8197f400-ffffffff8197f453: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81aecc50)
Location: drivers/base/class.c:204
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/core.c:devlink_class_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81aecc50-ffffffff81aecca3: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void class_unregister(const struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b3b320)
Location: drivers/base/class.c:223
Inline: False
Direct callers:
  - block/bsg.c:bsg_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtio_console_fini
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/base/core.c:devlink_class_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/roles/class.c:usb_roles_exit
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81b3b320-ffffffff81b3b38d: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void class_unregister(const struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b92e70)
Location: drivers/base/class.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_release
  - block/bsg.c:bsg_init
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/char/misc.c:misc_init
  - drivers/char/virtio_console.c:virtio_console_fini
  - drivers/char/virtio_console.c:virtio_console_init
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_exit
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/char/tpm/tpm-interface.c:tpm_init
  - drivers/base/core.c:devlink_class_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/sysfs.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/accel/drm_accel.c:accel_core_exit
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/roles/class.c:usb_roles_exit
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/leds/led-class.c:leds_exit
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_exit
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81b92e70-ffffffff81b92edd: class_unregister (STB_GLOBAL)
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
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffff8000108ec6d8)
Location: drivers/base/class.c:198
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffff8000108ec6d8-ffff8000108ec738: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c09da5a0)
Location: drivers/base/class.c:198
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/mtd/mtdcore.c:cleanup_mtd
  - drivers/mtd/mtdcore.c:init_mtd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
c09da5a0-c09da600: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c000000000983fb0)
Location: drivers/base/class.c:198
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
c000000000983fb0-c000000000984060: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffe00057fa14)
Location: drivers/base/class.c:198
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffe00057fa14-ffffffe00057fa78: class_unregister (STB_GLOBAL)
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
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816c66f0)
Location: drivers/base/class.c:198
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816c66f0-ffffffff816c6737: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a1950)
Location: drivers/base/class.c:198
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/firmware/dmi-id.c:dmi_id_init
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816a1950-ffffffff816a1997: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816f4bc0)
Location: drivers/base/class.c:198
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff816f4bc0-ffffffff816f4c07: class_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void class_unregister(struct class *cls);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170f450)
Location: drivers/base/class.c:198
Inline: False
Direct callers:
  - drivers/rapidio/rio-driver.c:rio_bus_init
  - drivers/base/class.c:class_destroy
  - drivers/base/transport_class.c:transport_class_unregister
  - drivers/base/firmware_loader/fallback.c:unregister_sysfs_loader
  - drivers/base/devcoredump.c:devcoredump_exit
  - drivers/scsi/hosts.c:scsi_exit_hosts
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_unregister
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/spi/spi.c:spi_init
  - drivers/net/phy/mdio_bus.c:mdio_bus_exit
  - drivers/net/phy/mdio_bus.c:mdio_bus_init
  - drivers/input/input.c:input_exit
  - drivers/input/input.c:input_init
  - drivers/hwmon/hwmon.c:hwmon_exit
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
  - drivers/mmc/core/host.c:mmc_unregister_host_class
  - drivers/firmware/dmi-id.c:dmi_id_init
  - drivers/remoteproc/remoteproc_sysfs.c:rproc_exit_sysfs
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff8170f450-ffffffff8170f497: class_unregister (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class *cls</code> ➡️ <code>const struct class *cls</code>
</li>
</ul>
</details>
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
