# Function: <code>devm_free_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff810defb0)
Location: kernel/irq/devres.c:131
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
```
**Symbols:**

```
ffffffff810defb0-ffffffff810df030: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff810e4910)
Location: kernel/irq/devres.c:131
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff810e4910-ffffffff810e4990: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff810eb180)
Location: kernel/irq/devres.c:131
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff810eb180-ffffffff810eb200: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff810ea870)
Location: kernel/irq/devres.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff810ea870-ffffffff810ea8e1: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff810f2dc0)
Location: kernel/irq/devres.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff810f2dc0-ffffffff810f2e31: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff810fb190)
Location: kernel/irq/devres.c:141
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff810fb190-ffffffff810fb201: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81106950)
Location: kernel/irq/devres.c:141
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81106950-ffffffff811069c1: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/devres.c (0)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/ata/libata-core.c:ata_host_activate
```
**Symbols:**

```
ffffffff8111019f-ffffffff811101b2: devm_free_irq.cold (STB_LOCAL)
ffffffff8110ff10-ffffffff8110ff85: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff8111c190)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8111c190-ffffffff8111c205: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811284c0)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:disable_interrupts
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
```
**Symbols:**

```
ffffffff811284c0-ffffffff81128535: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81123e00)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:disable_interrupts
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
```
**Symbols:**

```
ffffffff81123e00-ffffffff81123e75: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81124150)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:disable_interrupts
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
```
**Symbols:**

```
ffffffff81124150-ffffffff811241c5: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81144750)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:disable_interrupts
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
```
**Symbols:**

```
ffffffff81144750-ffffffff811447c5: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81168660)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:disable_interrupts
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
```
**Symbols:**

```
ffffffff81168660-ffffffff811686e6: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff8119cde0)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:disable_interrupts
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
```
**Symbols:**

```
ffffffff8119cde0-ffffffff8119ce66: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811aec60)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_free_irq_func
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/mailbox/pcc.c:pcc_shutdown
```
**Symbols:**

```
ffffffff811aec60-ffffffff811aece6: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff811be860)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_free_irq_func
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/mailbox/pcc.c:pcc_shutdown
```
**Symbols:**

```
ffffffff811be860-ffffffff811be8e6: devm_free_irq (STB_GLOBAL)
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
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffff8000101807f0)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_shutdown
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_shutdown
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/iommu/arm-smmu.c:arm_smmu_domain_free
  - drivers/iommu/rockchip-iommu.c:rk_iommu_shutdown
  - drivers/mailbox/pcc.c:pcc_mbox_free_channel
```
**Symbols:**

```
ffff8000101807f0-ffff800010180888: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (c03d0638)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/dma/ti/edma.c:edma_remove
  - drivers/dma/ti/edma.c:edma_remove
  - drivers/dma/ti/omap-dma.c:omap_dma_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_shutdown
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_shutdown
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_shutdown
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_startup
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/iommu/rockchip-iommu.c:rk_iommu_shutdown
```
**Symbols:**

```
c03d0638-c03d06dc: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (c0000000001db380)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/ata/libata-core.c:ata_host_activate
```
**Symbols:**

```
c0000000001db380-c0000000001db430: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffe00011880e)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffe00011880e-ffffffe000118872: devm_free_irq (STB_GLOBAL)
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
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81114770)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81114770-ffffffff811147e5: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81105480)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81105480-ffffffff811054f5: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff81112660)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff81112660-ffffffff811126d5: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devm_free_irq(struct device *dev, unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/devres.c (ffffffff8111dc80)
Location: kernel/irq/devres.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
```
**Symbols:**

```
ffffffff8111dc80-ffffffff8111dcf5: devm_free_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
