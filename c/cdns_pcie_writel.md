# Function: <code>cdns_pcie_writel</code>

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
In drivers/pci/controller/pcie-cadence.c (ffff80001071d22c)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071da68)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e308)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_start
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
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
In drivers/pci/controller/pcie-cadence.c (c08a62e0)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a6a8c)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a7510)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_start
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
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
In drivers/pci/controller/pcie-cadence.c (c00000000088deec)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088ea8c)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f724)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_start
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
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
In drivers/pci/controller/pcie-cadence.c (ffffffe0004e401a)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_reset_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region_for_normal_msg
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e4794)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pci_map_bus
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e5500)
Location: drivers/pci/controller/pcie-cadence.h:252
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_start
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_write_header
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
