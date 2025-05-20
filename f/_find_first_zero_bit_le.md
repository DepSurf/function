# Function: <code>_find_first_zero_bit_le</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - lib/sbitmap.c:sbitmap_any_bit_clear
  - drivers/irqchip/irq-meson-gpio.c:meson_gpio_irq_domain_alloc
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_epf_link
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_map_addr
  - drivers/pci/controller/pci-tegra.c:tegra_msi_setup_irq
  - drivers/pci/controller/pcie-rcar.c:rcar_msi_setup_irq
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_msi_setup_irq
  - drivers/pci/controller/pcie-altera-msi.c:altera_irq_domain_alloc
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_map_addr
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_irq_domain_alloc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_map_addr
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_set_bar
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_route_allocate
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/char/misc.c:misc_register
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_attach_device
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/scsi/sr.c:sr_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_get_init
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_alloc_bit
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/dev.c:dev_alloc_name_ns
  - lib/idr.c:ida_alloc_range
```
**Symbols:**

```
c0e7d548-c0e7d574: _find_first_zero_bit_le (STB_GLOBAL)
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
