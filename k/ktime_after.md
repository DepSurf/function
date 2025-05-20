# Function: <code>ktime_after</code>

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
In drivers/md/dm.c (ffffffff816a3e04)
Location: include/linux/ktime.h:151
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_request_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170f532)
Location: include/linux/ktime.h:151
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In drivers/acpi/button.c (ffffffff8151cf58)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815251f9)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/md/dm-rq.c (ffffffff8174151a)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In drivers/acpi/button.c (ffffffff8152d7d9)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81537af8)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/md/dm-rq.c (ffffffff8175b4d3)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In drivers/acpi/button.c (ffffffff8158e649)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159935d)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/md/dm-rq.c (ffffffff817cd726)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In drivers/acpi/button.c (ffffffff815c598b)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ee9ef)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/dm-rq.c (ffffffff818164c9)
Location: include/linux/ktime.h:125
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In drivers/acpi/button.c (ffffffff815def4b)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181a8bf)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
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
In drivers/acpi/button.c (ffffffff81610a53)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185cd14)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81863884)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff81631f03)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188eb24)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff818955cf)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff816def92)
Location: include/linux/ktime.h:110
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d7c4)
Location: include/linux/ktime.h:110
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81965bef)
Location: include/linux/ktime.h:110
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff816fcfb2)
Location: include/linux/ktime.h:111
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81964174)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff8196c6f0)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff816ded6d)
Location: include/linux/ktime.h:111
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81948594)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff819516b0)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff81756f0d)
Location: include/linux/ktime.h:111
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed23f)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff819f6bf0)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff8188a0ab)
Location: include/linux/ktime.h:111
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b53b57)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81b55793)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff819d0a8f)
Location: include/linux/ktime.h:111
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81cecab7)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81cee853)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff81a180ef)
Location: include/linux/ktime.h:111
Inline: True
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81bc155c)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/input/misc/uinput.c (ffffffff81d1f31f)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d557d7)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81d575d3)
Location: include/linux/ktime.h:111
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
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
In init/do_mounts.c (ffffffff838b1ce8)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In drivers/acpi/button.c (ffffffff81a6335f)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81c15ce7)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81caef74)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/input/misc/uinput.c (ffffffff81dd504f)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c6e7)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81e14213)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffff8000107a047c)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/clk/bcm/clk-bcm2835.c (ffff8000107cdd34)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adf6f0)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffff800010aeae50)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b5688c)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
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
In drivers/watchdog/watchdog_dev.c (c0bc1324)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (c0bc3714)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
```
In drivers/mmc/host/sdhci.c (c0c25ef8)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_reset
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37554)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
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
In drivers/watchdog/watchdog_dev.c (c000000000bc7928)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (c000000000bd6320)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In drivers/watchdog/watchdog_dev.c (ffffffe0006d756e)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffe0006e02e0)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff816023c3)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff818349a4)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff8183b44f)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/button.c (ffffffff815ed873)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc034)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81802abb)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff816261e3)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81883fd4)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff8188aa7f)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In drivers/acpi/button.c (ffffffff81640093)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189fa94)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff818a10bf)
Location: include/linux/ktime.h:128
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
</details>
</li>
</ul>

## Differences
