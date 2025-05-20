# Function: <code>__pcibus_to_node</code>

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
In arch/x86/kernel/quirks.c (ffffffff81035755)
Location: arch/x86/include/asm/pci.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff81431595)
Location: arch/x86/include/asm/pci.h:131
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_create_root_bus
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143ba56)
Location: arch/x86/include/asm/pci.h:131
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff81034951)
Location: arch/x86/include/asm/pci.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8147da38)
Location: arch/x86/include/asm/pci.h:128
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/pci/pci-sysfs.c (ffffffff814878e6)
Location: arch/x86/include/asm/pci.h:128
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff81034591)
Location: arch/x86/include/asm/pci.h:142
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8149e218)
Location: arch/x86/include/asm/pci.h:142
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a90c6)
Location: arch/x86/include/asm/pci.h:142
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff8103261d)
Location: arch/x86/include/asm/pci.h:135
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff814a8146)
Location: arch/x86/include/asm/pci.h:135
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b2826)
Location: arch/x86/include/asm/pci.h:135
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff81034951)
Location: arch/x86/include/asm/pci.h:134
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff814e7186)
Location: arch/x86/include/asm/pci.h:134
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f1f16)
Location: arch/x86/include/asm/pci.h:134
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff8103595d)
Location: arch/x86/include/asm/pci.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8151679b)
Location: arch/x86/include/asm/pci.h:131
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff815221b5)
Location: arch/x86/include/asm/pci.h:131
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff81036b3d)
Location: arch/x86/include/asm/pci.h:131
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8152c1ab)
Location: arch/x86/include/asm/pci.h:131
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff81537fe5)
Location: arch/x86/include/asm/pci.h:131
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff81038b7d)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8155ab8b)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff815679d5)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff8103934d)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8157bc1b)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff81588ca5)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff8103c14d)
Location: arch/x86/include/asm/pci.h:124
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff81621428)
Location: arch/x86/include/asm/pci.h:124
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff8162fc15)
Location: arch/x86/include/asm/pci.h:124
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff8103c8ad)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff81647fa8)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff816552a5)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020ea4)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810221f8)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/quirks.c (ffffffff8103e0dd)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8162ab38)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff81637ed5)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024a84)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81025d68)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/quirks.c (ffffffff81043d8d)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8169a018)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a8145)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81026bec)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029dc9)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/quirks.c (ffffffff8104bf04)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff817bb658)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cace5)
Location: arch/x86/include/asm/pci.h:113
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102ddff)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030889)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/quirks.c (ffffffff810581e4)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff818d7158)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e8885)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/events/intel/uncore.c (ffffffff810247e5)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8103099e)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/quirks.c (ffffffff81059384)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8191a3d8)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192be95)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/events/intel/uncore.c (ffffffff8102a915)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036c6e)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
```
```
In arch/x86/kernel/quirks.c (ffffffff810605a4)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff819627d8)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff81974785)
Location: arch/x86/include/asm/pci.h:111
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In arch/x86/kernel/quirks.c (ffffffff810394ad)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8157013b)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157cb35)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff81028dbd)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8155e89b)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156b905)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff8103930d)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff8156f96b)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157c9f5)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
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
In arch/x86/kernel/quirks.c (ffffffff8103a30d)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In drivers/pci/probe.c (ffffffff81589e4b)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/pci-sysfs.c (ffffffff81596ea5)
Location: arch/x86/include/asm/pci.h:132
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
</details>
</li>
</ul>

## Differences
