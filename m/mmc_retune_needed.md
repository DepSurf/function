# Function: <code>mmc_retune_needed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bd921)
Location: include/linux/mmc/host.h:506
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff816c1c46)
Location: include/linux/mmc/host.h:506
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff816c8a35)
Location: include/linux/mmc/host.h:506
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff8171f5d4)
Location: include/linux/mmc/host.h:532
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff817248d6)
Location: include/linux/mmc/host.h:532
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff8172b9e5)
Location: include/linux/mmc/host.h:532
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff817542aa)
Location: include/linux/mmc/host.h:529
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff81757856)
Location: include/linux/mmc/host.h:529
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff8175eab5)
Location: include/linux/mmc/host.h:529
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff81771fa7)
Location: include/linux/mmc/host.h:497
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff817756d6)
Location: include/linux/mmc/host.h:497
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff8177d255)
Location: include/linux/mmc/host.h:497
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff817e7aaf)
Location: include/linux/mmc/host.h:552
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff817eb9e5)
Location: include/linux/mmc/host.h:552
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff817f37d7)
Location: include/linux/mmc/host.h:552
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff818311d9)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff81834bb5)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff8183cc37)
Location: include/linux/mmc/host.h:557
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff8185d459)
Location: include/linux/mmc/host.h:564
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff81860b65)
Location: include/linux/mmc/host.h:564
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff81868bc7)
Location: include/linux/mmc/host.h:564
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff818a10d5)
Location: include/linux/mmc/host.h:559
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff818a48b5)
Location: include/linux/mmc/host.h:559
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff818acb18)
Location: include/linux/mmc/host.h:559
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff818d33c5)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff818d6d35)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff818def61)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff819a5a67)
Location: include/linux/mmc/host.h:579
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff819a9695)
Location: include/linux/mmc/host.h:579
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff819b2761)
Location: include/linux/mmc/host.h:579
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff819a887d)
Location: include/linux/mmc/host.h:590
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff819ac275)
Location: include/linux/mmc/host.h:590
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff819b4c89)
Location: include/linux/mmc/host.h:590
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff8198d54d)
Location: include/linux/mmc/host.h:608
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff819906e5)
Location: include/linux/mmc/host.h:608
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff81999169)
Location: include/linux/mmc/host.h:608
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff81a38b94)
Location: include/linux/mmc/host.h:609
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff81a3bfd5)
Location: include/linux/mmc/host.h:609
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff81a458d9)
Location: include/linux/mmc/host.h:609
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff81ba5be6)
Location: include/linux/mmc/host.h:612
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff81ba8ff5)
Location: include/linux/mmc/host.h:612
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb362f)
Location: include/linux/mmc/host.h:612
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff81d47ef6)
Location: include/linux/mmc/host.h:632
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff81d4bc85)
Location: include/linux/mmc/host.h:632
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff81d57b9f)
Location: include/linux/mmc/host.h:632
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff81db2773)
Location: include/linux/mmc/host.h:636
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff81db6525)
Location: include/linux/mmc/host.h:636
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc253e)
Location: include/linux/mmc/host.h:636
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff81e6ab03)
Location: include/linux/mmc/host.h:643
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff81e6e9c5)
Location: include/linux/mmc/host.h:643
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7adfe)
Location: include/linux/mmc/host.h:643
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
</details>
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
In drivers/mmc/core/core.c (ffff800010b2c4f4)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffff800010b30db0)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffff800010b3911c)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (c0c07afc)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (c0c0bb18)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (c0c13a54)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/host/sdhci.c (c0c287e4)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_irq
```
```
In drivers/mmc/host/sdhci-pltfm.c (c0c2d050)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_suspend
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2f0bc)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_suspend
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
In drivers/mmc/core/core.c (c000000000c25510)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (c000000000c2a908)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (c000000000c3523c)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffe000706894)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffe00070985a)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffe000710df4)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff81876d85)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff8187a6f5)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff81882921)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c8225)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff818cbb95)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff818d3dc1)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
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
In drivers/mmc/core/core.c (ffffffff818e4d16)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_request_done
  - drivers/mmc/core/core.c:mmc_request_done
```
```
In drivers/mmc/core/host.c (ffffffff818e86b5)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_timer
```
```
In drivers/mmc/core/sdio.c (ffffffff818f08e1)
Location: include/linux/mmc/host.h:572
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
</details>
</li>
</ul>

## Differences
