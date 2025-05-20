# Function: <code>pci_find_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8143aa30)
Location: drivers/pci/search.c:131
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/iov.c:pci_enable_sriov
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8143aa30-ffffffff8143aa83: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81486960)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81486960-ffffffff814869b0: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814a8110)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff814a8110-ffffffff814a8160: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814b20e0)
Location: drivers/pci/search.c:139
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff814b20e0-ffffffff814b2130: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff814f17d0)
Location: drivers/pci/search.c:139
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff814f17d0-ffffffff814f1820: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81521a60)
Location: drivers/pci/search.c:140
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81521a60-ffffffff81521ab0: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81537890)
Location: drivers/pci/search.c:140
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81537890-ffffffff815378e0: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81567220)
Location: drivers/pci/search.c:136
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81567220-ffffffff81567270: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81588580)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81588580-ffffffff815885d0: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8162f7b0)
Location: drivers/pci/search.c:141
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8162f7b0-ffffffff8162f848: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81654e40)
Location: drivers/pci/search.c:141
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81654e40-ffffffff81654ed8: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81637980)
Location: drivers/pci/search.c:141
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81637980-ffffffff81637a5f: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff816a7c10)
Location: drivers/pci/search.c:141
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff816a7c10-ffffffff816a7cef: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff817ca6f0)
Location: drivers/pci/search.c:141
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff817ca6f0-ffffffff817ca7d6: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff818e81e0)
Location: drivers/pci/search.c:141
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff818e81e0-ffffffff818e82c6: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8192b7f0)
Location: drivers/pci/search.c:141
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8192b7f0-ffffffff8192b8d6: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81974140)
Location: drivers/pci/search.c:141
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/rcec.c:walk_rcec
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81974140-ffffffff81974226: pci_find_bus (STB_GLOBAL)
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
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffff8000106eca90)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - arch/arm64/kernel/pci.c:raw_pci_write
  - arch/arm64/kernel/pci.c:raw_pci_read
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
```
**Symbols:**

```
ffff8000106eca90-ffff8000106ecaf8: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c0887cd4)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c0887cd4-c0887d2c: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (c000000000868830)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_probe
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c000000000868830-c0000000008688c8: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffe0004c1996)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffe0004c1996-ffffffe0004c19ec: pci_find_bus (STB_GLOBAL)
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
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c410)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8157c410-ffffffff8157c460: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8156b1e0)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8156b1e0-ffffffff8156b230: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff8157c2d0)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff8157c2d0-ffffffff8157c320: pci_find_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_bus *pci_find_bus(int domain, int busnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/search.c (ffffffff81596780)
Location: drivers/pci/search.c:135
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/acpi/reboot.c:acpi_reboot
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
  - arch/x86/pci/legacy.c:pcibios_scan_specific_bus
  - arch/x86/pci/irq.c:pirq_peer_trick
```
**Symbols:**

```
ffffffff81596780-ffffffff815967d0: pci_find_bus (STB_GLOBAL)
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
