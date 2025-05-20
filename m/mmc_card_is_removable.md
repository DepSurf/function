# Function: <code>mmc_card_is_removable</code>

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
In drivers/mmc/core/sdio.c (0)
Location: include/linux/mmc/host.h:439
Inline: True
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
In drivers/mmc/core/core.c (0)
Location: include/linux/mmc/host.h:460
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/mmc/host.h:460
Inline: True
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
In drivers/mmc/core/core.c (0)
Location: include/linux/mmc/host.h:462
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/mmc/host.h:462
Inline: True
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
In drivers/mmc/core/core.c (0)
Location: include/linux/mmc/host.h:466
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/mmc/host.h:466
Inline: True
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
In drivers/mmc/core/core.c (0)
Location: include/linux/mmc/host.h:521
Inline: True
```
```
In drivers/mmc/core/sdio.c (0)
Location: include/linux/mmc/host.h:521
Inline: True
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
In drivers/mmc/core/core.c (ffffffff818339df)
Location: include/linux/mmc/host.h:526
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff8183de04)
Location: include/linux/mmc/host.h:526
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/mmc/core/core.c (ffffffff8185f96f)
Location: include/linux/mmc/host.h:533
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff81869db4)
Location: include/linux/mmc/host.h:533
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a3503)
Location: include/linux/mmc/host.h:528
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d5883)
Location: include/linux/mmc/host.h:541
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a820f)
Location: include/linux/mmc/host.h:548
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
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
In drivers/mmc/core/core.c (ffffffff819ab401)
Location: include/linux/mmc/host.h:559
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
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
In drivers/mmc/core/core.c (ffffffff8198fd9d)
Location: include/linux/mmc/host.h:577
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff81999d57)
Location: include/linux/mmc/host.h:577
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
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
In drivers/mmc/core/core.c (ffffffff81a3b50f)
Location: include/linux/mmc/host.h:578
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_card_alternative_gpt_sector
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff81a46502)
Location: include/linux/mmc/host.h:578
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
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
In drivers/mmc/core/core.c (ffffffff81ba8470)
Location: include/linux/mmc/host.h:581
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_card_alternative_gpt_sector
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb441c)
Location: include/linux/mmc/host.h:581
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
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
In drivers/mmc/core/core.c (ffffffff81d4acc0)
Location: include/linux/mmc/host.h:601
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_card_alternative_gpt_sector
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff81d58a8c)
Location: include/linux/mmc/host.h:601
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
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
In drivers/mmc/core/core.c (ffffffff81db5530)
Location: include/linux/mmc/host.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_card_alternative_gpt_sector
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc341c)
Location: include/linux/mmc/host.h:605
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
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
In drivers/mmc/core/core.c (ffffffff81e6d980)
Location: include/linux/mmc/host.h:612
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_card_alternative_gpt_sector
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/bus.c (ffffffff81e6e535)
Location: include/linux/mmc/host.h:612
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_add_card
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7bcfc)
Location: include/linux/mmc/host.h:612
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2f26c)
Location: include/linux/mmc/host.h:541
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
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
In drivers/mmc/core/core.c (c0c0a654)
Location: include/linux/mmc/host.h:541
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/host/sdhci.c (c0c24574)
Location: include/linux/mmc/host.h:541
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/sdhci.c:sdhci_suspend_host
  - drivers/mmc/host/sdhci.c:sdhci_get_cd
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c28cfc)
Location: include/linux/mmc/host.h:541
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000708a08)
Location: include/linux/mmc/host.h:541
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81879243)
Location: include/linux/mmc/host.h:541
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818ca6e3)
Location: include/linux/mmc/host.h:541
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e7203)
Location: include/linux/mmc/host.h:541
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
</details>
</li>
</ul>

## Differences
