# Function: <code>sdio_read_cis</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff816caf50)
Location: drivers/mmc/core/sdio_cis.c:228
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
```
**Symbols:**

```
ffffffff816caf50-ffffffff816cb20d: sdio_read_cis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff8172df10)
Location: drivers/mmc/core/sdio_cis.c:234
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff8172df10-ffffffff8172e1c7: sdio_read_cis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff81760ed0)
Location: drivers/mmc/core/sdio_cis.c:234
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff81760ed0-ffffffff8176118b: sdio_read_cis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff8177f700)
Location: drivers/mmc/core/sdio_cis.c:234
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff8177f700-ffffffff8177f9ca: sdio_read_cis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff817f5cb0)
Location: drivers/mmc/core/sdio_cis.c:234
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff817f5cb0-ffffffff817f5f7a: sdio_read_cis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:234
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff8183f180-ffffffff8183f427: sdio_read_cis (STB_LOCAL)
ffffffff8183f770-ffffffff8183f7a2: sdio_read_cis.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:234
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff8186b130-ffffffff8186b3d7: sdio_read_cis (STB_LOCAL)
ffffffff8186b720-ffffffff8186b752: sdio_read_cis.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:230
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff818af020-ffffffff818af2c7: sdio_read_cis (STB_LOCAL)
ffffffff818af5e7-ffffffff818af619: sdio_read_cis.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:230
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff818e14d0-ffffffff818e1777: sdio_read_cis (STB_LOCAL)
ffffffff818e1a93-ffffffff818e1ac5: sdio_read_cis.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:230
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff819b4670-ffffffff819b4917: sdio_read_cis (STB_LOCAL)
ffffffff819b4bc8-ffffffff819b4bfa: sdio_read_cis.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:243
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff819b6c70-ffffffff819b6f15: sdio_read_cis (STB_LOCAL)
ffffffff81c2b284-ffffffff81c2b2b6: sdio_read_cis.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:243
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff8199b420-ffffffff8199b6c5: sdio_read_cis (STB_LOCAL)
ffffffff81c1d613-ffffffff81c1d645: sdio_read_cis.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:243
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff81a47d60-ffffffff81a48078: sdio_read_cis (STB_LOCAL)
ffffffff81d2e71d-ffffffff81d2e755: sdio_read_cis.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:243
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff81bb5d70-ffffffff81bb60cf: sdio_read_cis (STB_LOCAL)
ffffffff81efab96-ffffffff81efabcf: sdio_read_cis.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff81d5a6f0)
Location: drivers/mmc/core/sdio_cis.c:243
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff81d5a6f0-ffffffff81d5aa77: sdio_read_cis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff81dc50a0)
Location: drivers/mmc/core/sdio_cis.c:243
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff81dc50a0-ffffffff81dc5427: sdio_read_cis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffff81e7d9e0)
Location: drivers/mmc/core/sdio_cis.c:243
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff81e7d9e0-ffffffff81e7dd67: sdio_read_cis (STB_LOCAL)
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
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffff800010b3b9c0)
Location: drivers/mmc/core/sdio_cis.c:230
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffff800010b3b9c0-ffff800010b3bc90: sdio_read_cis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (c0c16158)
Location: drivers/mmc/core/sdio_cis.c:230
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
c0c16158-c0c16458: sdio_read_cis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (c000000000c38620)
Location: drivers/mmc/core/sdio_cis.c:230
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
c000000000c38620-c000000000c38a5c: sdio_read_cis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (ffffffe000713070)
Location: drivers/mmc/core/sdio_cis.c:230
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffe000713070-ffffffe0007132bc: sdio_read_cis (STB_LOCAL)
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
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:230
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff81884e90-ffffffff81885137: sdio_read_cis (STB_LOCAL)
ffffffff81885453-ffffffff81885485: sdio_read_cis.cold (STB_LOCAL)
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
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:230
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff818d6330-ffffffff818d65d7: sdio_read_cis (STB_LOCAL)
ffffffff818d68f3-ffffffff818d6925: sdio_read_cis.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sdio_read_cis(struct mmc_card *card, struct sdio_func *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_cis.c (0)
Location: drivers/mmc/core/sdio_cis.c:230
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_cis.c:sdio_read_func_cis
  - drivers/mmc/core/sdio_cis.c:sdio_read_common_cis
```
**Symbols:**

```
ffffffff818f2e50-ffffffff818f30f7: sdio_read_cis (STB_LOCAL)
ffffffff818f3413-ffffffff818f3445: sdio_read_cis.cold (STB_LOCAL)
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
