# Function: <code>acpi_device_enumerated</code>

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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814521d2)
Location: include/acpi/acpi_bus.h:519
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff8147fbe3)
Location: include/acpi/acpi_bus.h:519
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff81484fb9)
Location: include/acpi/acpi_bus.h:519
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149e862)
Location: include/acpi/acpi_bus.h:528
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff814ce471)
Location: include/acpi/acpi_bus.h:528
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff814d3b21)
Location: include/acpi/acpi_bus.h:528
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/spi/spi.c (ffffffff81647851)
Location: include/acpi/acpi_bus.h:528
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff816da8a6)
Location: include/acpi/acpi_bus.h:528
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:acpi_i2c_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c0492)
Location: include/acpi/acpi_bus.h:528
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff814f0345)
Location: include/acpi/acpi_bus.h:528
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff814f6170)
Location: include/acpi/acpi_bus.h:528
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/spi/spi.c (ffffffff81678941)
Location: include/acpi/acpi_bus.h:528
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff81709d25)
Location: include/acpi/acpi_bus.h:528
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_acpi_do_lookup
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cabd2)
Location: include/acpi/acpi_bus.h:533
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff814fd3e6)
Location: include/acpi/acpi_bus.h:533
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff81504201)
Location: include/acpi/acpi_bus.h:533
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/spi/spi.c (ffffffff8168d1e1)
Location: include/acpi/acpi_bus.h:533
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81723d35)
Location: include/acpi/acpi_bus.h:533
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150b1a2)
Location: include/acpi/acpi_bus.h:544
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff8153f126)
Location: include/acpi/acpi_bus.h:544
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff81546521)
Location: include/acpi/acpi_bus.h:544
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/tty/serdev/core.c (ffffffff81609cf7)
Location: include/acpi/acpi_bus.h:544
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff816f6bd1)
Location: include/acpi/acpi_bus.h:544
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81795235)
Location: include/acpi/acpi_bus.h:544
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8153fe52)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff81575075)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff8157c5bf)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/tty/serdev/core.c (ffffffff81643517)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81732079)
Location: include/acpi/acpi_bus.h:547
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d7d09)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81557192)
Location: include/acpi/acpi_bus.h:553
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff8158ce75)
Location: include/acpi/acpi_bus.h:553
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff815942ff)
Location: include/acpi/acpi_bus.h:553
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/tty/serdev/core.c (ffffffff81661857)
Location: include/acpi/acpi_bus.h:553
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81754a69)
Location: include/acpi/acpi_bus.h:553
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff817fee99)
Location: include/acpi/acpi_bus.h:553
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815871d2)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff815bdc35)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff815c536d)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/tty/serdev/core.c (ffffffff81697383)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff817902c3)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81840234)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a8ba2)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff815deef5)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff815e659d)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/acpi/acpi_platform.c (ffffffff815eb995)
Location: include/acpi/acpi_bus.h:540
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816b9f4b)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff817b3ea3)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81871b6b)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81651852)
Location: include/acpi/acpi_bus.h:541
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff8168c295)
Location: include/acpi/acpi_bus.h:541
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
```
In drivers/acpi/dock.c (ffffffff81691dab)
Location: include/acpi/acpi_bus.h:541
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:hotplug_dock_devices
```
```
In drivers/acpi/acpi_platform.c (ffffffff81697405)
Location: include/acpi/acpi_bus.h:541
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8176e305)
Location: include/acpi/acpi_bus.h:541
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff8187b583)
Location: include/acpi/acpi_bus.h:541
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194645e)
Location: include/acpi/acpi_bus.h:541
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81674212)
Location: include/acpi/acpi_bus.h:542
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff816aa314)
Location: include/acpi/acpi_bus.h:542
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
```
In drivers/acpi/dock.c (ffffffff816af84b)
Location: include/acpi/acpi_bus.h:542
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:hotplug_dock_devices
```
```
In drivers/acpi/acpi_platform.c (ffffffff816b4555)
Location: include/acpi/acpi_bus.h:542
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81788cd5)
Location: include/acpi/acpi_bus.h:542
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff8188a236)
Location: include/acpi/acpi_bus.h:542
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff8194c3ae)
Location: include/acpi/acpi_bus.h:542
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81656742)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff8168cb9a)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
```
In drivers/acpi/dock.c (ffffffff81691e5b)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/acpi/dock.c:docked_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/acpi/acpi_platform.c (ffffffff81696785)
Location: include/acpi/acpi_bus.h:543
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8176c4c7)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff8186cc16)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819302ee)
Location: include/acpi/acpi_bus.h:543
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8712)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff817023ea)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
```
In drivers/acpi/dock.c (ffffffff8170796b)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/acpi/dock.c:docked_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/acpi/acpi_platform.c (ffffffff8170c525)
Location: include/acpi/acpi_bus.h:547
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff817f1c07)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff818fcac6)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff819d35bf)
Location: include/acpi/acpi_bus.h:547
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817ee8d2)
Location: include/acpi/acpi_bus.h:556
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff8183010f)
Location: include/acpi/acpi_bus.h:556
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
```
```
In drivers/acpi/dock.c (ffffffff81835d29)
Location: include/acpi/acpi_bus.h:556
Inline: True
Inline callers:
  - drivers/acpi/dock.c:docked_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/acpi/acpi_platform.c (ffffffff8183abd5)
