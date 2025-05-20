# Function: <code>mmc_set_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bfc90)
Location: drivers/mmc/core/core.c:1060
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff816bfc90-ffffffff816bfd65: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81722990)
Location: drivers/mmc/core/core.c:1061
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81722990-ffffffff81722a74: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81755760)
Location: drivers/mmc/core/core.c:1133
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81755760-ffffffff81755844: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817738a0)
Location: drivers/mmc/core/core.c:965
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff817738a0-ffffffff81773961: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e9980)
Location: drivers/mmc/core/core.c:1153
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff817e9980-ffffffff817e9a47: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818328c0)
Location: drivers/mmc/core/core.c:952
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818328c0-ffffffff81832985: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185eac0)
Location: drivers/mmc/core/core.c:955
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8185eac0-ffffffff8185eb85: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:926
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818a3fb7-ffffffff818a3fd0: mmc_set_clock.cold (STB_LOCAL)
ffffffff818a2510-ffffffff818a25eb: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d4810)
Location: drivers/mmc/core/core.c:926
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818d4810-ffffffff818d48ee: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a6e70)
Location: drivers/mmc/core/core.c:909
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff819a6e70-ffffffff819a6f4e: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819aa0c0)
Location: drivers/mmc/core/core.c:909
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff819aa0c0-ffffffff819aa19e: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198e950)
Location: drivers/mmc/core/core.c:910
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8198e950-ffffffff8198ea2a: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:910
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81d2d04c-ffffffff81d2d074: mmc_set_clock.cold (STB_LOCAL)
ffffffff81a39ff0-ffffffff81a3a0d7: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:910
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff81ef940e-ffffffff81ef9434: mmc_set_clock.cold (STB_LOCAL)
ffffffff81ba6dc0-ffffffff81ba6ea3: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:909
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff820a9584-ffffffff820a95aa: mmc_set_clock.cold (STB_LOCAL)
ffffffff81d49350-ffffffff81d4943a: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:909
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8212a983-ffffffff8212a9a9: mmc_set_clock.cold (STB_LOCAL)
ffffffff81db3bd0-ffffffff81db3cba: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:914
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff8220c72b-ffffffff8220c751: mmc_set_clock.cold (STB_LOCAL)
ffffffff81e6bfa0-ffffffff81e6c08a: mmc_set_clock (STB_GLOBAL)
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
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2def0)
Location: drivers/mmc/core/core.c:926
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffff800010b2def0-ffff800010b2dfc0: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0941c)
Location: drivers/mmc/core/core.c:926
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
c0c0941c-c0c0950c: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c27330)
Location: drivers/mmc/core/core.c:926
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
c000000000c27330-c000000000c27478: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe0007078aa)
Location: drivers/mmc/core/core.c:926
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffe0007078aa-ffffffe000707958: mmc_set_clock (STB_GLOBAL)
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
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818781d0)
Location: drivers/mmc/core/core.c:926
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818781d0-ffffffff818782ae: mmc_set_clock (STB_GLOBAL)
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
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c9670)
Location: drivers/mmc/core/core.c:926
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818c9670-ffffffff818c974e: mmc_set_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmc_set_clock(struct mmc_host *host, unsigned int hz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e6190)
Location: drivers/mmc/core/core.c:926
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_hs400_to_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/mmc.c:mmc_set_bus_speed
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_sw_reset
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/debugfs.c:mmc_clock_opt_set
```
**Symbols:**

```
ffffffff818e6190-ffffffff818e626e: mmc_set_clock (STB_GLOBAL)
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
