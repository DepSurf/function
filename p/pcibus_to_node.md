# Function: <code>pcibus_to_node</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pcibus_to_node(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/pci.c (ffff8000100a7958)
Location: arch/arm64/kernel/pci.c:59
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
**Symbols:**

```
ffff8000100a7958-ffff8000100a7980: pcibus_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pcibus_to_node(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/pci_64.c (c000000000069a10)
Location: arch/powerpc/kernel/pci_64.c:263
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
  - drivers/pci/probe.c:pci_device_add
  - drivers/pci/probe.c:pci_register_host_bridge
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
**Symbols:**

```
c000000000069a10-c000000000069a24: pcibus_to_node (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
