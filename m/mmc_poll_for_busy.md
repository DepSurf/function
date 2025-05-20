# Function: <code>mmc_poll_for_busy</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8175c27b)
Location: drivers/mmc/core/mmc_ops.c:453
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8177a688)
Location: drivers/mmc/core/mmc_ops.c:448
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f0ad8)
Location: drivers/mmc/core/mmc_ops.c:449
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81839db4)
Location: drivers/mmc/core/mmc_ops.c:449
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81865de4)
Location: drivers/mmc/core/mmc_ops.c:449
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
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
In drivers/mmc/core/mmc_ops.c (ffffffff818a9c25)
Location: drivers/mmc/core/mmc_ops.c:451
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
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
In drivers/mmc/core/mmc_ops.c (ffffffff818dc078)
Location: drivers/mmc/core/mmc_ops.c:451
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819ae448)
Location: drivers/mmc/core/mmc_ops.c:539
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
**Symbols:**

```
ffffffff819aeca0-ffffffff819aecba: mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819b0aa8)
Location: drivers/mmc/core/mmc_ops.c:539
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
**Symbols:**

```
ffffffff819b1300-ffffffff819b131a: mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819952bf)
Location: drivers/mmc/core/mmc_ops.c:518
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
**Symbols:**

```
ffffffff81995af0-ffffffff81995b0a: mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, bool retry_crc_err, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a40c46)
Location: drivers/mmc/core/mmc_ops.c:515
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:sd_flush_cache
```
**Symbols:**

```
ffffffff81a40b20-ffffffff81a40b6c: mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, bool retry_crc_err, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81bae4f0)
Location: drivers/mmc/core/mmc_ops.c:544
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:sd_flush_cache
```
**Symbols:**

```
ffffffff81bae190-ffffffff81bae1fb: mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, bool retry_crc_err, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d51d71)
Location: drivers/mmc/core/mmc_ops.c:544
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:sd_flush_cache
```
**Symbols:**

```
ffffffff81d51610-ffffffff81d5167b: mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, bool retry_crc_err, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbc781)
Location: drivers/mmc/core/mmc_ops.c:544
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:sd_flush_cache
```
**Symbols:**

```
ffffffff81dbc030-ffffffff81dbc09b: mmc_poll_for_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_poll_for_busy(struct mmc_card *card, unsigned int timeout_ms, bool retry_crc_err, enum mmc_busy_cmd busy_cmd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e74d51)
Location: drivers/mmc/core/mmc_ops.c:544
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:sd_flush_cache
```
**Symbols:**

```
ffffffff81e74600-ffffffff81e7466b: mmc_poll_for_busy (STB_GLOBAL)
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
In drivers/mmc/core/mmc_ops.c (ffff800010b36180)
Location: drivers/mmc/core/mmc_ops.c:451
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c10c00)
Location: drivers/mmc/core/mmc_ops.c:451
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
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
In drivers/mmc/core/mmc_ops.c (c000000000c312d0)
Location: drivers/mmc/core/mmc_ops.c:451
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
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
In drivers/mmc/core/mmc_ops.c (ffffffe00070e3c6)
Location: drivers/mmc/core/mmc_ops.c:451
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
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
In drivers/mmc/core/mmc_ops.c (ffffffff8187fa38)
Location: drivers/mmc/core/mmc_ops.c:451
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
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
In drivers/mmc/core/mmc_ops.c (ffffffff818d0ed8)
Location: drivers/mmc/core/mmc_ops.c:451
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
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
In drivers/mmc/core/mmc_ops.c (ffffffff818ed9f8)
Location: drivers/mmc/core/mmc_ops.c:451
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
</details>
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
<code>bool retry_crc_err</code>
</li>
<li>
<b>Param reordered. </b>
<code>card, timeout_ms, busy_cmd</code> ➡️ <code>card, timeout_ms, retry_crc_err, busy_cmd</code>
</li>
</ul>
</details>
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
