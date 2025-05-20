# Function: <code>mmc_sdio_init_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard, int powered_resume);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff816c8d10)
Location: drivers/mmc/core/sdio.c:551
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff816c8d10-ffffffff816c981b: mmc_sdio_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard, int powered_resume);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8172bcd0)
Location: drivers/mmc/core/sdio.c:549
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8172bcd0-ffffffff8172c7d8: mmc_sdio_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard, int powered_resume);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8175ee90)
Location: drivers/mmc/core/sdio.c:550
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8175ee90-ffffffff8175f98d: mmc_sdio_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard, int powered_resume);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8177d540)
Location: drivers/mmc/core/sdio.c:562
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8177d540-ffffffff8177e19b: mmc_sdio_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard, int powered_resume);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff817f3ac0)
Location: drivers/mmc/core/sdio.c:562
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_power_restore
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff817f3ac0-ffffffff817f4723: mmc_sdio_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard, int powered_resume);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:565
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff8183cfe0-ffffffff8183dc19: mmc_sdio_init_card (STB_LOCAL)
ffffffff8183e2e9-ffffffff8183e368: mmc_sdio_init_card.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard, int powered_resume);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:565
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81868f70-ffffffff81869bcd: mmc_sdio_init_card (STB_LOCAL)
ffffffff8186a299-ffffffff8186a318: mmc_sdio_init_card.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:561
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818acde0-ffffffff818ada97: mmc_sdio_init_card (STB_LOCAL)
ffffffff818ae15f-ffffffff818ae1f2: mmc_sdio_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:561
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818df230-ffffffff818dfefa: mmc_sdio_init_card (STB_LOCAL)
ffffffff818e0616-ffffffff818e0696: mmc_sdio_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:599
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff819b28e0-ffffffff819b2f5a: mmc_sdio_init_card (STB_LOCAL)
ffffffff819b3664-ffffffff819b36b8: mmc_sdio_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:643
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff819b4e30-ffffffff819b54aa: mmc_sdio_init_card (STB_LOCAL)
ffffffff81c2b199-ffffffff81c2b1ed: mmc_sdio_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:643
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81999310-ffffffff81999a38: mmc_sdio_init_card (STB_LOCAL)
ffffffff81c1d513-ffffffff81c1d567: mmc_sdio_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:643
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81a45a80-ffffffff81a461d9: mmc_sdio_init_card (STB_LOCAL)
ffffffff81d2e5f8-ffffffff81d2e676: mmc_sdio_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:644
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81bb37f0-ffffffff81bb3f0a: mmc_sdio_init_card (STB_LOCAL)
ffffffff81efaa6a-ffffffff81efaaec: mmc_sdio_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:658
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81d57da0-ffffffff81d58511: mmc_sdio_init_card (STB_LOCAL)
ffffffff820a9aea-ffffffff820a9b1a: mmc_sdio_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:658
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81dc2740-ffffffff81dc2eaa: mmc_sdio_init_card (STB_LOCAL)
ffffffff8212aecc-ffffffff8212aefc: mmc_sdio_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:658
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81e7b000-ffffffff81e7b76a: mmc_sdio_init_card (STB_LOCAL)
ffffffff8220cc89-ffffffff8220ccb9: mmc_sdio_init_card.cold (STB_LOCAL)
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
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffff800010b39478)
Location: drivers/mmc/core/sdio.c:561
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffff800010b39478-ffff800010b3a054: mmc_sdio_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (c0c13dac)
Location: drivers/mmc/core/sdio.c:561
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
c0c13dac-c0c14a98: mmc_sdio_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (c000000000c35870)
Location: drivers/mmc/core/sdio.c:561
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
c000000000c35870-c000000000c36800: mmc_sdio_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffe000711156)
Location: drivers/mmc/core/sdio.c:561
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffe000711156-ffffffe000711c10: mmc_sdio_init_card (STB_LOCAL)
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
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:561
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81882bf0-ffffffff818838ba: mmc_sdio_init_card (STB_LOCAL)
ffffffff81883fd6-ffffffff81884056: mmc_sdio_init_card.cold (STB_LOCAL)
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
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:561
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818d4090-ffffffff818d4d5a: mmc_sdio_init_card (STB_LOCAL)
ffffffff818d5476-ffffffff818d54f6: mmc_sdio_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_sdio_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:561
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818f0bb0-ffffffff818f187a: mmc_sdio_init_card (STB_LOCAL)
ffffffff818f1f96-ffffffff818f2016: mmc_sdio_init_card.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int powered_resume</code>
</li>
</ul>
</details>
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
