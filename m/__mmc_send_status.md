# Function: <code>__mmc_send_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, bool ignore_crc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff816c5620)
Location: drivers/mmc/core/mmc_ops.c:57
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_status
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_status
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff816c5620-ffffffff816c5626: __mmc_send_status.part.2 (STB_LOCAL)
ffffffff816c5630-ffffffff816c56d4: __mmc_send_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, bool ignore_crc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81728989)
Location: drivers/mmc/core/mmc_ops.c:57
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_send_status
Direct callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_send_status
```
**Symbols:**

```
ffffffff817284a0-ffffffff817284a6: __mmc_send_status.part.2 (STB_LOCAL)
ffffffff817284b0-ffffffff81728554: __mmc_send_status (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81779490)
Location: drivers/mmc/core/mmc_ops.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
```
**Symbols:**

```
ffffffff81779490-ffffffff81779528: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817ef8e0)
Location: drivers/mmc/core/mmc_ops.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
```
**Symbols:**

```
ffffffff817ef8e0-ffffffff817ef978: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81838c50)
Location: drivers/mmc/core/mmc_ops.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
```
**Symbols:**

```
ffffffff81838c50-ffffffff81838ce8: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81864c80)
Location: drivers/mmc/core/mmc_ops.c:58
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
```
**Symbols:**

```
ffffffff81864c80-ffffffff81864d18: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818a8b40)
Location: drivers/mmc/core/mmc_ops.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
```
**Symbols:**

```
ffffffff818a8b40-ffffffff818a8bc7: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818daf80)
Location: drivers/mmc/core/mmc_ops.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
```
**Symbols:**

```
ffffffff818daf80-ffffffff818db007: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819ad9f0)
Location: drivers/mmc/core/mmc_ops.c:56
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
**Symbols:**

```
ffffffff819ad9f0-ffffffff819ada76: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819b0060)
Location: drivers/mmc/core/mmc_ops.c:56
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
**Symbols:**

```
ffffffff819b0060-ffffffff819b00e6: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81994830)
Location: drivers/mmc/core/mmc_ops.c:56
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
**Symbols:**

```
ffffffff81994830-ffffffff819948b6: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a40560)
Location: drivers/mmc/core/mmc_ops.c:61
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_busy_cb
```
**Symbols:**

```
ffffffff81a40560-ffffffff81a405e6: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81bad940)
Location: drivers/mmc/core/mmc_ops.c:69
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_busy_cb
```
**Symbols:**

```
ffffffff81bad940-ffffffff81bad9e6: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d51040)
Location: drivers/mmc/core/mmc_ops.c:69
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_busy_cb
```
**Symbols:**

```
ffffffff81d51040-ffffffff81d510e6: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbba60)
Location: drivers/mmc/core/mmc_ops.c:69
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_busy_cb
```
**Symbols:**

```
ffffffff81dbba60-ffffffff81dbbb06: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e74030)
Location: drivers/mmc/core/mmc_ops.c:69
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:mmc_busy_cb
```
**Symbols:**

```
ffffffff81e74030-ffffffff81e740d6: __mmc_send_status (STB_GLOBAL)
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
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b34f68)
Location: drivers/mmc/core/mmc_ops.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:card_busy_detect
```
**Symbols:**

```
ffff800010b34f68-ffff800010b35018: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c0fa68)
Location: drivers/mmc/core/mmc_ops.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:card_busy_detect
```
**Symbols:**

```
c0c0fa68-c0c0fb1c: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c2fbb0)
Location: drivers/mmc/core/mmc_ops.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
```
**Symbols:**

```
c000000000c2fbb0-c000000000c2fc8c: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070d42a)
Location: drivers/mmc/core/mmc_ops.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:card_busy_detect
```
**Symbols:**

```
ffffffe00070d42a-ffffffe00070d4b6: __mmc_send_status (STB_GLOBAL)
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
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8187e940)
Location: drivers/mmc/core/mmc_ops.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
```
**Symbols:**

```
ffffffff8187e940-ffffffff8187e9c7: __mmc_send_status (STB_GLOBAL)
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
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818cfde0)
Location: drivers/mmc/core/mmc_ops.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
```
**Symbols:**

```
ffffffff818cfde0-ffffffff818cfe67: __mmc_send_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __mmc_send_status(struct mmc_card *card, u32 *status, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818ec900)
Location: drivers/mmc/core/mmc_ops.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/mmc_ops.c:__mmc_switch_status
```
**Symbols:**

```
ffffffff818ec900-ffffffff818ec987: __mmc_send_status (STB_GLOBAL)
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
