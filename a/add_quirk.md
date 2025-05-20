# Function: <code>add_quirk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/quirks.c (ffffffff816ccb50)
Location: include/linux/mmc/card.h:413
Inline: False
```
**Symbols:**

```
ffffffff816ccb50-ffffffff816ccb5c: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81725030)
Location: include/linux/mmc/card.h:434
Inline: False
```
```
In drivers/mmc/core/quirks.c (ffffffff8172fa70)
Location: include/linux/mmc/card.h:434
Inline: False
```
**Symbols:**

```
ffffffff81725030-ffffffff8172503c: add_quirk (STB_LOCAL)
ffffffff8172fa70-ffffffff8172fa7c: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81757fb0)
Location: include/linux/mmc/card.h:425
Inline: False
```
```
In drivers/mmc/core/quirks.c (ffffffff81762a50)
Location: include/linux/mmc/card.h:425
Inline: False
```
**Symbols:**

```
ffffffff81757fb0-ffffffff81757fbc: add_quirk (STB_LOCAL)
ffffffff81762a50-ffffffff81762a5c: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81776270)
Location: drivers/mmc/core/card.h:139
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff8177d040)
Location: drivers/mmc/core/card.h:139
Inline: False
```
**Symbols:**

```
ffffffff81776270-ffffffff8177627c: add_quirk (STB_LOCAL)
ffffffff8177d040-ffffffff8177d04c: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff817ec5b0)
Location: drivers/mmc/core/card.h:142
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff817f35c0)
Location: drivers/mmc/core/card.h:142
Inline: False
```
**Symbols:**

```
ffffffff817ec5b0-ffffffff817ec5bc: add_quirk (STB_LOCAL)
ffffffff817f35c0-ffffffff817f35cc: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818357a0)
Location: drivers/mmc/core/card.h:142
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff8183ca10)
Location: drivers/mmc/core/card.h:142
Inline: False
```
**Symbols:**

```
ffffffff818357a0-ffffffff818357a7: add_quirk (STB_LOCAL)
ffffffff8183ca10-ffffffff8183ca17: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81861750)
Location: drivers/mmc/core/card.h:138
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff818689a0)
Location: drivers/mmc/core/card.h:138
Inline: False
```
**Symbols:**

```
ffffffff81861750-ffffffff81861757: add_quirk (STB_LOCAL)
ffffffff818689a0-ffffffff818689a7: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818a5530)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff818ac8d0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffffffff818a5530-ffffffff818a5537: add_quirk (STB_LOCAL)
ffffffff818ac8d0-ffffffff818ac8d7: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818d7970)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff818ded00)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffffffff818d7970-ffffffff818d7977: add_quirk (STB_LOCAL)
ffffffff818ded00-ffffffff818ded07: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff819aa2d0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff819b1b10)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffffffff819aa2d0-ffffffff819aa2d7: add_quirk (STB_LOCAL)
ffffffff819b1b10-ffffffff819b1b17: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff819ace70)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff819b3ee0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffffffff819ace70-ffffffff819ace77: add_quirk (STB_LOCAL)
ffffffff819b3ee0-ffffffff819b3ee7: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff819916c0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff819986c0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffffffff819916c0-ffffffff819916c7: add_quirk (STB_LOCAL)
ffffffff819986c0-ffffffff819986c7: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81a3ce70)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff81a44dd0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffffffff81a3ce70-ffffffff81a3ce77: add_quirk (STB_LOCAL)
ffffffff81a44dd0-ffffffff81a44dd7: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81ba9f50)
Location: drivers/mmc/core/card.h:155
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb29e0)
Location: drivers/mmc/core/card.h:155
Inline: False
```
**Symbols:**

```
ffffffff81ba9f50-ffffffff81ba9f5f: add_quirk (STB_LOCAL)
ffffffff81bb29e0-ffffffff81bb29ef: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81d4ce20)
Location: drivers/mmc/core/card.h:156
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff81d56d20)
Location: drivers/mmc/core/card.h:156
Inline: False
```
**Symbols:**

```
ffffffff81d4ce20-ffffffff81d4ce2f: add_quirk (STB_LOCAL)
ffffffff81d56d20-ffffffff81d56d2f: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81db7780)
Location: drivers/mmc/core/card.h:167
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc16a0)
Location: drivers/mmc/core/card.h:167
Inline: False
```
**Symbols:**

```
ffffffff81db7780-ffffffff81db778f: add_quirk (STB_LOCAL)
ffffffff81dc16a0-ffffffff81dc16af: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81e6fc50)
Location: drivers/mmc/core/card.h:167
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff81e79f60)
Location: drivers/mmc/core/card.h:167
Inline: False
```
**Symbols:**

```
ffffffff81e6fc50-ffffffff81e6fc5f: add_quirk (STB_LOCAL)
ffffffff81e79f60-ffffffff81e79f6f: add_quirk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffff800010b31c90)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffff800010b38e78)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/block.c (ffff800010b3ec28)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffff800010b31c90-ffff800010b31ca0: add_quirk (STB_LOCAL)
ffff800010b38e78-ffff800010b38e88: add_quirk (STB_LOCAL)
ffff800010b3ec28-ffff800010b3ec38: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c0c0c8f0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (c0c137bc)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/block.c (c0c19030)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
c0c0c8f0-c0c0c90c: add_quirk (STB_LOCAL)
c0c137bc-c0c137d8: add_quirk (STB_LOCAL)
c0c19030-c0c1904c: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c000000000c2bbe0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (c000000000c34ea0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
c000000000c2bbe0-c000000000c2bbf0: add_quirk (STB_LOCAL)
c000000000c34ea0-c000000000c34eb0: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffe00070a682)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffe000710ba4)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/block.c (ffffffe000715a06)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffffffe000715a06-ffffffe000715a1c: add_quirk (STB_LOCAL)
ffffffe00070a682-ffffffe00070a698: add_quirk (STB_LOCAL)
ffffffe000710ba4-ffffffe000710bba: add_quirk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff8187b330)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff818826c0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffffffff8187b330-ffffffff8187b337: add_quirk (STB_LOCAL)
ffffffff818826c0-ffffffff818826c7: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818cc7d0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff818d3b60)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffffffff818cc7d0-ffffffff818cc7d7: add_quirk (STB_LOCAL)
ffffffff818d3b60-ffffffff818d3b67: add_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate ⚠️</summary>

```c
void add_quirk(struct mmc_card *card, int data);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818e92f0)
Location: drivers/mmc/core/card.h:137
Inline: False
```
```
In drivers/mmc/core/sdio.c (ffffffff818f0680)
Location: drivers/mmc/core/card.h:137
Inline: False
```
**Symbols:**

```
ffffffff818e92f0-ffffffff818e92f7: add_quirk (STB_LOCAL)
ffffffff818f0680-ffffffff818f0687: add_quirk (STB_LOCAL)
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
