# Function: <code>mmc_release_host</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bdd00)
Location: drivers/mmc/core/core.c:986
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_resume
  - drivers/mmc/core/sd.c:_mmc_sd_resume
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
ffffffff816bdd00-ffffffff816bddbc: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8171f910)
Location: drivers/mmc/core/core.c:987
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
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
ffffffff8171f910-ffffffff8171f9cc: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817521a0)
Location: drivers/mmc/core/core.c:1059
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
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
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff817521a0-ffffffff8175225c: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81770c00)
Location: drivers/mmc/core/core.c:891
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
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
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81770c00-ffffffff81770ca3: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e6940)
Location: drivers/mmc/core/core.c:1074
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
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
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff817e6940-ffffffff817e69f1: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8182fc90)
Location: drivers/mmc/core/core.c:873
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
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
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8182fc90-ffffffff8182fd41: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185bf00)
Location: drivers/mmc/core/core.c:873
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
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
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/sdio_irq.c:sdio_run_irqs
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8185bf00-ffffffff8185bfcb: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:844
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818a3cea-ffffffff818a3cfd: mmc_release_host.cold (STB_LOCAL)
ffffffff8189fdc0-ffffffff8189fe81: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d2330)
Location: drivers/mmc/core/core.c:844
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818d2330-ffffffff818d23f8: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a4a70)
Location: drivers/mmc/core/core.c:827
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff819a4a70-ffffffff819a4b38: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a7b10)
Location: drivers/mmc/core/core.c:827
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff819a7b10-ffffffff819a7bd8: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198c810)
Location: drivers/mmc/core/core.c:828
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8198c810-ffffffff8198c8d8: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a37e70)
Location: drivers/mmc/core/core.c:828
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81a37e70-ffffffff81a37f38: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba4a40)
Location: drivers/mmc/core/core.c:828
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81ba4a40-ffffffff81ba4b2f: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d46c80)
Location: drivers/mmc/core/core.c:827
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81d46c80-ffffffff81d46d6f: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db1470)
Location: drivers/mmc/core/core.c:827
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81db1470-ffffffff81db155f: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e69800)
Location: drivers/mmc/core/core.c:832
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81e69800-ffffffff81e698ef: mmc_release_host (STB_GLOBAL)
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
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2d7e8)
Location: drivers/mmc/core/core.c:844
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/queue.c:mmc_queue_suspend
```
**Symbols:**

```
ffff800010b2d7e8-ffff800010b2d938: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c06c60)
Location: drivers/mmc/core/core.c:844
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/queue.c:mmc_queue_suspend
```
**Symbols:**

```
c0c06c60-c0c06d2c: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c23e50)
Location: drivers/mmc/core/core.c:844
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
c000000000c23e50-c000000000c23f84: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe0007056b0)
Location: drivers/mmc/core/core.c:844
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/queue.c:mmc_queue_suspend
```
**Symbols:**

```
ffffffe0007056b0-ffffffe000705784: mmc_release_host (STB_GLOBAL)
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
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81875cf0)
Location: drivers/mmc/core/core.c:844
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81875cf0-ffffffff81875db8: mmc_release_host (STB_GLOBAL)
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
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c7190)
Location: drivers/mmc/core/core.c:844
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818c7190-ffffffff818c7258: mmc_release_host (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmc_release_host(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e3c40)
Location: drivers/mmc/core/core.c:844
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_put_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_runtime_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_suspend
  - drivers/mmc/core/sdio_io.c:sdio_release_host
  - drivers/mmc/core/sdio_irq.c:sdio_irq_thread
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/sdio_irq.c:sdio_irq_work
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818e3c40-ffffffff818e3d08: mmc_release_host (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