Location: include/acpi/acpi_bus.h:556
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81932353)
Location: include/acpi/acpi_bus.h:556
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81a4e1ad)
Location: include/acpi/acpi_bus.h:556
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81b35ca8)
Location: include/acpi/acpi_bus.h:556
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81916982)
Location: include/acpi/acpi_bus.h:566
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff8196327d)
Location: include/acpi/acpi_bus.h:566
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/acpi/dock.c (ffffffff81969d09)
Location: include/acpi/acpi_bus.h:566
Inline: True
Inline callers:
  - drivers/acpi/dock.c:docked_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/acpi/acpi_platform.c (ffffffff81970255)
Location: include/acpi/acpi_bus.h:566
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81a90e33)
Location: include/acpi/acpi_bus.h:566
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81bd86ee)
Location: include/acpi/acpi_bus.h:566
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81ccaf28)
Location: include/acpi/acpi_bus.h:566
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81959f72)
Location: include/acpi/acpi_bus.h:569
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff819a9724)
Location: include/acpi/acpi_bus.h:569
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/acpi/dock.c (ffffffff819b02c9)
Location: include/acpi/acpi_bus.h:569
Inline: True
Inline callers:
  - drivers/acpi/dock.c:docked_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/acpi/acpi_platform.c (ffffffff819b6895)
Location: include/acpi/acpi_bus.h:569
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81adc643)
Location: include/acpi/acpi_bus.h:569
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81c2f0de)
Location: include/acpi/acpi_bus.h:569
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32cf9)
Location: include/acpi/acpi_bus.h:569
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a3512)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff819f2224)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
```
```
In drivers/acpi/dock.c (ffffffff819fa779)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/acpi/dock.c:docked_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/acpi/acpi_platform.c (ffffffff81a00e45)
Location: include/acpi/acpi_bus.h:669
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81b2f963)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81ce1d22)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8d19)
Location: include/acpi/acpi_bus.h:669
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_notify
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/bus/hisi_lpc.c (ffff80001067f2ec)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff800010711d84)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffff80001076b538)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffff8000107735f8)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/acpi/acpi_platform.c (ffff800010776e64)
Location: include/acpi/acpi_bus.h:540
Inline: True
```
```
In drivers/tty/serdev/core.c (ffff8000108a9910)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffff8000109c31f8)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab531c)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159c3b2)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff815d13d5)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/acpi_platform.c (ffffffff815dad75)
Location: include/acpi/acpi_bus.h:540
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8167f9ab)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff81778983)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158b542)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff815baf95)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/acpi_platform.c (ffffffff815c63b5)
Location: include/acpi/acpi_bus.h:540
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81758733)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159c8f2)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff815d31d5)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff815da87d)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/acpi/acpi_platform.c (ffffffff815dfc75)
Location: include/acpi/acpi_bus.h:540
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816add8b)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff817a8d23)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81865cfb)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
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
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b6d22)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_rescan_slot
```
```
In drivers/acpi/scan.c (ffffffff815ed095)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_device_not_present
```
```
In drivers/acpi/dock.c (ffffffff815f473d)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
```
```
In drivers/acpi/acpi_platform.c (ffffffff815f9b35)
Location: include/acpi/acpi_bus.h:540
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816c81eb)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
```
```
In drivers/spi/spi.c (ffffffff817c2bb3)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81880fab)
Location: include/acpi/acpi_bus.h:540
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
</details>
</li>
</ul>

## Differences
