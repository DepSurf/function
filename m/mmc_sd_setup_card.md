# Function: <code>mmc_sd_setup_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff816c7170)
Location: drivers/mmc/core/sd.c:808
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff816c7170-ffffffff816c754f: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8172a160)
Location: drivers/mmc/core/sd.c:837
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8172a160-ffffffff8172a57c: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8175d260)
Location: drivers/mmc/core/sd.c:846
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8175d260-ffffffff8175d68a: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8177ba00)
Location: drivers/mmc/core/sd.c:833
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8177ba00-ffffffff8177bdea: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff817f2440)
Location: drivers/mmc/core/sd.c:833
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff817f2440-ffffffff817f271f: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:827
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8183c07c-ffffffff8183c138: mmc_sd_setup_card.cold.19 (STB_LOCAL)
ffffffff8183b670-ffffffff8183b8a4: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81867615)
Location: drivers/mmc/core/sd.c:827
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8186800c-ffffffff818680c8: mmc_sd_setup_card.cold.19 (STB_LOCAL)
ffffffff81867600-ffffffff81867834: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff818ab467)
Location: drivers/mmc/core/sd.c:847
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818abf04-ffffffff818abff5: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff818ab450-ffffffff818ab6e1: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff818dd8b7)
Location: drivers/mmc/core/sd.c:847
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818de36b-ffffffff818de45c: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff818dd8a0-ffffffff818ddb31: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:871
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b11d2-ffffffff819b1244: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff819b0740-ffffffff819b08de: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:901
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81c2b022-ffffffff81c2b094: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff819b2cb0-ffffffff819b2e4e: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:909
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81c1d39c-ffffffff81c1d40e: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff81997490-ffffffff8199762e: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:919
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d2e3e7-ffffffff81d2e46e: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff81a43b30-ffffffff81a43cd4: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:926
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81efa80e-ffffffff81efa88b: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff81bb15f0-ffffffff81bb1799: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:927
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff820a9a7d-ffffffff820a9a92: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff81d55600-ffffffff81d5595a: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:927
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8212ae65-ffffffff8212ae7a: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff81dbff40-ffffffff81dc02c4: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:927
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8220cc22-ffffffff8220cc37: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff81e78700-ffffffff81e78ab3: mmc_sd_setup_card (STB_GLOBAL)
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
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffff800010b37b90)
Location: drivers/mmc/core/sd.c:847
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffff800010b37b90-ffff800010b37ed0: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (c0c124cc)
Location: drivers/mmc/core/sd.c:847
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
c0c124cc-c0c1280c: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (c000000000c33520)
Location: drivers/mmc/core/sd.c:847
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
c000000000c33520-c000000000c339e4: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffe00070faf2)
Location: drivers/mmc/core/sd.c:847
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffe00070faf2-ffffffe00070fe00: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81881277)
Location: drivers/mmc/core/sd.c:847
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81881d2b-ffffffff81881e1c: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff81881260-ffffffff818814f1: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff818d2717)
Location: drivers/mmc/core/sd.c:847
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818d31cb-ffffffff818d32bc: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff818d2700-ffffffff818d2991: mmc_sd_setup_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_sd_setup_card(struct mmc_host *host, struct mmc_card *card, bool reinit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff818ef237)
Location: drivers/mmc/core/sd.c:847
Inline: True
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818efceb-ffffffff818efddc: mmc_sd_setup_card.cold (STB_LOCAL)
ffffffff818ef220-ffffffff818ef4b1: mmc_sd_setup_card (STB_GLOBAL)
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
