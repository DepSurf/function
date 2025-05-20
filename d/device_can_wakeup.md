# Function: <code>device_can_wakeup</code>

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
In drivers/acpi/wakeup.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/acpi/device_pm.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8160e006)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff81676108)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
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
In drivers/acpi/wakeup.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/acpi/device_pm.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8166dbf8)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff816d69d7)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
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
In drivers/acpi/wakeup.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/acpi/device_pm.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff815de69b)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff8169b8d8)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff817066b7)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
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
In drivers/pci/pci.c (ffffffff814abcbf)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/acpi/wakeup.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/base/power/domain.c (ffffffff815f321a)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff816b0cc8)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8171c297)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
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
In drivers/pci/pci.c (ffffffff814ead8f)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff814f09a8)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/acpi/proc.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/pnp/pnpacpi/core.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/base/power/sysfs.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff8171c2dd)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/host/ehci-pci.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/usb/host/ohci-pci.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff8178d517)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/pm_wakeup.h:81
Inline: True
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
In drivers/pci/pci.c (ffffffff8151a344)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff815202e7)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff8271e98d)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff8157208b)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff81572e31)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff815dd622)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff8168c0b6)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (ffffffff81691c15)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (ffffffff8169662d)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff8175b026)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (ffffffff81760f82)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8178d144)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81793dc8)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/rtc-sysfs.c (ffffffff817cfad0)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/rtc/rtc-sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (ffffffff81830054)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff815300b2)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff81536115)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff828d69b8)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff81589e6b)
Location: include/linux/pm_wakeup.h:81
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff8158aa41)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff815f6dc2)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff816ac2e6)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (ffffffff816b2202)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (ffffffff816b6cfd)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff8177f556)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
```
In drivers/usb/core/driver.c (ffffffff81785542)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff817b3944)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff817ba398)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff817f6a90)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (ffffffff8185c2d4)
Location: include/linux/pm_wakeup.h:81
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff8155f892)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff81565a86)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff828f0831)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff815ba8eb)
Location: include/linux/pm_wakeup.h:68
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff815bb7d1)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81628cf2)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff816e5e79)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (ffffffff816ec0b2)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (ffffffff816f0b68)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff817bf37e)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff817c3ac8)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff817f2f45)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff817f9cb8)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff81837780)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (ffffffff8189ff04)
Location: include/linux/pm_wakeup.h:68
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff815809d2)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff81586d86)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff828f999b)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff815dbb8b)
Location: include/linux/pm_wakeup.h:72
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff815dca91)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8164a7e2)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff8170a253)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (ffffffff8171011f)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (ffffffff81715008)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff817efcfc)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff817f4458)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81823d65)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff8182aaf8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff818690f0)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (ffffffff818d5764)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff81624472)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff8162de37)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff82d10ab9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff81685b9a)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff816871a2)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff816f9972)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff817c5233)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/domain.c (ffffffff817d0538)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff818bf65f)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff818c3fc9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff818f58b0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff818fc978)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff8193cd80)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (ffffffff819a6b40)
Location: include/linux/pm_wakeup.h:77
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
In drivers/pci/pci.c (ffffffff8164a032)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff8165352a)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff82ffe59f)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff816a39aa)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff816a4eb5)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81716436)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff817d9d03)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/domain.c (ffffffff817e4ba8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff81c1cc8c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff818cfeb9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff818fe5a2)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff819052e8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff81942d90)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
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
In drivers/pci/pci.c (ffffffff8162cbfe)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff81635fca)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff83209352)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff8168679a)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff81687c36)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff816f7726)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff817be0c3)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/usb/core/hcd.c (ffffffff81c0ea51)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff818b34e9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff818e1d0a)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff818e8ad8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff819265b0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
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
In drivers/pci/pci.c (ffffffff8169ebcf)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff816a61da)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff832f161d)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff816fbb3a)
Location: include/linux/pm_wakeup.h:77
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff816fd0c0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81771ec6)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff81848443)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/usb/core/hcd.c (ffffffff81d15bea)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81948949)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff8197dcda)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81984ee8)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff819c94f0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
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
In drivers/pci/pci.c (ffffffff817c0bf9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff817c8af6)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff834a96ab)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff81828d50)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
```
```
In drivers/acpi/proc.c (ffffffff8182a847)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff818a75e2)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff8198d14c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/usb/core/hcd.c (ffffffff81ee06f9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81aa1469)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81ad9312)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81ae0a78)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff81b2a7e4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
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
In drivers/pci/pci.c (ffffffff818dd4c9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff818e6170)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff83ee11b1)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff8195ae80)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
```
```
In drivers/acpi/proc.c (ffffffff8195cda4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff819f1832)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff81afcdfc)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/usb/core/hcd.c (ffffffff81c1f888)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81c26b59)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81c6429d)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81c6c198)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff81cbec10)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
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
In drivers/pci/pci.c (ffffffff81920a2e)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff819297b0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff83706b71)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff819a1350)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
```
```
In drivers/acpi/proc.c (ffffffff819a3004)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81a39ee2)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff81b4b1ec)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/usb/core/hcd.c (ffffffff81c8694c)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81c8db19)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81ccb6ca)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81cd3788)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff81d26539)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
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
In drivers/pci/pci.c (ffffffff81968bd0)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff81971fb2)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff8393a0f1)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff819e9a00)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_suspend_noirq
```
```
In drivers/acpi/proc.c (ffffffff819eb6b4)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81a85792)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff81ba35dc)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/usb/core/hcd.c (ffffffff81d3b3ba)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81d42559)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81d805ba)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff81d88748)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff81ddc2a9)
Location: include/linux/pm_wakeup.h:77
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
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
In drivers/pci/pci.c (ffff8000106e36e0)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffff8000106eb85c)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffff80001147cbfc)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffff800010767c90)
Location: include/linux/pm_wakeup.h:72
Inline: True
```
```
In drivers/base/power/sysfs.c (ffff8000108f85e8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (ffff800010900784)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (ffff8000109061e4)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffff800010a1dd04)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffff800010a24f38)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffff800010a5e5a4)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffff800010a666f8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffff800010aab8a8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (ffff800010b2f394)
Location: include/linux/pm_wakeup.h:72
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
In drivers/pci/pci.c (c087f640)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (c0886414)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/base/power/sysfs.c (c09e4180)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (c09ea9a4)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (c09f0360)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (c0af5204)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (c0afb584)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (c0b2f964)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (c0b37f60)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (c0b89ef8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/rtc/rtc-twl.c (c0b8f54c)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/rtc/rtc-twl.c:twl_rtc_alarm_irq_enable
```
```
In drivers/mmc/core/core.c (c0c0a6ec)
Location: include/linux/pm_wakeup.h:72
Inline: True
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
In drivers/pci/pci.c (c00000000085d8c0)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (c000000000867300)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/base/power/sysfs.c (c0000000009943fc)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (c00000000099dff8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (c0000000009a524c)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (c000000000ad6bdc)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (c000000000adfe58)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (c000000000b2c62c)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (c000000000b36fbc)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (c000000000b8d970)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (c000000000c28e10)
Location: include/linux/pm_wakeup.h:72
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
In drivers/pci/pci.c (ffffffe0004bad42)
Location: include/linux/pm_wakeup.h:114
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/base/power/sysfs.c (ffffffe000588912)
Location: include/linux/pm_wakeup.h:114
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
```
```
In drivers/usb/core/hcd.c (ffffffe000640ebe)
Location: include/linux/pm_wakeup.h:114
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffe000647200)
Location: include/linux/pm_wakeup.h:114
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffe0006794f2)
Location: include/linux/pm_wakeup.h:114
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffe000680694)
Location: include/linux/pm_wakeup.h:114
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffe0006b63b2)
Location: include/linux/pm_wakeup.h:114
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/pm_wakeup.h:114
Inline: True
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
In drivers/pci/pci.c (ffffffff81574ef2)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/acpi/wakeup.c (ffffffff828e26d9)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff815ce25b)
Location: include/linux/pm_wakeup.h:72
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff815cf0e1)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81610842)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff816cf9a3)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (ffffffff816d6216)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (ffffffff816db338)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff817a80dc)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff817ac838)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff817dc145)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff817e2ed8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff8181bda0)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (ffffffff81879124)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff81563652)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff815699e6)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff828da6f2)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff815b7e1b)
Location: include/linux/pm_wakeup.h:72
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff815b8ca1)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81604d92)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff816aacd3)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (ffffffff816b0b0f)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (ffffffff816b59b8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff81799af5)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff8179e238)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/rtc/sysfs.c (ffffffff817e3490)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
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
In drivers/pci/pci.c (ffffffff81574722)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff8157aad6)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff828f5597)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff815cfe6b)
Location: include/linux/pm_wakeup.h:72
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff815d0d71)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff8163e622)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff816fdf13)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (ffffffff81703ddf)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (ffffffff81708cc8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff817e4b7c)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff817e92d8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81818be5)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff8181f978)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff8185d280)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (ffffffff818ca5c4)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
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
In drivers/pci/pci.c (ffffffff8158ecf2)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_finish_runtime_suspend
```
```
In drivers/pci/pci-driver.c (ffffffff815950e6)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_suspend_noirq
```
```
In drivers/acpi/wakeup.c (ffffffff828fa9ef)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_wakeup_device_init
```
```
In drivers/acpi/device_pm.c (ffffffff815e9d2b)
Location: include/linux/pm_wakeup.h:72
Inline: True
```
```
In drivers/acpi/proc.c (ffffffff815eac31)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
  - drivers/acpi/proc.c:acpi_system_write_wakeup_device
```
```
In drivers/pnp/pnpacpi/core.c (ffffffff81658972)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
```
In drivers/base/power/sysfs.c (ffffffff81718763)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/sysfs.c:dpm_sysfs_change_owner
  - drivers/base/power/sysfs.c:dpm_sysfs_add
  - drivers/base/power/sysfs.c:wakeup_store
  - drivers/base/power/sysfs.c:wakeup_show
```
```
In drivers/base/power/main.c (ffffffff8171eb2f)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend_noirq
```
```
In drivers/base/power/domain.c (ffffffff81723838)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_prepare
```
```
In drivers/usb/core/hcd.c (ffffffff817fede8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/hcd.c:rh_call_control
  - drivers/usb/core/hcd.c:rh_call_control
```
```
In drivers/usb/core/driver.c (ffffffff81803808)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:autosuspend_check
```
```
In drivers/usb/host/ehci-pci.c (ffffffff81832bd5)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
  - drivers/usb/host/ehci-pci.c:ehci_pci_setup
```
```
In drivers/usb/host/ohci-pci.c (ffffffff818398e8)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/usb/host/ohci-pci.c:ohci_pci_reset
```
```
In drivers/rtc/sysfs.c (ffffffff818784f0)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/rtc/sysfs.c:rtc_attr_is_visible
```
```
In drivers/mmc/core/core.c (ffffffff818e70e4)
Location: include/linux/pm_wakeup.h:72
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
```
</details>
</li>
</ul>

## Differences
