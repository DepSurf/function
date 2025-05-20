# Function: <code>pm_runtime_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81437306)
Location: include/linux/pm_runtime.h:201
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814393a3)
Location: include/linux/pm_runtime.h:201
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_prepare
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143b352)
Location: include/linux/pm_runtime.h:201
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/pci/pci-acpi.c (ffffffff81457485)
Location: include/linux/pm_runtime.h:201
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff8147cd46)
Location: include/linux/pm_runtime.h:201
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/power/wakeirq.c (ffffffff81557fbd)
Location: include/linux/pm_runtime.h:201
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:handle_threaded_wake_irq
```
```
In drivers/ata/libata-zpodd.c (ffffffff815e22dd)
Location: include/linux/pm_runtime.h:201
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff816152b5)
Location: include/linux/pm_runtime.h:201
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482ec9)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81485dfe)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff814871d6)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/pci/pci-acpi.c (ffffffff814a4095)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff814cba6e)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff815aa0cd)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:handle_threaded_wake_irq
```
```
In drivers/base/power/domain.c (ffffffff815af9dd)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff8163bfbe)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff81675275)
Location: include/linux/pm_runtime.h:207
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a4459)
Location: include/linux/pm_runtime.h:210
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814a75be)
Location: include/linux/pm_runtime.h:210
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a8986)
Location: include/linux/pm_runtime.h:210
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/pci/pci-acpi.c (ffffffff814c5e25)
Location: include/linux/pm_runtime.h:210
Inline: True
Inline callers:
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
```
```
In drivers/acpi/device_pm.c (ffffffff814ed99c)
Location: include/linux/pm_runtime.h:210
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
```
```
In drivers/base/power/wakeirq.c (ffffffff815d8cfd)
Location: include/linux/pm_runtime.h:210
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:handle_threaded_wake_irq
```
```
In drivers/base/power/domain.c (ffffffff815de6d5)
Location: include/linux/pm_runtime.h:210
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff8166d03e)
Location: include/linux/pm_runtime.h:210
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff816a2f05)
Location: include/linux/pm_runtime.h:210
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae519)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814b14da)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b35e8)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff814f9fb6)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/power/wakeirq.c (ffffffff815ed91d)
Location: include/linux/pm_runtime.h:198
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff815f325e)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff8168168e)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff816b8098)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81727136)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ed8e9)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814f0ac4)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f2dc8)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff8153bbe6)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/power/wakeirq.c (ffffffff81654ccd)
Location: include/linux/pm_runtime.h:198
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff8165aad6)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff816eaece)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff8172399f)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d549)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81520806)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff81523028)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff815719e1)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff8167f186)
Location: include/linux/pm_runtime.h:198
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff8169059d)
Location: include/linux/pm_runtime.h:198
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81696659)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff81727853)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff817625fe)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532c49)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81536636)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff81538e88)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff815897b1)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff8169f5d0)
Location: include/linux/pm_runtime.h:198
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff816b0dad)
Location: include/linux/pm_runtime.h:198
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816b6d29)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff8174a033)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff81786c0e)
Location: include/linux/pm_runtime.h:198
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81562399)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81565f0d)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156887d)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff815ba352)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff816d7ca3)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/base/power/wakeirq.c (ffffffff816eaa5d)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816f0c78)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff81785ea3)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff817c50eb)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81583539)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8158726d)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff81589abd)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff815db592)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff816fbe4a)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff8170ea9d)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81715118)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff817a9ae3)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff817f5a8b)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162a0f9)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8162d98d)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff816309bc)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff816859a2)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff817b5744)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff817ca20d)
Location: include/linux/pm_runtime.h:209
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff817d055f)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff8186f423)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff818c5b4d)
Location: include/linux/pm_runtime.h:209
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81650559)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8165307d)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff8165605c)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff816a37b2)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff817c9ffa)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff817decad)
Location: include/linux/pm_runtime.h:323
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff817e4bcf)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff8187e0f3)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff818d1a1d)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In net/core/dev.c (ffffffff81a0d38f)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - net/core/dev.c:__dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81633109)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81635b1d)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff81638ba9)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff816865b5)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff817ad81a)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff817c30ad)
Location: include/linux/pm_runtime.h:323
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff818608a3)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff818b503f)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In net/core/dev.c (ffffffff819f402f)
Location: include/linux/pm_runtime.h:323
Inline: True
Inline callers:
  - net/core/dev.c:__dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a3279)
