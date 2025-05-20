# Function: <code>pci_unlock_rescan_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81430070)
Location: drivers/pci/probe.c:2382
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81430070-ffffffff81430087: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147b7d0)
Location: drivers/pci/probe.c:2422
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8147b7d0-ffffffff8147b7e7: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149cce0)
Location: drivers/pci/probe.c:2500
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8149cce0-ffffffff8149ccf7: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a6bf0)
Location: drivers/pci/probe.c:2647
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff814a6bf0-ffffffff814a6c07: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e53d0)
Location: drivers/pci/probe.c:2874
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff814e53d0-ffffffff814e53e7: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81514910)
Location: drivers/pci/probe.c:3091
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81514910-ffffffff81514927: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152a120)
Location: drivers/pci/probe.c:3217
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8152a120-ffffffff8152a137: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81559850)
Location: drivers/pci/probe.c:3441
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81559850-ffffffff81559867: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157a8f0)
Location: drivers/pci/probe.c:3175
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8157a8f0-ffffffff8157a907: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8161fd40)
Location: drivers/pci/probe.c:3227
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8161fd40-ffffffff8161fd57: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81646490)
Location: drivers/pci/probe.c:3235
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81646490-ffffffff816464a7: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816290a0)
Location: drivers/pci/probe.c:3279
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff816290a0-ffffffff816290b7: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81698a50)
Location: drivers/pci/probe.c:3321
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81698a50-ffffffff81698a67: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817b9ff0)
Location: drivers/pci/probe.c:3292
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff817b9ff0-ffffffff817ba00d: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d4ea0)
Location: drivers/pci/probe.c:3302
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff818d4ea0-ffffffff818d4ebd: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81917f50)
Location: drivers/pci/probe.c:3316
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff81917f50-ffffffff81917f6d: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81960560)
Location: drivers/pci/probe.c:3365
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81960560-ffffffff8196057d: pci_unlock_rescan_remove (STB_GLOBAL)
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
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106dd348)
Location: drivers/pci/probe.c:3175
Inline: False
Direct callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
  - drivers/pci/pci-sysfs.c:bus_rescan_store
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/pci/controller/pci-host-common.c:pci_host_common_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffff8000106dd348-ffff8000106dd370: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0878e44)
Location: drivers/pci/probe.c:3175
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
c0878e44-c0878e68: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008554b0)
Location: drivers/pci/probe.c:3175
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
c0000000008554b0-c0000000008554ec: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b5682)
Location: drivers/pci/probe.c:3175
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
ffffffe0004b5682-ffffffe0004b56ac: pci_unlock_rescan_remove (STB_GLOBAL)
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
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156ee10)
Location: drivers/pci/probe.c:3175
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8156ee10-ffffffff8156ee27: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155d570)
Location: drivers/pci/probe.c:3175
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8155d570-ffffffff8155d587: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156e640)
Location: drivers/pci/probe.c:3175
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8156e640-ffffffff8156e657: pci_unlock_rescan_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_unlock_rescan_remove();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81588b20)
Location: drivers/pci/probe.c:3175
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
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_check_host_bridge
  - drivers/acpi/pci_root.c:acpi_pci_root_remove
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81588b20-ffffffff81588b37: pci_unlock_rescan_remove (STB_GLOBAL)
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
