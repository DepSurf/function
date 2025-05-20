# Function: <code>pm_runtime_suspended</code>

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
In drivers/pci/pci.c (ffffffff814371a5)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_complete_resume
```
```
In drivers/acpi/device_pm.c (ffffffff8147d317)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81487913)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/scsi/scsi_pm.c (ffffffff815b91b3)
Location: include/linux/pm_runtime.h:85
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff815bcaba)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff815c8cb0)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff815e22bf)
Location: include/linux/pm_runtime.h:85
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
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
In drivers/pci/pci.c (ffffffff81482e2c)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_keep_suspended
```
```
In drivers/acpi/device_pm.c (ffffffff814cbacd)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814d663d)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/domain.c (ffffffff815b01de)
Location: include/linux/pm_runtime.h:90
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81611802)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/scsi/sd.c (ffffffff816157aa)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff816212af)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff8163bfa0)
Location: include/linux/pm_runtime.h:90
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
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
In drivers/pci/pci.c (ffffffff814a43bc)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_keep_suspended
```
```
In drivers/acpi/device_pm.c (ffffffff814ed9fb)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/acpi/acpi_lpss.c (ffffffff814f8c9d)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/domain.c (ffffffff815df56d)
Location: include/linux/pm_runtime.h:89
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81641092)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/scsi/sd.c (ffffffff816451da)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff81651e2f)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff8166d020)
Location: include/linux/pm_runtime.h:89
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
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
In drivers/pci/pci.c (ffffffff814ae47c)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_keep_suspended
```
```
In drivers/acpi/device_pm.c (ffffffff814f9ed3)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_prepare
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815079b0)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/domain.c (ffffffff815f42b4)
Location: include/linux/pm_runtime.h:79
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8165597a)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/scsi/sd.c (ffffffff816589aa)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff8166646f)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff81681670)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81727047)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
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
In drivers/pci/pci.c (ffffffff814ed84c)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_keep_suspended
```
```
In drivers/pci/pci-driver.c (ffffffff814eff28)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff8153b75a)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81549e31)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/main.c (ffffffff81658501)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff8165c134)
Location: include/linux/pm_runtime.h:79
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff816bef2a)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/scsi/sd.c (ffffffff816c1fea)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff816cfacf)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff816eaeb0)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798697)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_prepare
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
In drivers/pci/pci.c (ffffffff8151d4ac)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_keep_suspended
```
```
In drivers/pci/pci-driver.c (ffffffff81520ae8)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff8157159a)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81580041)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/main.c (ffffffff81693f37)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff81697e84)
Location: include/linux/pm_runtime.h:79
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff816fb53a)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/scsi/sd.c (ffffffff816fe64a)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff8170c4f5)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff8172782f)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db525)
Location: include/linux/pm_runtime.h:79
Inline: True
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
In drivers/pci/pci.c (ffffffff81532bac)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_keep_suspended
  - drivers/pci/pci.c:pci_dev_keep_suspended
