# Function: <code>mmc_send_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff816c5b00)
Location: drivers/mmc/core/mmc_ops.c:86
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/mmc.c:mmc_switch_status
  - drivers/mmc/core/sd.c:mmc_sd_alive
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get
```
**Symbols:**

```
ffffffff816c5b00-ffffffff816c5b9f: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81728980)
Location: drivers/mmc/core/mmc_ops.c:86
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/mmc.c:mmc_switch_status
  - drivers/mmc/core/sd.c:mmc_sd_alive
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get
```
**Symbols:**

```
ffffffff81728980-ffffffff81728a1f: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8175b900)
Location: drivers/mmc/core/mmc_ops.c:57
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
  - drivers/mmc/core/sd.c:mmc_sd_alive
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get
```
**Symbols:**

```
ffffffff8175b900-ffffffff8175b98b: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8177aa5b)
Location: drivers/mmc/core/mmc_ops.c:82
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get
```
**Symbols:**

```
ffffffff81779dd0-ffffffff81779de5: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f104d)
Location: drivers/mmc/core/mmc_ops.c:82
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff817ef980-ffffffff817ef995: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8183a301)
Location: drivers/mmc/core/mmc_ops.c:82
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff81838cf0-ffffffff81838d05: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818662e1)
Location: drivers/mmc/core/mmc_ops.c:82
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff81864d20-ffffffff81864d35: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818aa121)
Location: drivers/mmc/core/mmc_ops.c:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff818a8bd0-ffffffff818a8be5: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818dc571)
Location: drivers/mmc/core/mmc_ops.c:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff818db010-ffffffff818db025: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819af392)
Location: drivers/mmc/core/mmc_ops.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff819ae580-ffffffff819ae60a: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81c2acab)
Location: drivers/mmc/core/mmc_ops.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff819b0be0-ffffffff819b0c6a: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81995223)
Location: drivers/mmc/core/mmc_ops.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff819954c0-ffffffff8199554a: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a40bb2)
Location: drivers/mmc/core/mmc_ops.c:85
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_busy_cb
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff81a410a0-ffffffff81a4112a: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81bae456)
Location: drivers/mmc/core/mmc_ops.c:93
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_busy_cb
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff81bae5f0-ffffffff81bae697: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d51cdb)
Location: drivers/mmc/core/mmc_ops.c:93
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_busy_cb
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff81d51ea0-ffffffff81d51f47: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbc6eb)
Location: drivers/mmc/core/mmc_ops.c:93
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_busy_cb
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff81dbc8b0-ffffffff81dbc957: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e74cbb)
Location: drivers/mmc/core/mmc_ops.c:93
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_busy_cb
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff81e74e80-ffffffff81e74f27: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b36744)
Location: drivers/mmc/core/mmc_ops.c:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
```
**Symbols:**

```
ffff800010b35018-ffff800010b35050: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c111c8)
Location: drivers/mmc/core/mmc_ops.c:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
```
**Symbols:**

```
c0c0fb1c-c0c0fb3c: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c31a50)
Location: drivers/mmc/core/mmc_ops.c:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
c000000000c2fc90-c000000000c2fca8: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070e842)
Location: drivers/mmc/core/mmc_ops.c:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
```
**Symbols:**

```
ffffffe00070d4b6-ffffffe00070d4ea: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8187ff31)
Location: drivers/mmc/core/mmc_ops.c:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff8187e9d0-ffffffff8187e9e5: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818d13d1)
Location: drivers/mmc/core/mmc_ops.c:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff818cfe70-ffffffff818cfe85: mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mmc_send_status(struct mmc_card *card, u32 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818edef1)
Location: drivers/mmc/core/mmc_ops.c:78
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_alive
  - drivers/mmc/core/sd.c:mmc_sd_alive
```
**Symbols:**

```
ffffffff818ec990-ffffffff818ec9a5: mmc_send_status (STB_GLOBAL)
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
