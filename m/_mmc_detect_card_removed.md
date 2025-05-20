# Function: <code>_mmc_detect_card_removed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816c0da0)
Location: drivers/mmc/core/core.c:2497
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff816c0da0-ffffffff816c0e8e: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817204e0)
Location: drivers/mmc/core/core.c:2561
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff817204e0-ffffffff817205a3: _mmc_detect_card_removed.part.31 (STB_LOCAL)
ffffffff81723bb0-ffffffff81723bde: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81752d70)
Location: drivers/mmc/core/core.c:2659
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81752d70-ffffffff81752e33: _mmc_detect_card_removed.part.36 (STB_LOCAL)
ffffffff81756a70-ffffffff81756a9e: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81771406)
Location: drivers/mmc/core/core.c:2492
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
**Symbols:**

```
ffffffff817712e0-ffffffff817713a3: _mmc_detect_card_removed.part.34 (STB_LOCAL)
ffffffff817749c0-ffffffff817749ec: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e7316)
Location: drivers/mmc/core/core.c:2698
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
**Symbols:**

```
ffffffff817e71f0-ffffffff817e72bc: _mmc_detect_card_removed.part.36 (STB_LOCAL)
ffffffff817eac10-ffffffff817eac3c: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81830c8f)
Location: drivers/mmc/core/core.c:2533
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
**Symbols:**

```
ffffffff81830b20-ffffffff81830be6: _mmc_detect_card_removed.part.35 (STB_LOCAL)
ffffffff81833b70-ffffffff81833b9c: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185cf0f)
Location: drivers/mmc/core/core.c:2522
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
**Symbols:**

```
ffffffff8185cda0-ffffffff8185ce66: _mmc_detect_card_removed.part.37 (STB_LOCAL)
ffffffff8185fb00-ffffffff8185fb2c: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a0880)
Location: drivers/mmc/core/core.c:2210
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
**Symbols:**

```
ffffffff818a0730-ffffffff818a07f6: _mmc_detect_card_removed.part.0 (STB_LOCAL)
ffffffff818a3680-ffffffff818a36ac: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d5a5d)
Location: drivers/mmc/core/core.c:2212
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
**Symbols:**

```
ffffffff818d58e0-ffffffff818d59a6: _mmc_detect_card_removed.part.0 (STB_LOCAL)
ffffffff818d5bd0-ffffffff818d5bfc: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a83fe)
Location: drivers/mmc/core/core.c:2160
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff819a82c0-ffffffff819a8386: _mmc_detect_card_removed.part.0 (STB_LOCAL)
ffffffff819a8610-ffffffff819a863c: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a9e4e)
Location: drivers/mmc/core/core.c:2175
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff819a9ce0-ffffffff819a9ddc: _mmc_detect_card_removed.part.0 (STB_LOCAL)
ffffffff819ab6c0-ffffffff819ab6ec: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198fb70)
Location: drivers/mmc/core/core.c:2101
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff8198fb70-ffffffff8198fc8f: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a3b2e0)
Location: drivers/mmc/core/core.c:2086
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81a3b2e0-ffffffff81a3b3f9: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba8240)
Location: drivers/mmc/core/core.c:2088
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81ba8240-ffffffff81ba8359: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d4aa60)
Location: drivers/mmc/core/core.c:2100
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81d4aa60-ffffffff81d4ab8b: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db52c0)
Location: drivers/mmc/core/core.c:2100
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81db52c0-ffffffff81db53fc: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6d710)
Location: drivers/mmc/core/core.c:2105
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffff81e6d710-ffffffff81e6d84c: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2f568)
Location: drivers/mmc/core/core.c:2212
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
**Symbols:**

```
ffff800010b2f418-ffff800010b2f504: _mmc_detect_card_removed.part.0 (STB_LOCAL)
ffff800010b2f778-ffff800010b2f7c8: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (c0c0a754)
Location: drivers/mmc/core/core.c:2212
Inline: True
```
**Symbols:**

```
c0c0a754-c0c0a840: _mmc_detect_card_removed.part.0 (STB_LOCAL)
c0c0aa7c-c0c0aab8: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c29104)
Location: drivers/mmc/core/core.c:2212
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
c000000000c28ea0-c000000000c28ff8: _mmc_detect_card_removed.part.0 (STB_LOCAL)
c000000000c292e0-c000000000c29318: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000705f9c)
Location: drivers/mmc/core/core.c:2212
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
**Symbols:**

```
ffffffe000705e6c-ffffffe000705f40: _mmc_detect_card_removed.part.0 (STB_LOCAL)
ffffffe000708990-ffffffe0007089d6: _mmc_detect_card_removed (STB_GLOBAL)
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
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8187941d)
Location: drivers/mmc/core/core.c:2212
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
**Symbols:**

```
ffffffff818792a0-ffffffff81879366: _mmc_detect_card_removed.part.0 (STB_LOCAL)
ffffffff81879590-ffffffff818795bc: _mmc_detect_card_removed (STB_GLOBAL)
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
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818ca8bd)
Location: drivers/mmc/core/core.c:2212
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
**Symbols:**

```
ffffffff818ca740-ffffffff818ca806: _mmc_detect_card_removed.part.0 (STB_LOCAL)
ffffffff818caa30-ffffffff818caa5c: _mmc_detect_card_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_detect_card_removed(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e73dd)
Location: drivers/mmc/core/core.c:2212
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
Direct callers:
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
**Symbols:**

```
ffffffff818e7260-ffffffff818e7326: _mmc_detect_card_removed.part.0 (STB_LOCAL)
ffffffff818e7550-ffffffff818e757c: _mmc_detect_card_removed (STB_GLOBAL)
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
