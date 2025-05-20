# Function: <code>mmc_claim_host</code>

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
In drivers/mmc/core/core.c (ffffffff816bdceb)
Location: include/linux/mmc/core.h:205
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_pm_notify
```
```
In drivers/mmc/core/mmc.c (ffffffff816c46e9)
Location: include/linux/mmc/core.h:205
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
```
```
In drivers/mmc/core/sd.c (ffffffff816c6955)
Location: include/linux/mmc/core.h:205
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_resume
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
```
```
In drivers/mmc/core/sdio.c (ffffffff816c8996)
Location: include/linux/mmc/core.h:205
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/core/sdio_io.c (ffffffff816cc063)
Location: include/linux/mmc/core.h:205
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff816cc456)
Location: include/linux/mmc/core.h:205
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
```
In drivers/mmc/core/debugfs.c (ffffffff816cd1ed)
Location: include/linux/mmc/core.h:205
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff81723a68)
Location: include/linux/mmc/core.h:204
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
```
```
In drivers/mmc/core/mmc.c (ffffffff81727f62)
Location: include/linux/mmc/core.h:204
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff8172af25)
Location: include/linux/mmc/core.h:204
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff8172ce9e)
Location: include/linux/mmc/core.h:204
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8172efb3)
Location: include/linux/mmc/core.h:204
Inline: True
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff8172f3a6)
Location: include/linux/mmc/core.h:204
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
```
In drivers/mmc/core/debugfs.c (ffffffff8173014d)
Location: include/linux/mmc/core.h:204
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff81756928)
Location: include/linux/mmc/core.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
```
```
In drivers/mmc/core/mmc.c (ffffffff8175afdd)
Location: include/linux/mmc/core.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff8175dfec)
Location: include/linux/mmc/core.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff8175fe4e)
Location: include/linux/mmc/core.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81761541)
Location: include/linux/mmc/core.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81762396)
Location: include/linux/mmc/core.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
```
In drivers/mmc/core/debugfs.c (ffffffff8176314d)
Location: include/linux/mmc/core.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff81774868)
Location: drivers/mmc/core/core.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
```
```
In drivers/mmc/core/mmc.c (ffffffff817793e9)
Location: drivers/mmc/core/core.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff8177ad54)
Location: drivers/mmc/core/core.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
```
```
In drivers/mmc/core/sd.c (ffffffff8177c72c)
Location: drivers/mmc/core/core.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff8177e73c)
Location: drivers/mmc/core/core.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8177fd7e)
Location: drivers/mmc/core/core.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81780af6)
Location: drivers/mmc/core/core.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
```
In drivers/mmc/core/debugfs.c (ffffffff8178176d)
Location: drivers/mmc/core/core.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff817eaaa7)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff817ef839)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff817f1044)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
```
```
In drivers/mmc/core/sd.c (ffffffff817f2cac)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff817f4cdc)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (ffffffff817f6331)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff817f70b6)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
```
In drivers/mmc/core/debugfs.c (ffffffff817f7d21)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff818339f7)
Location: drivers/mmc/core/core.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff8183868d)
Location: drivers/mmc/core/core.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff8183be95)
Location: drivers/mmc/core/core.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff8183e129)
Location: drivers/mmc/core/core.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8183f83e)
Location: drivers/mmc/core/core.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81840585)
Location: drivers/mmc/core/core.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
```
In drivers/mmc/core/debugfs.c (ffffffff818412f1)
Location: drivers/mmc/core/core.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff8185f987)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff8186468d)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff81867e25)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff8186a0d9)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8186b7ee)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff8186c535)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
```
```
In drivers/mmc/core/debugfs.c (ffffffff8186d1c1)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff818a351f)
Location: drivers/mmc/core/core.h:132
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff818a8548)
Location: drivers/mmc/core/core.h:132
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff818abd13)
Location: drivers/mmc/core/core.h:132
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff818adfa8)
Location: drivers/mmc/core/core.h:132
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818af822)
Location: drivers/mmc/core/core.h:132
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818b0ac6)
Location: drivers/mmc/core/core.h:132
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff818b149d)
Location: drivers/mmc/core/core.h:132
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff818d589f)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff818da9a8)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff818de173)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff818e0458)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818e1cca)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818e2f76)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff818e393d)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff819a822b)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff819ad408)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff819b0f63)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff819b34e9)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffff819b4cca)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff819b6096)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff819b6a3d)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff819ab41d)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff819affe8)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff819b34d3)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff819b5a39)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffff819b727a)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff819b8616)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff819b8f3d)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff81990089)
Location: drivers/mmc/core/core.h:127
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff819947b8)
Location: drivers/mmc/core/core.h:127
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff81997cb3)
Location: drivers/mmc/core/core.h:127
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff8199a1bd)
Location: drivers/mmc/core/core.h:127
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8199ba3a)
Location: drivers/mmc/core/core.h:127
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff8199cd46)
Location: drivers/mmc/core/core.h:127
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff8199d66d)
Location: drivers/mmc/core/core.h:127
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff81a3b8a9)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff81a404e8)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff81a44473)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff81a46a6b)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81a483ea)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81a49738)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff81a4a0ad)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff81ba8830)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff81bad8ce)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff81bb1f51)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb4835)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81bb646a)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81bb7a48)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff81bb850d)
Location: drivers/mmc/core/core.h:131
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff81d4b0b0)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff81d50fdf)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff81d561de)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff81d58eda)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81d5ae9a)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81d5c668)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff81d5d58d)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff81db5960)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff81dbb99f)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff81dc0b4e)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc388e)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81dc591a)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81dc70c8)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff81dc816d)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff81e6ddb0)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff81e73f6f)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff81e793de)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7c16e)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81e7e25a)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81e7fa08)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff81e80c3d)
Location: drivers/mmc/core/core.h:146
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffff800010b2f284)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffff800010b34ee4)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffff800010b3850c)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a638)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (ffff800010b3c2bc)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffff800010b3d80c)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffff800010b3e678)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
```
In drivers/mmc/core/block.c (ffff800010b417b0)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/mmc/core/queue.c (ffff800010b44628)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_queue_suspend
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
In drivers/mmc/core/core.c (c0c0a670)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (c0c0f9d4)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (c0c12e70)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (c0c15060)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (c0c169a4)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (c0c17e40)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (c0c18b84)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
```
In drivers/mmc/core/block.c (c0c1c59c)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/mmc/core/queue.c (c0c1e1a4)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_queue_suspend
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
In drivers/mmc/core/core.c (c000000000c28d20)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (c000000000c2fb04)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (c000000000c3427c)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (c000000000c36ec4)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (c000000000c391a0)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (c000000000c3ad70)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (c000000000c3c1e0)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffe000708ed6)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffe00070d3b4)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffe00071038e)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffe0007120a4)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_io.c (ffffffe0007137e6)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffe0007148ce)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffe00071555e)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
```
In drivers/mmc/core/block.c (ffffffe00071869a)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/mmc/core/queue.c (ffffffe000719f0e)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_queue_suspend
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
In drivers/mmc/core/core.c (ffffffff8187925f)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff8187e368)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff81881b33)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff81883e18)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8188568a)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81886936)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff818872fd)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff818ca6ff)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff818cf808)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff818d2fd3)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff818d52b8)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818d6b2a)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818d7dd6)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff818d879d)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
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
In drivers/mmc/core/core.c (ffffffff818e721f)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/mmc.c (ffffffff818ec328)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/sd.c (ffffffff818efaf3)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1dd8)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818f364a)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818f48f6)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
```
```
In drivers/mmc/core/debugfs.c (ffffffff818f52bd)
Location: drivers/mmc/core/core.h:134
Inline: True
Inline callers:
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
</details>
</li>
</ul>

## Differences
