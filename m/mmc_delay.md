# Function: <code>mmc_delay</code>

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
In drivers/mmc/core/core.c (ffffffff816beb2a)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
```
```
In drivers/mmc/core/mmc.c (ffffffff816c494e)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff816c5caf)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sd_ops.c (ffffffff816c82c3)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff816ca235)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff8172341b)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff8172669e)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff817293b2)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff8172b277)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8172d1f5)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff8175628b)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:mmc_set_signal_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff8175a9f4)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff8175c419)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff8175e32e)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff817601bc)
Location: drivers/mmc/core/core.h:57
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff817742bb)
Location: drivers/mmc/core/core.h:62
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81776e8b)
Location: drivers/mmc/core/core.h:62
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff8177a7f7)
Location: drivers/mmc/core/core.h:62
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff8177ca98)
Location: drivers/mmc/core/core.h:62
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8177ea67)
Location: drivers/mmc/core/core.h:62
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff817ea65b)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff817ed29d)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff817f0c4a)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff817f3018)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff817f5007)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff818335c0)
Location: drivers/mmc/core/core.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff818363df)
Location: drivers/mmc/core/core.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81839f3d)
Location: drivers/mmc/core/core.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff8183c468)
Location: drivers/mmc/core/core.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8183e4f7)
Location: drivers/mmc/core/core.h:65
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff8185f550)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff818623cf)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81865f71)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff818683f8)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8186a4a7)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff818a3111)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff818a652e)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff818a9da5)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff818ac318)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818ae397)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff818d5401)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff818d898d)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff818dc1f9)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff818de768)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818e0827)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff819a82a8)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff819aa91e)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_sleep
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff819ae381)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff819b1588)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff819b3847)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff819ab4b0)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff819ad4be)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_sleep
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff819b09e1)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff819b38a8)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff819b5cc7)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff819900f9)
Location: drivers/mmc/core/core.h:62
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81992837)
Location: drivers/mmc/core/core.h:62
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff819951ba)
Location: drivers/mmc/core/core.h:62
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81998088)
Location: drivers/mmc/core/core.h:62
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff8199a487)
Location: drivers/mmc/core/core.h:62
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff81a3b919)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81a3e2fa)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81a41b53)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81a44848)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81a46dc7)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff81ba88a1)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81bab5c3)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81baf252)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81bb2368)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81bb4bc7)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff81d4b121)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81d4e90b)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81d52c30)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81d56628)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81d592a7)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff81db59d1)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81db9225)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbd5e0)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81dc0f98)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81dc3c57)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff81e6de21)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_stop_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
  - drivers/mmc/core/core.c:mmc_power_up
  - drivers/mmc/core/core.c:mmc_power_up
  - drivers/mmc/core/core.c:mmc_power_up
  - drivers/mmc/core/core.c:mmc_power_up
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:mmc_select_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff81e71775)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81e75c10)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81e798d8)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff81e7c537)
Location: drivers/mmc/core/core.h:63
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffff800010b2ec1c)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffff800010b32fd8)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffff800010b362e0)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffff800010b3888c)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffff800010b3a9d0)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (c0c0a0fc)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (c0c0da1c)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (c0c10db4)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (c0c13214)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (c0c15398)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (c000000000c285fc)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (c000000000c2d3c0)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (c000000000c31334)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (c000000000c34728)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (c000000000c373bc)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffe0007083d0)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffe00070b73a)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffe00070e440)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffe00071063c)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffe000712326)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff81878dc1)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff8187c34d)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff8187fbb9)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81882128)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818841e7)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff818ca261)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff818cd7ed)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff818d1059)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff818d35c8)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818d5687)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
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
In drivers/mmc/core/core.c (ffffffff818e6d81)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_power_cycle
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:mmc_host_set_uhs_voltage
  - drivers/mmc/core/core.c:__mmc_start_request
  - drivers/mmc/core/core.c:__mmc_start_request
```
```
In drivers/mmc/core/mmc.c (ffffffff818ea30d)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff818edb79)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
  - drivers/mmc/core/mmc_ops.c:mmc_go_idle
```
```
In drivers/mmc/core/sd_ops.c (ffffffff818f00e8)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_send_app_op_cond
```
```
In drivers/mmc/core/sdio_ops.c (ffffffff818f21a7)
Location: drivers/mmc/core/core.h:61
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond
```
</details>
</li>
</ul>

## Differences
