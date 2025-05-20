# Function: <code>rockchip_pcie_write</code>

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
In drivers/pci/controller/pcie-rockchip.c (ffff8000107282f4)
Location: drivers/pci/controller/pcie-rockchip.h:323
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff800010729678)
Location: drivers/pci/controller/pcie-rockchip.h:323
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_start
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_msi
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
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
In drivers/pci/controller/pcie-rockchip.c (c08b35fc)
Location: drivers/pci/controller/pcie-rockchip.h:323
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_cfg_configuration_accesses
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_init_port
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (c08b448c)
Location: drivers/pci/controller/pcie-rockchip.h:323
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_start
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_msi
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_unmap_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_clear_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_write_header
```
</details>
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
