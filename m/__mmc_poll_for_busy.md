# Function: <code>__mmc_poll_for_busy</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, bool send_status, bool retry_crc_err, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:488
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff819ae200-ffffffff819ae3b6: __mmc_poll_for_busy (STB_LOCAL)
ffffffff819af2b1-ffffffff819af2e6: __mmc_poll_for_busy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, bool send_status, bool retry_crc_err, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:488
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff819b0860-ffffffff819b0a16: __mmc_poll_for_busy (STB_LOCAL)
ffffffff81c2abca-ffffffff81c2abff: __mmc_poll_for_busy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, bool send_status, bool retry_crc_err, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:467
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81995030-ffffffff819951ef: __mmc_poll_for_busy (STB_LOCAL)
ffffffff81c1cfcd-ffffffff81c1d002: __mmc_poll_for_busy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, int (*busy_cb)(void *, bool *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:473
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
**Symbols:**

```
ffffffff81d2ddac-ffffffff81d2de38: __mmc_poll_for_busy.cold (STB_LOCAL)
ffffffff81a40a10-ffffffff81a40b14: __mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __mmc_poll_for_busy(struct mmc_host *host, unsigned int period_us, unsigned int timeout_ms, int (*busy_cb)(void *, bool *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:502
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
**Symbols:**

```
ffffffff81efa202-ffffffff81efa299: __mmc_poll_for_busy.cold (STB_LOCAL)
ffffffff81bae070-ffffffff81bae18f: __mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __mmc_poll_for_busy(struct mmc_host *host, unsigned int period_us, unsigned int timeout_ms, int (*busy_cb)(void *, bool *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:502
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
**Symbols:**

```
ffffffff820a999f-ffffffff820a9a0a: __mmc_poll_for_busy.cold (STB_LOCAL)
ffffffff81d514a0-ffffffff81d515f1: __mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __mmc_poll_for_busy(struct mmc_host *host, unsigned int period_us, unsigned int timeout_ms, int (*busy_cb)(void *, bool *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:502
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
**Symbols:**

```
ffffffff8212ad81-ffffffff8212adec: __mmc_poll_for_busy.cold (STB_LOCAL)
ffffffff81dbbec0-ffffffff81dbc011: __mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __mmc_poll_for_busy(struct mmc_host *host, unsigned int period_us, unsigned int timeout_ms, int (*busy_cb)(void *, bool *), void *cb_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:502
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_op_cond
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
```
**Symbols:**

```
ffffffff8220cb3e-ffffffff8220cba9: __mmc_poll_for_busy.cold (STB_LOCAL)
ffffffff81e74490-ffffffff81e745e1: __mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int (*busy_cb)(void *, bool *)</code>
</li>
<li>
<b>Param added. </b>
<code>void *cb_data</code>
</li>
<li>
<b>Param removed. </b>
<code>bool send_status</code>
</li>
<li>
<b>Param removed. </b>
<code>bool retry_crc_err</code>
</li>
<li>
<b>Param removed. </b>
<code>enum mmc_busy_cmd busy_cmd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmc_host *host</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int period_us</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mmc_card *card</code>
</li>
<li>
<b>Param reordered. </b>
<code>card, timeout_ms, busy_cb, cb_data</code> ➡️ <code>host, period_us, timeout_ms, busy_cb, cb_data</code>
</li>
</ul>
</details>
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
