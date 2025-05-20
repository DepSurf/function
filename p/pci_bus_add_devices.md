# Function: <code>pci_bus_add_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8142f5a0)
Location: drivers/pci/bus.c:306
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8142f5a0-ffffffff8142f614: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8147af60)
Location: drivers/pci/bus.c:344
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8147af60-ffffffff8147afd4: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8149c3e0)
Location: drivers/pci/bus.c:344
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8149c3e0-ffffffff8149c454: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814a6190)
Location: drivers/pci/bus.c:344
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff814a6190-ffffffff814a61fc: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff814e4fd0)
Location: drivers/pci/bus.c:344
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff814e4fd0-ffffffff814e503c: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff815144b0)
Location: drivers/pci/bus.c:343
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff815144b0-ffffffff8151451a: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81529c10)
Location: drivers/pci/bus.c:343
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81529c10-ffffffff81529c7a: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81558e10)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81558e10-ffffffff81558e7a: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8157a3b0)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8157a3b0-ffffffff8157a41a: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8161f4c0)
Location: drivers/pci/bus.c:338
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8161f4c0-ffffffff8161f52a: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81645cb0)
Location: drivers/pci/bus.c:338
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81645cb0-ffffffff81645d1a: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff816289f0)
Location: drivers/pci/bus.c:338
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff816289f0-ffffffff81628a5a: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81698370)
Location: drivers/pci/bus.c:338
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff81698370-ffffffff816983da: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff817b9660)
Location: drivers/pci/bus.c:338
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff817b9660-ffffffff817b96d2: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff818d4280)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff818d4280-ffffffff818d42f2: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff819174d0)
Location: drivers/pci/bus.c:364
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff819174d0-ffffffff81917542: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8195f5e0)
Location: drivers/pci/bus.c:366
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8195f5e0-ffffffff8195f652: pci_bus_add_devices (STB_GLOBAL)
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
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffff8000106dccf8)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffff8000106dccf8-ffff8000106dcd80: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c08788d0)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - arch/arm/kernel/bios32.c:pci_common_init_dev
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_enable
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
c08788d0-c0878950: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (c000000000854e40)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci_64.c:pcibios_init
  - arch/powerpc/kernel/pci-common.c:pcibios_finish_adding_to_bus
  - arch/powerpc/kernel/pci-common.c:pcibios_finish_adding_to_bus
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
**Symbols:**

```
c000000000854e40-c000000000854ef0: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffe0004b516a)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init
```
**Symbols:**

```
ffffffe0004b516a-ffffffe0004b51e8: pci_bus_add_devices (STB_GLOBAL)
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
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8156e8c0)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8156e8c0-ffffffff8156e92a: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8155d030)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8155d030-ffffffff8155d09a: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8156e100)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff8156e100-ffffffff8156e16a: pci_bus_add_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_bus_add_devices(const struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff815885e0)
Location: drivers/pci/bus.c:342
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_devices
  - drivers/pci/probe.c:pci_rescan_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - arch/x86/pci/common.c:pcibios_scan_root
```
**Symbols:**

```
ffffffff815885e0-ffffffff8158864a: pci_bus_add_devices (STB_GLOBAL)
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
