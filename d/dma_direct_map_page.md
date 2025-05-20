# Function: <code>dma_direct_map_page</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8110d040)
Location: kernel/dma/direct.c:138
Inline: False
```
**Symbols:**

```
ffffffff8110d040-ffffffff8110d093: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118770)
Location: kernel/dma/direct.c:318
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81118770-ffffffff811188c9: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122c10)
Location: kernel/dma/direct.c:332
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - mm/hmm.c:hmm_range_dma_map
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81122c10-ffffffff81122cfa: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f050)
Location: kernel/dma/direct.c:332
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - mm/hmm.c:hmm_range_dma_map
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff8112f050-ffffffff8112f13a: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113dab0)
Location: kernel/dma/direct.c:412
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_setup_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_alloc_split_dma_aligned_buf
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-ring.c:xhci_align_td
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff8113dab0-ffffffff8113dbea: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81137d90)
Location: kernel/dma/direct.h:83
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8113941f)
Location: kernel/dma/direct.h:83
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff81137d90-ffffffff81137f2a: dma_direct_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138e50)
Location: kernel/dma/direct.h:83
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8113a50f)
Location: kernel/dma/direct.h:83
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff81138e50-ffffffff81138fed: dma_direct_map_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/direct.h:83
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:83
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff8115bca0-ffffffff8115be74: dma_direct_map_page (STB_LOCAL)
ffffffff81cb0300-ffffffff81cb0340: dma_direct_map_page.cold (STB_LOCAL)
ffffffff8115c380-ffffffff8115c554: dma_direct_map_page (STB_LOCAL)
ffffffff81cb0340-ffffffff81cb0380: dma_direct_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/direct.h:83
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:83
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff81185890-ffffffff81185a8b: dma_direct_map_page (STB_LOCAL)
ffffffff81e60fa0-ffffffff81e60fe1: dma_direct_map_page.cold (STB_LOCAL)
ffffffff811860b0-ffffffff811862ab: dma_direct_map_page (STB_LOCAL)
ffffffff81e60fe1-ffffffff81e61022: dma_direct_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/direct.h:84
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:84
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff811c1200-ffffffff811c1440: dma_direct_map_page (STB_LOCAL)
ffffffff8205a725-ffffffff8205a766: dma_direct_map_page.cold (STB_LOCAL)
ffffffff811c1a50-ffffffff811c1c90: dma_direct_map_page (STB_LOCAL)
ffffffff8205a766-ffffffff8205a7a7: dma_direct_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/direct.h:84
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:84
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff811d3c80-ffffffff811d3ec0: dma_direct_map_page (STB_LOCAL)
ffffffff820d8f99-ffffffff820d8fda: dma_direct_map_page.cold (STB_LOCAL)
ffffffff811d4590-ffffffff811d47d0: dma_direct_map_page (STB_LOCAL)
ffffffff820d8fda-ffffffff820d901b: dma_direct_map_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/direct.h:85
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:85
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
```
**Symbols:**

```
ffffffff811e8920-ffffffff811e8b59: dma_direct_map_page (STB_LOCAL)
ffffffff821b46d2-ffffffff821b4713: dma_direct_map_page.cold (STB_LOCAL)
ffffffff811e9480-ffffffff811e96b9: dma_direct_map_page (STB_LOCAL)
ffffffff821b4787-ffffffff821b47c8: dma_direct_map_page.cold (STB_LOCAL)
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
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff8000101949b0)
Location: kernel/dma/direct.c:332
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - mm/hmm.c:hmm_range_dma_map
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/soc/fsl/qbman/qman.c:qman_init_fq
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffff8000101949b0-ffff800010194b00: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e17e0)
Location: kernel/dma/direct.c:332
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - mm/hmm.c:hmm_range_dma_map
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:iopte_alloc
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/tegra-smmu.c:tegra_smmu_map
  - drivers/iommu/tegra-smmu.c:tegra_smmu_attach_dev
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_domain_alloc
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_submit_si
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/usb/gadget/udc/core.c:usb_gadget_map_request_by_dev
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_dma_xfer
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
c03e17e0-c03e18b4: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f4c70)
Location: kernel/dma/direct.c:332
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_map_page
  - kernel/dma/direct.c:dma_direct_map_sg
  - mm/hmm.c:hmm_range_dma_map
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:ibmvtpm_interrupt
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
c0000000001f4c70-c0000000001f4dc0: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126922)
Location: kernel/dma/direct.c:332
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - mm/hmm.c:hmm_range_dma_map
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffe000126922-ffffffe0001269ea: dma_direct_map_page (STB_GLOBAL)
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
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127630)
Location: kernel/dma/direct.c:332
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - mm/hmm.c:hmm_range_dma_map
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81127630-ffffffff8112771a: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a090)
Location: kernel/dma/direct.c:332
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - mm/hmm.c:hmm_range_dma_map
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/nvme/host/pci.c:nvme_queue_rq
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/nvme/host/pci.c:nvme_map_data
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff8111a090-ffffffff8111a17a: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125520)
Location: kernel/dma/direct.c:332
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - mm/hmm.c:hmm_range_dma_map
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81125520-ffffffff8112560a: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_page(struct device *dev, struct page *page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131b60)
Location: kernel/dma/direct.c:332
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - mm/hmm.c:hmm_range_dma_map
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/tty/serial/8250/8250_dma.c:serial8250_request_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_map_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81131b60-ffffffff81131c4a: dma_direct_map_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
