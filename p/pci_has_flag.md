# Function: <code>pci_has_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (0)
Location: include/asm-generic/pci-bridge.h:59
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:759
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
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:789
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/pci.h:789
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
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:814
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/pci.h:814
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
In drivers/pci/probe.c (0)
Location: include/linux/pci.h:840
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/pci.h:840
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
In drivers/pci/probe.c (ffffffff81518345)
Location: include/linux/pci.h:839
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff8151f42b)
Location: include/linux/pci.h:839
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
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
In drivers/pci/probe.c (ffffffff8152ddc5)
Location: include/linux/pci.h:875
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff815353de)
Location: include/linux/pci.h:875
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
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
In drivers/pci/probe.c (ffffffff8155c4f9)
Location: include/linux/pci.h:936
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff8156470b)
Location: include/linux/pci.h:936
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
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
In drivers/pci/probe.c (ffffffff8157d5c9)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff81585a1f)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
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
In drivers/pci/probe.c (ffffffff81622bb9)
Location: include/linux/pci.h:961
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff8162c640)
Location: include/linux/pci.h:961
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
In drivers/pci/probe.c (ffffffff816497b9)
Location: include/linux/pci.h:977
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff816523a0)
Location: include/linux/pci.h:977
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
In drivers/pci/probe.c (ffffffff8162c379)
Location: include/linux/pci.h:983
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff81634e55)
Location: include/linux/pci.h:983
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
In drivers/pci/probe.c (ffffffff8169b849)
Location: include/linux/pci.h:1031
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff816a4f46)
Location: include/linux/pci.h:1031
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
In drivers/pci/probe.c (ffffffff817bd039)
Location: include/linux/pci.h:1055
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff817c7470)
Location: include/linux/pci.h:1055
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
In drivers/pci/probe.c (ffffffff818d9035)
Location: include/linux/pci.h:1062
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff818e4a70)
Location: include/linux/pci.h:1062
Inline: True
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
In drivers/pci/probe.c (ffffffff8191c375)
Location: include/linux/pci.h:1067
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff819280b0)
Location: include/linux/pci.h:1067
Inline: True
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
In drivers/pci/probe.c (ffffffff819647a5)
Location: include/linux/pci.h:1090
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff81970850)
Location: include/linux/pci.h:1090
Inline: True
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
In drivers/pci/probe.c (ffff8000106e0de8)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffff8000106ea488)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/controller/pci-host-common.c (ffff800010723034)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
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
In arch/arm/kernel/bios32.c (c03116b8)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - arch/arm/kernel/bios32.c:pci_common_init_dev
```
```
In drivers/pci/probe.c (c087cb3c)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (c08853f0)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9e70)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
```
```
In drivers/pci/controller/pci-host-common.c (c08afcf4)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
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
In arch/powerpc/kernel/pci-common.c (c00000000006ca20)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_scan_phb
  - arch/powerpc/kernel/pci-common.c:pcibios_finish_adding_to_bus
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_resource_survey
  - arch/powerpc/kernel/pci-common.c:pcibios_align_resource
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
  - arch/powerpc/kernel/pci-common.c:pci_proc_domain
  - arch/powerpc/kernel/pci-common.c:pci_proc_domain
```
```
In drivers/pci/probe.c (c000000000859f78)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (c000000000865750)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/controller/pci-host-common.c (c000000000891710)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
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
In drivers/pci/probe.c (ffffffe0004b8afa)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffe0004c05c6)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
```
In drivers/pci/controller/pci-host-common.c (ffffffe0004e687c)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
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
In drivers/pci/probe.c (ffffffff81571ae9)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff81579f3f)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
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
In drivers/pci/probe.c (ffffffff81560249)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff8156867f)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
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
In drivers/pci/probe.c (ffffffff81571319)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff8157976f)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
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
In drivers/pci/probe.c (ffffffff8158b7f9)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_host_probe
  - drivers/pci/probe.c:pci_scan_slot
```
```
In drivers/pci/pci.c (ffffffff81593c04)
Location: include/linux/pci.h:938
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
```
</details>
</li>
</ul>

## Differences
