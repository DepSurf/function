# Function: <code>dma_direct_unmap_page</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118680)
Location: kernel/dma/direct.c:285
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
```
**Symbols:**

```
ffffffff81118680-ffffffff811186fd: dma_direct_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122ac0)
Location: kernel/dma/direct.c:299
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/iommu/intel-iommu.c:intel_unmap_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff81122ac0-ffffffff81122b37: dma_direct_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112ef00)
Location: kernel/dma/direct.c:299
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/iommu/intel-iommu.c:intel_unmap_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff8112ef00-ffffffff8112ef7a: dma_direct_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113da30)
Location: kernel/dma/direct.c:386
Inline: True
Direct callers:
  - kernel/dma/direct.c:dma_direct_map_sg
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_xfercomp_isoc_split_in
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_alloc
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:page_pool_release_page
```
**Symbols:**

```
ffffffff8113da30-ffffffff8113daaa: dma_direct_unmap_page (STB_GLOBAL)
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
In kernel/dma/mapping.c (ffffffff81137fcb)
Location: kernel/dma/direct.h:108
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811391fe)
Location: kernel/dma/direct.h:108
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
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
In kernel/dma/mapping.c (ffffffff8113908b)
Location: kernel/dma/direct.h:108
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8113a2ce)
Location: kernel/dma/direct.h:108
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
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
In kernel/dma/mapping.c (ffffffff8115bf1b)
Location: kernel/dma/direct.h:108
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff8115d35d)
Location: kernel/dma/direct.h:108
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
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
In kernel/dma/mapping.c (ffffffff81185bb5)
Location: kernel/dma/direct.h:108
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811871fd)
Location: kernel/dma/direct.h:108
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
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
In kernel/dma/mapping.c (ffffffff811c1585)
Location: kernel/dma/direct.h:114
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811c2d35)
Location: kernel/dma/direct.h:114
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
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
In kernel/dma/mapping.c (ffffffff811d4005)
Location: kernel/dma/direct.h:115
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811d5875)
Location: kernel/dma/direct.h:115
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
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
In kernel/dma/mapping.c (ffffffff811e902f)
Location: kernel/dma/direct.h:116
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (ffffffff811ea7a9)
Location: kernel/dma/direct.h:116
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
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
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff8000101947c8)
Location: kernel/dma/direct.c:299
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_free
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/tty/serial/msm_serial.c:msm_handle_tx
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/msm_serial.c:msm_stop_dma
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_domain_free
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_start_xmit
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_free_buffers
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - drivers/firmware/qcom_scm-64.c:qcom_scm_call
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffff8000101947c8-ffff80001019486c: dma_direct_unmap_page (STB_GLOBAL)
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
In mm/hmm.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/iommu/omap-iommu.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/iommu/tegra-smmu.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/iommu/exynos-iommu.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/usb/gadget/udc/core.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/i2c/busses/i2c-imx.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/firmware/qcom_scm-32.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/firmware/tegra/ivc.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In drivers/staging/emxx_udc/emxx_udc.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/dma-mapping.h:237
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f49b0)
Location: kernel/dma/direct.c:299
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_unmap_page
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
c0000000001f49b0-c0000000001f4a98: dma_direct_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126794)
Location: kernel/dma/direct.c:299
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - drivers/mmc/host/mmc_spi.c:mmc_spi_remove
  - drivers/mmc/host/mmc_spi.c:mmc_spi_remove
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffe000126794-ffffffe00012681c: dma_direct_unmap_page (STB_GLOBAL)
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
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811274e0)
Location: kernel/dma/direct.c:299
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/iommu/intel-iommu.c:intel_unmap_page
  - drivers/nvme/host/pci.c:nvme_pci_complete_rq
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff811274e0-ffffffff8112755a: dma_direct_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81119f40)
Location: kernel/dma/direct.c:299
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/iommu/intel-iommu.c:intel_unmap_page
  - drivers/nvme/host/pci.c:nvme_pci_complete_rq
  - drivers/nvme/host/pci.c:nvme_unmap_data
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff81119f40-ffffffff81119fba: dma_direct_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811253d0)
Location: kernel/dma/direct.c:299
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/iommu/intel-iommu.c:intel_unmap_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_check_cmd_completion
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff811253d0-ffffffff8112544a: dma_direct_unmap_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_direct_unmap_page(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131a10)
Location: kernel/dma/direct.c:299
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_sg
  - mm/hmm.c:hmm_range_dma_unmap
  - mm/hmm.c:hmm_range_dma_map
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/dma/dmaengine.c:dmaengine_unmap
  - drivers/virtio/virtio_ring.c:detach_buf_packed
  - drivers/tty/serial/8250/8250_dma.c:serial8250_release_dma
  - drivers/char/agp/intel-gtt.c:intel_gtt_teardown_scratch_page
  - drivers/iommu/intel-iommu.c:intel_unmap_page
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_for_dma
  - drivers/usb/core/hcd.c:usb_hcd_unmap_urb_setup_for_dma
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_xfercomp_intr
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_desc_list_free
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_giveback
  - net/core/page_pool.c:__page_pool_clean_page
```
**Symbols:**

```
ffffffff81131a10-ffffffff81131a8a: dma_direct_unmap_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
