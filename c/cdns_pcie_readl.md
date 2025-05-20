# Function: <code>cdns_pcie_readl</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071d784)
Location: drivers/pci/controller/pcie-cadence.h:257
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e624)
Location: drivers/pci/controller/pcie-cadence.h:257
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
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
In drivers/pci/controller/pcie-cadence-host.c (c08a6790)
Location: drivers/pci/controller/pcie-cadence.h:257
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a6f8c)
Location: drivers/pci/controller/pcie-cadence.h:257
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
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
In drivers/pci/controller/pcie-cadence-host.c (c00000000088e6a0)
Location: drivers/pci/controller/pcie-cadence.h:257
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f9dc)
Location: drivers/pci/controller/pcie-cadence.h:257
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
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
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e4472)
Location: drivers/pci/controller/pcie-cadence.h:257
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e4d30)
Location: drivers/pci/controller/pcie-cadence.h:257
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
```
</details>
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
