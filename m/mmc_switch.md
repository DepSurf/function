# Function: <code>mmc_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff816c64e0)
Location: drivers/mmc/core/mmc_ops.c:583
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff816c64e0-ffffffff816c6513: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81729400)
Location: drivers/mmc/core/mmc_ops.c:587
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff81729400-ffffffff81729433: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8175c460)
Location: drivers/mmc/core/mmc_ops.c:603
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff8175c460-ffffffff8175c498: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8177a91f)
Location: drivers/mmc/core/mmc_ops.c:598
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff8177a850-ffffffff8177a873: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f0d6f)
Location: drivers/mmc/core/mmc_ops.c:599
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff817f0ca0-ffffffff817f0cc3: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8183a083)
Location: drivers/mmc/core/mmc_ops.c:599
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff81839fb0-ffffffff81839fd3: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818660d3)
Location: drivers/mmc/core/mmc_ops.c:599
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff81866000-ffffffff81866023: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818a9f0a)
Location: drivers/mmc/core/mmc_ops.c:601
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff818a9e30-ffffffff818a9e53: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818dc35a)
Location: drivers/mmc/core/mmc_ops.c:603
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff818dc280-ffffffff818dc2a3: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819aeff1)
Location: drivers/mmc/core/mmc_ops.c:632
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/mmc.c:__mmc_select_powerclass
```
**Symbols:**

```
ffffffff819aeeb0-ffffffff819aeed1: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819b1651)
Location: drivers/mmc/core/mmc_ops.c:632
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/mmc.c:__mmc_select_powerclass
```
**Symbols:**

```
ffffffff819b1510-ffffffff819b1531: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81995ebc)
Location: drivers/mmc/core/mmc_ops.c:612
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff81995d10-ffffffff81995d33: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a41d87)
Location: drivers/mmc/core/mmc_ops.c:629
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_flush_cache
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/mmc.c:__mmc_select_powerclass
```
**Symbols:**

```
ffffffff81a41be0-ffffffff81a41c03: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81baf417)
Location: drivers/mmc/core/mmc_ops.c:659
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_flush_cache
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/mmc.c:__mmc_select_powerclass
```
**Symbols:**

```
ffffffff81baf2b0-ffffffff81baf2e5: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d52e77)
Location: drivers/mmc/core/mmc_ops.c:659
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_flush_cache
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/mmc.c:__mmc_select_powerclass
```
**Symbols:**

```
ffffffff81d52ca0-ffffffff81d52cd5: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbd847)
Location: drivers/mmc/core/mmc_ops.c:660
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_flush_cache
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/mmc.c:__mmc_select_powerclass
```
**Symbols:**

```
ffffffff81dbd650-ffffffff81dbd685: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e75e77)
Location: drivers/mmc/core/mmc_ops.c:660
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_flush_cache
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/mmc.c:__mmc_select_powerclass
```
**Symbols:**

```
ffffffff81e75c80-ffffffff81e75cb5: mmc_switch (STB_GLOBAL)
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
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b364a0)
Location: drivers/mmc/core/mmc_ops.c:603
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffff800010b36358-ffff800010b363cc: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c10f54)
Location: drivers/mmc/core/mmc_ops.c:603
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_reset
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
c0c10e48-c0c10e88: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c316b0)
Location: drivers/mmc/core/mmc_ops.c:603
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
c000000000c31540-c000000000c31584: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070e634)
Location: drivers/mmc/core/mmc_ops.c:603
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_reset
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
  - drivers/mmc/core/block.c:__mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffffffe00070e548-ffffffe00070e59a: mmc_switch (STB_GLOBAL)
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
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8187fd1a)
Location: drivers/mmc/core/mmc_ops.c:603
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff8187fc40-ffffffff8187fc63: mmc_switch (STB_GLOBAL)
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
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818d11ba)
Location: drivers/mmc/core/mmc_ops.c:603
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff818d10e0-ffffffff818d1103: mmc_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int mmc_switch(struct mmc_card *card, u8 set, u8 index, u8 value, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818edcda)
Location: drivers/mmc/core/mmc_ops.c:603
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_switch
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff818edc00-ffffffff818edc23: mmc_switch (STB_GLOBAL)
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
