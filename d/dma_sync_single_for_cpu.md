# Function: <code>dma_sync_single_for_cpu</code>

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
In drivers/tty/serial/8250/8250_dma.c (ffffffff81509d70)
Location: include/asm-generic/dma-mapping-common.h:103
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8155bd20)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168fd56)
Location: include/linux/dma-mapping.h:261
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff81588500)
Location: include/linux/dma-mapping.h:311
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bde06)
Location: include/linux/dma-mapping.h:311
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8159c988)
Location: include/linux/dma-mapping.h:354
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d1d70)
Location: include/linux/dma-mapping.h:354
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff81601c98)
Location: include/linux/dma-mapping.h:352
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173e3f0)
Location: include/linux/dma-mapping.h:352
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8163af5f)
Location: include/linux/dma-mapping.h:352
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177ed96)
Location: include/linux/dma-mapping.h:352
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff81659178)
Location: include/linux/dma-mapping.h:380
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a553e)
Location: include/linux/dma-mapping.h:380
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff8168e636)
Location: include/linux/dma-mapping.h:383
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e475a)
Location: include/linux/dma-mapping.h:383
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff816b0c06)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8181561a)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff81763fe6)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e5846)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba97b2)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dma_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811381f0)
Location: kernel/dma/mapping.c:258
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
**Symbols:**

```
ffffffff811381f0-ffffffff811382ad: dma_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dma_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811392c0)
Location: kernel/dma/mapping.c:260
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
**Symbols:**

```
ffffffff811392c0-ffffffff8113937c: dma_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dma_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115c150)
Location: kernel/dma/mapping.c:325
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
**Symbols:**

```
ffffffff8115c150-ffffffff8115c203: dma_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dma_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185e20)
Location: kernel/dma/mapping.c:321
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
**Symbols:**

```
ffffffff81185e20-ffffffff81185f1a: dma_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dma_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c1810)
Location: kernel/dma/mapping.c:328
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
**Symbols:**

```
ffffffff811c1810-ffffffff811c190a: dma_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dma_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d4290)
Location: kernel/dma/mapping.c:332
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
**Symbols:**

```
ffffffff811d4290-ffffffff811d438a: dma_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dma_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/mapping.c (0)
Location: kernel/dma/mapping.c:332
Inline: False
Direct callers:
  - drivers/virtio/virtio_ring.c:virtqueue_dma_sync_single_range_for_cpu
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
**Symbols:**

```
ffffffff821b4713-ffffffff821b472e: dma_sync_single_for_cpu.cold (STB_LOCAL)
ffffffff811e8ca0-ffffffff811e8ddb: dma_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/mv_xor.c (ffff800010807408)
Location: include/linux/dma-mapping.h:376
Inline: True
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/tty/serial/8250/8250_dma.c (ffff80001088c064)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e3048)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6dac)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e7b8)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffff800010807408-ffff800010807444: dma_sync_single_for_cpu.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dma/mv_xor.c (c0925128)
Location: include/linux/dma-mapping.h:376
Inline: True
Direct callers:
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
```
```
In drivers/tty/serial/8250/8250_dma.c (c0989a28)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/iommu/exynos-iommu.c (c09cae5c)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_unmap
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
  - drivers/iommu/exynos-iommu.c:exynos_iommu_map
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acbae0)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad6e30)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:__cpdma_chan_free
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b20878)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/mmc/host/sdhci.c (c0c22cc0)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_request_done
  - drivers/mmc/host/sdhci.c:sdhci_request_done
```
```
In drivers/firmware/qcom_scm-32.c (c0c36334)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
  - drivers/firmware/qcom_scm-32.c:qcom_scm_call
```
```
In drivers/firmware/tegra/ivc.c (c0c43ee4)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/firmware/tegra/ivc.c:tegra_ivc_notified
  - drivers/firmware/tegra/ivc.c:tegra_ivc_read_advance
  - drivers/firmware/tegra/ivc.c:tegra_ivc_read_advance
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5c05c)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_dma_unmap_single
```
**Symbols:**

```
c0925128-c092516c: dma_sync_single_for_cpu.constprop.0 (STB_LOCAL)
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
In drivers/tty/serial/8250/8250_dma.c (c000000000934c58)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b16340)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffe0005558a8)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066b156)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071b3b6)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_command_send
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff81676676)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cd9fa)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_dma.c (ffffffff81655756)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff816a4a46)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8180a49a)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
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
In drivers/tty/serial/8250/8250_dma.c (ffffffff816beea6)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818245aa)
Location: include/linux/dma-mapping.h:376
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
