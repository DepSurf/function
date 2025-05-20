# Function: <code>pci_assign_unassigned_bridge_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81440600)
Location: drivers/pci/setup-bus.c:1787
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
**Symbols:**

```
ffffffff81440600-ffffffff8144089d: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148c4e0)
Location: drivers/pci/setup-bus.c:1859
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
**Symbols:**

```
ffffffff8148c4e0-ffffffff8148c7a9: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814adcd0)
Location: drivers/pci/setup-bus.c:1865
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
**Symbols:**

```
ffffffff814adcd0-ffffffff814adf99: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b8070)
Location: drivers/pci/setup-bus.c:1856
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
**Symbols:**

```
ffffffff814b8070-ffffffff814b8336: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f82b0)
Location: drivers/pci/setup-bus.c:2026
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
```
**Symbols:**

```
ffffffff814f82b0-ffffffff814f84d6: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2021
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8152956b-ffffffff81529675: pci_assign_unassigned_bridge_resources.cold.19 (STB_LOCAL)
ffffffff81528e10-ffffffff81528f1e: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2023
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8153f41e-ffffffff8153f528: pci_assign_unassigned_bridge_resources.cold.18 (STB_LOCAL)
ffffffff8153ecb0-ffffffff8153edbe: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1991
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff8156eaf5-ffffffff8156ec23: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff8156e110-ffffffff8156e214: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1997
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8158fac8-ffffffff8158fc18: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff8158f0f0-ffffffff8158f1f4: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2049
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff81637601-ffffffff81637743: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff81636b60-ffffffff81636c1b: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2050
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff81bf8a6a-ffffffff81bf8bac: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff8165bc20-ffffffff8165bcdb: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2050
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff81bea8c4-ffffffff81beaa06: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff8163e1c0-ffffffff8163e27b: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2050
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff81ce5746-ffffffff81ce5888: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff816aed20-ffffffff816aeddb: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2050
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff81eac216-ffffffff81eac357: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff817d21a0-ffffffff817d2269: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818f2650)
Location: drivers/pci/setup-bus.c:2154
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff818f2650-ffffffff818f28ac: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81935a70)
Location: drivers/pci/setup-bus.c:2145
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
```
**Symbols:**

```
ffffffff81935a70-ffffffff81935ccc: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197e820)
Location: drivers/pci/setup-bus.c:2155
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8197e820-ffffffff8197ea7c: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
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
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f4430)
Location: drivers/pci/setup-bus.c:1997
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffff8000106f4430-ffff8000106f4688: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088eeac)
Location: drivers/pci/setup-bus.c:1997
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
```
**Symbols:**

```
c088eeac-c088f108: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c000000000872b30)
Location: drivers/pci/setup-bus.c:1997
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_finish_adding_to_bus
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
```
**Symbols:**

```
c000000000872b30-c000000000872df0: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c757a)
Location: drivers/pci/setup-bus.c:1997
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffe0004c757a-ffffffe0004c7768: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1997
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8158394c-ffffffff81583a9c: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff81582f70-ffffffff81583074: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1997
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff81572728-ffffffff81572878: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff81571d50-ffffffff81571e54: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1997
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff81583818-ffffffff81583968: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff81582e40-ffffffff81582f44: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_bridge_resources(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1997
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_rescan_bus_bridge_resize
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_configure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_configure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_configure_device
```
**Symbols:**

```
ffffffff8159dcc8-ffffffff8159de18: pci_assign_unassigned_bridge_resources.cold (STB_LOCAL)
ffffffff8159d2f0-ffffffff8159d3f4: pci_assign_unassigned_bridge_resources (STB_GLOBAL)
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
