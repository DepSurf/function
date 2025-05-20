# Function: <code>mmc_remove_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff816c1bb0)
Location: drivers/mmc/core/bus.c:367
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff816c1bb0-ffffffff816c1c3b: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81724840)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81724840-ffffffff817248cb: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff817577c0)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff817577c0-ffffffff8175784b: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81775650)
Location: drivers/mmc/core/bus.c:370
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff81775650-ffffffff817756cc: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff817eb930)
Location: drivers/mmc/core/bus.c:373
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff817eb930-ffffffff817eb9d7: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:371
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff81834b4b-ffffffff81834ba2: mmc_remove_card.cold.14 (STB_LOCAL)
ffffffff818348a0-ffffffff818348fd: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:371
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff81860b04-ffffffff81860b5b: mmc_remove_card.cold.14 (STB_LOCAL)
ffffffff81860830-ffffffff8186088d: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818a4847-ffffffff818a48a3: mmc_remove_card.cold (STB_LOCAL)
ffffffff818a4540-ffffffff818a45a2: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818d6cd2-ffffffff818d6d2e: mmc_remove_card.cold (STB_LOCAL)
ffffffff818d69c0-ffffffff818d6a22: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:382
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819a9632-ffffffff819a968e: mmc_remove_card.cold (STB_LOCAL)
ffffffff819a9320-ffffffff819a9382: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:394
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81c2a547-ffffffff81c2a5a1: mmc_remove_card.cold (STB_LOCAL)
ffffffff819ac210-ffffffff819ac26e: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:394
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81c1c905-ffffffff81c1c95f: mmc_remove_card.cold (STB_LOCAL)
ffffffff81990650-ffffffff819906ae: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:392
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d2d4f6-ffffffff81d2d564: mmc_remove_card.cold (STB_LOCAL)
ffffffff81a3bf00-ffffffff81a3bf6c: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:382
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81ef98fe-ffffffff81ef996a: mmc_remove_card.cold (STB_LOCAL)
ffffffff81ba8ee0-ffffffff81ba8f5b: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:380
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff820a97aa-ffffffff820a97be: mmc_remove_card.cold (STB_LOCAL)
ffffffff81d4bae0-ffffffff81d4bbb5: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:380
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8212aba3-ffffffff8212abb7: mmc_remove_card.cold (STB_LOCAL)
ffffffff81db6380-ffffffff81db645d: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:383
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_pre_suspend
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8220c94b-ffffffff8220c95f: mmc_remove_card.cold (STB_LOCAL)
ffffffff81e6e820-ffffffff81e6e8fd: mmc_remove_card (STB_GLOBAL)
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
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffff800010b30cd8)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffff800010b30cd8-ffff800010b30d98: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (c0c0ba48)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
c0c0ba48-c0c0bb04: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (c000000000c2a7e0)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
c000000000c2a7e0-c000000000c2a8f4: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffe00070978e)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffe00070978e-ffffffe000709844: mmc_remove_card (STB_GLOBAL)
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
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff8187a692-ffffffff8187a6ee: mmc_remove_card.cold (STB_LOCAL)
ffffffff8187a380-ffffffff8187a3e2: mmc_remove_card (STB_GLOBAL)
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
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818cbb32-ffffffff818cbb8e: mmc_remove_card.cold (STB_LOCAL)
ffffffff818cb820-ffffffff818cb882: mmc_remove_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mmc_remove_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:368
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_remove
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_resend_if_cond
```
**Symbols:**

```
ffffffff818e8652-ffffffff818e86ae: mmc_remove_card.cold (STB_LOCAL)
ffffffff818e8340-ffffffff818e83a2: mmc_remove_card (STB_GLOBAL)
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
