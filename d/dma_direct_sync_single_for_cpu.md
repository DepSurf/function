# Function: <code>dma_direct_sync_single_for_cpu</code>

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
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81118500)
Location: kernel/dma/direct.c:250
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81118500-ffffffff81118541: dma_direct_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122950)
Location: kernel/dma/direct.c:262
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81122950-ffffffff81122994: dma_direct_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112ed90)
Location: kernel/dma/direct.c:262
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff8112ed90-ffffffff8112edd4: dma_direct_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8113d8c0)
Location: kernel/dma/direct.c:349
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_non_isoc_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_complete_isoc_xfer_ddma
  - net/xdp/xsk_buff_pool.c:xp_dma_sync_for_cpu_slow
```
**Symbols:**

```
ffffffff8113d8c0-ffffffff8113d904: dma_direct_sync_single_for_cpu (STB_GLOBAL)
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
In kernel/dma/mapping.c (ffffffff81138226)
Location: kernel/dma/direct.h:66
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:66
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
In kernel/dma/mapping.c (ffffffff811392f6)
Location: kernel/dma/direct.h:66
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:66
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
In kernel/dma/mapping.c (ffffffff8115c183)
Location: kernel/dma/direct.h:66
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:66
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
In kernel/dma/mapping.c (ffffffff81185e8c)
Location: kernel/dma/direct.h:66
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:66
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
In kernel/dma/mapping.c (ffffffff811c187c)
Location: kernel/dma/direct.h:67
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:67
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
In kernel/dma/mapping.c (ffffffff811d42fc)
Location: kernel/dma/direct.h:67
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:67
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
In kernel/dma/mapping.c (ffffffff811e8d0c)
Location: kernel/dma/direct.h:68
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_sync_single_for_cpu
  - kernel/dma/mapping.c:dma_unmap_page_attrs
```
```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.h:68
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
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194650)
Location: kernel/dma/direct.c:262
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffff800010194650-ffff8000101946f0: dma_direct_sync_single_for_cpu (STB_GLOBAL)
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
In drivers/dma/mv_xor.c (0)
Location: include/linux/dma-mapping.h:246
Inline: True
```
```
In drivers/tty/serial/8250/8250_dma.c (0)
Location: include/linux/dma-mapping.h:246
Inline: True
```
```
In drivers/iommu/exynos-iommu.c (0)
Location: include/linux/dma-mapping.h:246
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/linux/dma-mapping.h:246
Inline: True
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (0)
Location: include/linux/dma-mapping.h:246
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/dma-mapping.h:246
Inline: True
```
```
In drivers/mmc/host/sdhci.c (0)
Location: include/linux/dma-mapping.h:246
Inline: True
```
```
In drivers/firmware/qcom_scm-32.c (0)
Location: include/linux/dma-mapping.h:246
Inline: True
```
```
In drivers/firmware/tegra/ivc.c (0)
Location: include/linux/dma-mapping.h:246
Inline: True
```
```
In drivers/staging/emxx_udc/emxx_udc.c (0)
Location: include/linux/dma-mapping.h:246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f4720)
Location: kernel/dma/direct.c:262
Inline: False
Direct callers:
  - arch/powerpc/kernel/dma-iommu.c:dma_iommu_sync_for_cpu
  - kernel/dma/direct.c:dma_direct_unmap_page
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
c0000000001f4720-c0000000001f4790: dma_direct_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe00012660c)
Location: kernel/dma/direct.c:262
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/mmc/host/mmc_spi.c:mmc_spi_command_send
```
**Symbols:**

```
ffffffe00012660c-ffffffe000126670: dma_direct_sync_single_for_cpu (STB_GLOBAL)
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
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81127370)
Location: kernel/dma/direct.c:262
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81127370-ffffffff811273b4: dma_direct_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81119dd0)
Location: kernel/dma/direct.c:262
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
```
**Symbols:**

```
ffffffff81119dd0-ffffffff81119e14: dma_direct_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81125260)
Location: kernel/dma/direct.c:262
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff81125260-ffffffff811252a4: dma_direct_sync_single_for_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dma_direct_sync_single_for_cpu(struct device *dev, dma_addr_t addr, size_t size, enum dma_data_direction dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811318a0)
Location: kernel/dma/direct.c:262
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_unmap_page
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
**Symbols:**

```
ffffffff811318a0-ffffffff811318e4: dma_direct_sync_single_for_cpu (STB_GLOBAL)
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
