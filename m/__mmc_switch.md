# Function: <code>__mmc_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, bool use_busy_signal, bool send_status, bool ignore_crc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff816c61f0)
Location: drivers/mmc/core/mmc_ops.c:482
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc_ops.c:mmc_switch
```
**Symbols:**

```
ffffffff816c61f0-ffffffff816c64d4: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, bool use_busy_signal, bool send_status, bool ignore_crc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81729090)
Location: drivers/mmc/core/mmc_ops.c:472
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_switch
```
**Symbols:**

```
ffffffff81729090-ffffffff817293ff: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8175c0e0)
Location: drivers/mmc/core/mmc_ops.c:527
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_switch
```
**Symbols:**

```
ffffffff8175c0e0-ffffffff8175c454: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8177a4c0)
Location: drivers/mmc/core/mmc_ops.c:522
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
```
**Symbols:**

```
ffffffff8177a4c0-ffffffff8177a844: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f0910)
Location: drivers/mmc/core/mmc_ops.c:523
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
ffffffff817f0910-ffffffff817f0c97: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:523
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
ffffffff8183a52c-ffffffff8183a54e: __mmc_switch.cold.9 (STB_LOCAL)
ffffffff81839c40-ffffffff81839fa1: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:523
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
ffffffff818664c8-ffffffff818664ea: __mmc_switch.cold.9 (STB_LOCAL)
ffffffff81865c70-ffffffff81865ff1: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:525
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
ffffffff818aa301-ffffffff818aa32d: __mmc_switch.cold (STB_LOCAL)
ffffffff818a9ab0-ffffffff818a9e29: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:525
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
ffffffff818dc751-ffffffff818dc77d: __mmc_switch.cold (STB_LOCAL)
ffffffff818dbef0-ffffffff818dc27d: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:559
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff819af30c-ffffffff819af337: __mmc_switch.cold (STB_LOCAL)
ffffffff819aecc0-ffffffff819aeea9: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:559
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff81c2ac25-ffffffff81c2ac50: __mmc_switch.cold (STB_LOCAL)
ffffffff819b1320-ffffffff819b1509: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:539
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff81c1d075-ffffffff81c1d0a0: __mmc_switch.cold (STB_LOCAL)
ffffffff81995b10-ffffffff81995d06: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:564
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff81d2def8-ffffffff81d2df23: __mmc_switch.cold (STB_LOCAL)
ffffffff81a41990-ffffffff81a41bd7: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:594
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff81efa31f-ffffffff81efa34a: __mmc_switch.cold (STB_LOCAL)
ffffffff81baf030-ffffffff81baf2b0: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d529e0)
Location: drivers/mmc/core/mmc_ops.c:594
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff81d529e0-ffffffff81d52c8e: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbd390)
Location: drivers/mmc/core/mmc_ops.c:595
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff81dbd390-ffffffff81dbd63e: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool send_status, bool retry_crc_err, unsigned int retries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e759c0)
Location: drivers/mmc/core/mmc_ops.c:595
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff81e759c0-ffffffff81e75c6e: __mmc_switch (STB_GLOBAL)
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
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b36018)
Location: drivers/mmc/core/mmc_ops.c:525
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
ffff800010b36018-ffff800010b36354: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c10a80)
Location: drivers/mmc/core/mmc_ops.c:525
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
c0c10a80-c0c10e48: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c310b0)
Location: drivers/mmc/core/mmc_ops.c:525
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
c000000000c310b0-c000000000c3153c: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070e28e)
Location: drivers/mmc/core/mmc_ops.c:525
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
ffffffe00070e28e-ffffffe00070e548: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:525
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
ffffffff81880111-ffffffff8188013d: __mmc_switch.cold (STB_LOCAL)
ffffffff8187f8b0-ffffffff8187fc3d: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:525
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
ffffffff818d15b1-ffffffff818d15dd: __mmc_switch.cold (STB_LOCAL)
ffffffff818d0d50-ffffffff818d10dd: __mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms, unsigned char timing, bool use_busy_signal, bool send_status, bool retry_crc_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:525
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
```
**Symbols:**

```
ffffffff818ee0d1-ffffffff818ee0fd: __mmc_switch.cold (STB_LOCAL)
ffffffff818ed870-ffffffff818edbfd: __mmc_switch (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned char timing</code>
</li>
<li>
<b>Param added. </b>
<code>bool retry_crc_err</code>
</li>
<li>
<b>Param removed. </b>
<code>bool ignore_crc</code>
</li>
<li>
<b>Param reordered. </b>
<code>card, set, index, value, timeout_ms, use_busy_signal, send_status, ignore_crc</code> ➡️ <code>card, set, index, value, timeout_ms, timing, use_busy_signal, send_status, retry_crc_err</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool use_busy_signal</code>
</li>
<li>
<b>Param reordered. </b>
<code>card, set, index, value, timeout_ms, timing, use_busy_signal, send_status, retry_crc_err</code> ➡️ <code>card, set, index, value, timeout_ms, timing, send_status, retry_crc_err</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int retries</code>
</li>
</ul>
</details>
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
