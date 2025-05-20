# Function: <code>pci_lock_rescan_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81430050)
Location: drivers/pci/probe.c:2376
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81430050-ffffffff81430067: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147b7b0)
Location: drivers/pci/probe.c:2416
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8147b7b0-ffffffff8147b7c7: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149ccc0)
Location: drivers/pci/probe.c:2494
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8149ccc0-ffffffff8149ccd7: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a6bd0)
Location: drivers/pci/probe.c:2641
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff814a6bd0-ffffffff814a6be7: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e53b0)
Location: drivers/pci/probe.c:2868
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff814e53b0-ffffffff814e53c7: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815148f0)
Location: drivers/pci/probe.c:3085
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff815148f0-ffffffff81514907: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152a100)
Location: drivers/pci/probe.c:3211
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8152a100-ffffffff8152a117: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81559830)
Location: drivers/pci/probe.c:3435
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:dev_bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81559830-ffffffff81559847: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157a8d0)
Location: drivers/pci/probe.c:3169
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8157a8d0-ffffffff8157a8e7: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8161fd20)
Location: drivers/pci/probe.c:3221
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8161fd20-ffffffff8161fd37: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81646470)
Location: drivers/pci/probe.c:3229
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81646470-ffffffff81646487: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81629080)
Location: drivers/pci/probe.c:3273
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81629080-ffffffff81629097: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81698a30)
Location: drivers/pci/probe.c:3315
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81698a30-ffffffff81698a47: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817b9fd0)
Location: drivers/pci/probe.c:3286
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff817b9fd0-ffffffff817b9fed: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d4e70)
Location: drivers/pci/probe.c:3296
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff818d4e70-ffffffff818d4e8d: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81917f20)
Location: drivers/pci/probe.c:3310
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff81917f20-ffffffff81917f3d: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81960530)
Location: drivers/pci/probe.c:3359
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81960530-ffffffff8196054d: pci_lock_rescan_remove (STB_GLOBAL)
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
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106dd320)
Location: drivers/pci/probe.c:3169
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/controller/pci-host-common.c:pci_host_common_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffff8000106dd320-ffff8000106dd348: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0878e20)
Location: drivers/pci/probe.c:3169
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/controller/pci-host-common.c:pci_host_common_remove
```
**Symbols:**

```
c0878e20-c0878e44: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000855470)
Location: drivers/pci/probe.c:3169
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_special_event
  - arch/powerpc/kernel/eeh_driver.c:eeh_handle_normal_event
  - arch/powerpc/kernel/eeh_driver.c:eeh_reset_device
  - arch/powerpc/kernel/eeh_driver.c:eeh_reset_device
  - arch/powerpc/kernel/eeh_driver.c:eeh_rmv_device
  - arch/powerpc/kernel/eeh_driver.c:eeh_pe_report
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/controller/pci-host-common.c:pci_host_common_remove
```
**Symbols:**

```
c000000000855470-c0000000008554ac: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b5658)
Location: drivers/pci/probe.c:3169
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/controller/pci-host-common.c:pci_host_common_remove
```
**Symbols:**

```
ffffffe0004b5658-ffffffe0004b5682: pci_lock_rescan_remove (STB_GLOBAL)
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
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156edf0)
Location: drivers/pci/probe.c:3169
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8156edf0-ffffffff8156ee07: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155d550)
Location: drivers/pci/probe.c:3169
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8155d550-ffffffff8155d567: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156e620)
Location: drivers/pci/probe.c:3169
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8156e620-ffffffff8156e637: pci_lock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_lock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81588b00)
Location: drivers/pci/probe.c:3169
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
  - drivers/pci/pci-sysfs.c:dev_rescan_store
  - drivers/pci/pci-sysfs.c:rescan_store
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81588b00-ffffffff81588b17: pci_lock_rescan_remove (STB_GLOBAL)
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
