# Function: <code>dma_direct_sync_single_for_device</code>

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
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811184b0)
Location: kernel/dma/direct.c:215
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
**Symbols:**

```
ffffffff811184b0-ffffffff811184f4: dma_direct_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122900)
Location: kernel/dma/direct.c:225
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
**Symbols:**

```
ffffffff81122900-ffffffff81122947: dma_direct_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112ed40)
Location: kernel/dma/direct.c:225
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
**Symbols:**

```
ffffffff8112ed40-ffffffff8112ed87: dma_direct_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113d870)
Location: kernel/dma/direct.c:312
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_fill_host_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_device_slow
  - net/xdp/xsk_buff_pool.c:xp_alloc
```
**Symbols:**

```
ffffffff8113d870-ffffffff8113d8b7: dma_direct_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81138166)
Location: kernel/dma/direct.h:54
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81139236)
Location: kernel/dma/direct.h:54
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff8115c0c3)
Location: kernel/dma/direct.h:54
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff81185d8c)
Location: kernel/dma/direct.h:54
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811c176f)
Location: kernel/dma/direct.h:55
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811d41ef)
Location: kernel/dma/direct.h:55
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/mapping.c (ffffffff811e8e5f)
Location: kernel/dma/direct.h:56
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_device
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
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff8000101944b0)
Location: kernel/dma/direct.c:225
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/iommu/rockchip-iommu.c:rk_iommu_map
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
**Symbols:**

```
ffff8000101944b0-ffff800010194568: dma_direct_sync_single_for_device (STB_GLOBAL)
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
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/iommu/omap-iommu.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/iommu/tegra-smmu.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/iommu/exynos-iommu.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/mmc/host/sdhci.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/firmware/tegra/ivc.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
```
In drivers/staging/emxx_udc/emxx_udc.c (0)
Location: include/linux/dma-mapping.h:215
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f46b0)
Location: kernel/dma/direct.c:225
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_for_device
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
**Symbols:**

```
c0000000001f46b0-c0000000001f4720: dma_direct_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe0001265a8)
Location: kernel/dma/direct.c:225
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
  - drivers/mmc/host/mmc_spi.c:mmc_spi_command_send
```
**Symbols:**

```
ffffffe0001265a8-ffffffe00012660c: dma_direct_sync_single_for_device (STB_GLOBAL)
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
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127320)
Location: kernel/dma/direct.c:225
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
**Symbols:**

```
ffffffff81127320-ffffffff81127367: dma_direct_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81119d80)
Location: kernel/dma/direct.c:225
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
```
**Symbols:**

```
ffffffff81119d80-ffffffff81119dc7: dma_direct_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125210)
Location: kernel/dma/direct.c:225
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
**Symbols:**

```
ffffffff81125210-ffffffff81125257: dma_direct_sync_single_for_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_direct_sync_single_for_device(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131850)
Location: kernel/dma/direct.c:225
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:serial8250_tx_dma
  - drivers/usb/dwc2/hcd.c:dwc2_hc_start_transfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_init_non_isoc_dma_desc
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_update_frame_list
```
**Symbols:**

```
ffffffff81131850-ffffffff81131897: dma_direct_sync_single_for_device (STB_GLOBAL)
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
