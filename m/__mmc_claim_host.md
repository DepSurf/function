# Function: <code>__mmc_claim_host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bdb00)
Location: drivers/mmc/core/core.c:940
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_resume
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
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
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff816bdb00-ffffffff816bdcc3: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8171f720)
Location: drivers/mmc/core/core.c:941
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
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
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8171f720-ffffffff8171f8d3: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81751fb0)
Location: drivers/mmc/core/core.c:1013
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
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
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81751fb0-ffffffff81752165: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817709e0)
Location: drivers/mmc/core/core.c:845
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff817709e0-ffffffff81770bce: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e66b0)
Location: drivers/mmc/core/core.c:1026
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff817e66b0-ffffffff817e68fd: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8182fa00)
Location: drivers/mmc/core/core.c:825
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8182fa00-ffffffff8182fc4d: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185bc70)
Location: drivers/mmc/core/core.c:825
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8185bc70-ffffffff8185bec0: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8189fb20)
Location: drivers/mmc/core/core.c:796
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8189fb20-ffffffff8189fd76: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d2090)
Location: drivers/mmc/core/core.c:796
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818d2090-ffffffff818d22e6: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a47e0)
Location: drivers/mmc/core/core.c:779
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff819a47e0-ffffffff819a4a2a: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a7860)
Location: drivers/mmc/core/core.c:779
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff819a7860-ffffffff819a7ac1: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198c570)
Location: drivers/mmc/core/core.c:780
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8198c570-ffffffff8198c7d0: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a37bf0)
Location: drivers/mmc/core/core.c:780
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81a37bf0-ffffffff81a37e2c: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba47c0)
Location: drivers/mmc/core/core.c:780
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81ba47c0-ffffffff81ba49f6: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d469e0)
Location: drivers/mmc/core/core.c:779
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81d469e0-ffffffff81d46c16: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db11b0)
Location: drivers/mmc/core/core.c:779
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81db11b0-ffffffff81db1404: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e69540)
Location: drivers/mmc/core/core.c:784
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81e69540-ffffffff81e69794: __mmc_claim_host (STB_GLOBAL)
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
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2d4d0)
Location: drivers/mmc/core/core.c:796
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/queue.c:mmc_queue_suspend
```
**Symbols:**

```
ffff800010b2d4d0-ffff800010b2d7a0: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c069ec)
Location: drivers/mmc/core/core.c:796
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/queue.c:mmc_queue_suspend
```
**Symbols:**

```
c0c069ec-c0c06c24: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c23af0)
Location: drivers/mmc/core/core.c:796
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
c000000000c23af0-c000000000c23df0: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe00070549a)
Location: drivers/mmc/core/core.c:796
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/queue.c:mmc_queue_suspend
```
**Symbols:**

```
ffffffe00070549a-ffffffe00070566e: __mmc_claim_host (STB_GLOBAL)
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
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81875a50)
Location: drivers/mmc/core/core.c:796
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81875a50-ffffffff81875ca6: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c6ef0)
Location: drivers/mmc/core/core.c:796
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818c6ef0-ffffffff818c7146: __mmc_claim_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __mmc_claim_host(struct mmc_host *host, struct mmc_ctx *ctx, atomic_t *abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e39a0)
Location: drivers/mmc/core/core.c:796
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_claim_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818e39a0-ffffffff818e3bf1: __mmc_claim_host (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmc_ctx *ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>host, abort</code> ➡️ <code>host, ctx, abort</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