```
```
In drivers/pci/pci-driver.c (ffffffff81536918)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff8158935a)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81597f24)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/main.c (ffffffff816b45b7)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff816b8694)
Location: include/linux/pm_runtime.h:79
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8171e1d3)
Location: include/linux/pm_runtime.h:79
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8172121a)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff8172e975)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff8174a00f)
Location: include/linux/pm_runtime.h:79
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818028d5)
Location: include/linux/pm_runtime.h:79
Inline: True
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
In drivers/pci/pci.c (ffffffff815622ef)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff815661f8)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff815b9e4a)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c925e)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/main.c (ffffffff816ee440)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff816f26d5)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81759903)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8175c8e8)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff8176a165)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff81785e7f)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843d95)
Location: include/linux/pm_runtime.h:78
Inline: True
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
In drivers/pci/pci.c (ffffffff8158348f)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff81587558)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff815db08a)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815ea2ee)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/main.c (ffffffff8171241e)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff81716ba5)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8177d813)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff817807b8)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff8178e1c5)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff817a9abf)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875705)
Location: include/linux/pm_runtime.h:78
Inline: True
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
In drivers/pci/pci.c (ffffffff8162a05f)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff8162d358)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff8168566a)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8169613e)
Location: include/linux/pm_runtime.h:83
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff817d2bbb)
Location: include/linux/pm_runtime.h:83
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81840c87)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
```
In drivers/scsi/sd.c (ffffffff818468a8)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff81853d95)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff8186f3ff)
Location: include/linux/pm_runtime.h:83
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a225)
Location: include/linux/pm_runtime.h:83
Inline: True
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
In drivers/pci/pci.c (ffffffff816504bf)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff81652a48)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff816a341a)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff816b328e)
Location: include/linux/pm_runtime.h:120
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff817e76cb)
Location: include/linux/pm_runtime.h:120
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff818511c7)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
```
In drivers/scsi/sd.c (ffffffff81858408)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff81864065)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff8187e0cf)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fdb5)
Location: include/linux/pm_runtime.h:120
Inline: True
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
In drivers/pci/pci.c (ffffffff8163306f)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff81635508)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff8168621a)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8169550e)
Location: include/linux/pm_runtime.h:120
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff817cb7bb)
Location: include/linux/pm_runtime.h:120
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81834257)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
```
In drivers/scsi/sd.c (ffffffff8183b388)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff81846cc5)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff8186087f)
Location: include/linux/pm_runtime.h:120
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933c75)
Location: include/linux/pm_runtime.h:120
Inline: True
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
In drivers/pci/pci.c (ffffffff816a31df)
Location: include/linux/pm_runtime.h:123
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff816a5418)
Location: include/linux/pm_runtime.h:123
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff816fb52a)
Location: include/linux/pm_runtime.h:123
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8170b23e)
Location: include/linux/pm_runtime.h:123
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81855113)
Location: include/linux/pm_runtime.h:123
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/scsi/scsi_pm.c (ffffffff818c0257)
Location: include/linux/pm_runtime.h:123
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_poweroff
  - drivers/scsi/scsi_pm.c:scsi_bus_freeze
  - drivers/scsi/scsi_pm.c:scsi_bus_suspend
```
```
In drivers/scsi/sd.c (ffffffff818c7b38)
Location: include/linux/pm_runtime.h:123
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff818d30e5)
Location: include/linux/pm_runtime.h:123
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff818ef63f)
Location: include/linux/pm_runtime.h:123
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d7075)
Location: include/linux/pm_runtime.h:123
Inline: True
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
In drivers/pci/pci.c (ffffffff817c53e6)
Location: include/linux/pm_runtime.h:153
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff817c7a88)
Location: include/linux/pm_runtime.h:153
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff818289f8)
Location: include/linux/pm_runtime.h:153
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81839791)
Location: include/linux/pm_runtime.h:153
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff8199bda7)
Location: include/linux/pm_runtime.h:153
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/scsi/sd.c (ffffffff81a146e5)
Location: include/linux/pm_runtime.h:153
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_resume_system
  - drivers/scsi/sd.c:sd_suspend_system
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff81a237e3)
Location: include/linux/pm_runtime.h:153
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff81a417bb)
Location: include/linux/pm_runtime.h:153
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39b85)
Location: include/linux/pm_runtime.h:153
Inline: True
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
In drivers/pci/pci.c (ffffffff818e2496)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff818e51f8)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff8195aad8)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff8196ed71)
Location: include/linux/pm_runtime.h:157
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81b0cfc7)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/scsi/sd.c (ffffffff81b94b25)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_resume_system
  - drivers/scsi/sd.c:sd_suspend_system
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff81ba5663)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff81bc7afb)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81cce1a1)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
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
In drivers/pci/pci.c (ffffffff819258d6)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff81928838)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff819a0fa8)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff819b52f1)
Location: include/linux/pm_runtime.h:157
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff81b5afc3)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/base/power/domain.c:dev_pm_genpd_set_performance_state
```
```
In drivers/scsi/sd.c (ffffffff81beaf85)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_resume_system
  - drivers/scsi/sd.c:sd_suspend_system
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff81bfbcb3)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff81c1f68b)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d35f71)
Location: include/linux/pm_runtime.h:157
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
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
In drivers/pci/pci.c (ffffffff8196e056)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pci-driver.c (ffffffff81971058)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff819e9658)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff819ff671)
Location: include/linux/pm_runtime.h:155
Inline: True
```
```
In drivers/pmdomain/core.c (ffffffff81aa2a2f)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_dev_pm_set_performance_state
```
```
In drivers/scsi/sd.c (ffffffff81c40ce5)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_suspend_system
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff81c51978)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff81c747eb)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81dece41)
Location: include/linux/pm_runtime.h:155
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr
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
In drivers/pci/pci.c (ffff8000106e73d4)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffff8000106eb1f4)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffff800010767224)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d2058)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_pm_resume
```
```
In drivers/base/power/main.c (ffff800010902f40)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffff800010908960)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffff800010983ab0)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/sd.c (ffff800010986ef8)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffff800010999248)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffff8000109b6754)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba4f0)
Location: include/linux/pm_runtime.h:78
Inline: True
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
In drivers/pci/pci.c (c0882538)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (c0886cc8)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/base/power/main.c (c09ed218)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (c09f2de4)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/scsi_pm.c (c0a562c4)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/sd.c (c0a591b4)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (c0a6785c)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99b7c)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/power/avs/smartreflex.c (c0ba9b4c)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:sr_disable
```
```
In drivers/clocksource/timer-ti-dm.c (c0c47210)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_write_status
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_trigger
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
In drivers/pci/pci.c (c000000000861b1c)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (c0000000008668e4)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/base/power/main.c (c0000000009a1574)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (c0000000009a8530)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/scsi_pm.c (c000000000a40670)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/sd.c (c000000000a46594)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (c000000000a5a0b0)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9db90)
Location: include/linux/pm_runtime.h:78
Inline: True
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
In drivers/pci/pci.c (ffffffe0004bdb7c)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/base/power/domain.c (ffffffe00058f496)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/sd.c (ffffffe0005eb372)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffe0005f861a)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
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
In drivers/pci/pci.c (ffffffff815779af)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/acpi/device_pm.c (ffffffff815cd85a)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/base/power/main.c (ffffffff816d879e)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff816dced5)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81731f03)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81734ea8)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff81753355)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
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
In drivers/pci/pci.c (ffffffff815660ff)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff8156a1b8)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff815b73da)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c4d5e)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/main.c (ffffffff816b2df8)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff816b7655)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8170b323)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81716b48)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff817331f5)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
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
In drivers/pci/pci.c (ffffffff815771df)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff8157b2a8)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff815cf36a)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815de5ce)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/main.c (ffffffff817060de)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff8170a865)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81770cd3)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81775638)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff81783045)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff8179e93f)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186abb5)
Location: include/linux/pm_runtime.h:78
Inline: True
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
In drivers/pci/pci.c (ffffffff815916af)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_complete_resume
  - drivers/pci/pci.c:pci_dev_adjust_pme
  - drivers/pci/pci.c:pci_dev_need_resume
```
```
In drivers/pci/pci-driver.c (ffffffff815958b8)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_complete
```
```
In drivers/acpi/device_pm.c (ffffffff815e922a)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_dev_needs_resume
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f848e)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
```
```
In drivers/base/power/main.c (ffffffff81720ace)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/power/domain.c (ffffffff817257e5)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8178c473)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8178f418)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_shutdown
```
```
In drivers/ata/libata-core.c (ffffffff8179cf05)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_freeze
  - drivers/ata/libata-core.c:ata_port_pm_suspend
```
```
In drivers/ata/libata-zpodd.c (ffffffff817b87bf)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884b45)
Location: include/linux/pm_runtime.h:78
Inline: True
```
</details>
</li>
</ul>

## Differences