Location: include/linux/pm_runtime.h:330
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff816a5d0d)
Location: include/linux/pm_runtime.h:330
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a8ed9)
Location: include/linux/pm_runtime.h:330
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff816fb8c5)
Location: include/linux/pm_runtime.h:330
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff81836b04)
Location: include/linux/pm_runtime.h:330
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff8184d4fd)
Location: include/linux/pm_runtime.h:330
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff818ef663)
Location: include/linux/pm_runtime.h:330
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff8194a5b4)
Location: include/linux/pm_runtime.h:330
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In net/core/dev.c (ffffffff81aa5911)
Location: include/linux/pm_runtime.h:330
Inline: True
Inline callers:
  - net/core/dev.c:__dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c5483)
Location: include/linux/pm_runtime.h:359
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff817c85ab)
Location: include/linux/pm_runtime.h:359
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cbb7c)
Location: include/linux/pm_runtime.h:359
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff81828de5)
Location: include/linux/pm_runtime.h:359
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff81978b45)
Location: include/linux/pm_runtime.h:359
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff819928e0)
Location: include/linux/pm_runtime.h:359
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81a417df)
Location: include/linux/pm_runtime.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff81aa3271)
Location: include/linux/pm_runtime.h:359
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In net/core/dev.c (ffffffff81c1d399)
Location: include/linux/pm_runtime.h:359
Inline: True
Inline callers:
  - net/core/dev.c:__dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e2543)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff818e5e4b)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e994c)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff8195af35)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff81ae543d)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff81b02dd0)
Location: include/linux/pm_runtime.h:363
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81bc7b1f)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff81c28da1)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In net/core/dev.c (ffffffff81dce609)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - net/core/dev.c:__dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81925983)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8192948b)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192cf5c)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff819a1405)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff81b337bf)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff81b50dd0)
Location: include/linux/pm_runtime.h:363
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81c1f6af)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff81c8fd71)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In net/core/dev.c (ffffffff81e3f209)
Location: include/linux/pm_runtime.h:363
Inline: True
Inline callers:
  - net/core/dev.c:__dev_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196e103)
Location: include/linux/pm_runtime.h:361
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81971c8b)
Location: include/linux/pm_runtime.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff819757e7)
Location: include/linux/pm_runtime.h:361
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff819e9ab5)
Location: include/linux/pm_runtime.h:361
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff81b8b0fe)
Location: include/linux/pm_runtime.h:361
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff81ba9350)
Location: include/linux/pm_runtime.h:361
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81c7480f)
Location: include/linux/pm_runtime.h:361
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff81d44921)
Location: include/linux/pm_runtime.h:361
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
```
In net/core/dev.c (ffffffff81efdb59)
Location: include/linux/pm_runtime.h:361
Inline: True
Inline callers:
  - net/core/dev.c:__dev_open
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e74b4)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffff8000106eba8c)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ee430)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffff8000107675d0)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffff8000108e675c)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffff8000108feac0)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/base/power/domain.c (ffff8000109062f0)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffff8000109b6780)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffff800010a26a28)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08825f8)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (c0886970)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/base/core.c (c09d4d74)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (c09e8f5c)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/base/power/domain.c (c09f041c)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/driver.c (c0afcb04)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000861c50)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (c000000000867644)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/base/core.c (c00000000097c5ac)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (c00000000099ba44)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/base/power/domain.c (c0000000009a53c0)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/driver.c (c000000000ae22f0)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bdc50)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffe0004c0d0a)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/base/core.c (ffffffe00057b142)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffe00058d0b0)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffe0006488c4)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577a59)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8157b43d)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d94d)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff815cdd72)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff816c163a)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff816d41ed)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816db448)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/driver.c (ffffffff817ade6b)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81566199)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81569ecd)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156c71d)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff815b78e2)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff8169c8ea)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff816af48d)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff816b5ac8)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/driver.c (ffffffff8179f86b)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577289)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8157afbd)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d80d)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff815cf872)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff816efb0a)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff8170275d)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81708dd8)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff8179e963)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff817ea90b)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81591749)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff815955cd)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_shutdown
```
```
In drivers/pci/pci-sysfs.c (ffffffff81597cbd)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
```
In drivers/acpi/device_pm.c (ffffffff815e9732)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
```
```
In drivers/base/core.c (ffffffff8170a34a)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/wakeirq.c (ffffffff8171cf7d)
Location: include/linux/pm_runtime.h:199
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81723948)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/ata/libata-zpodd.c (ffffffff817b87e3)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/usb/core/driver.c (ffffffff81804b4b)
Location: include/linux/pm_runtime.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_suspend
```
</details>
</li>
</ul>

## Differences
