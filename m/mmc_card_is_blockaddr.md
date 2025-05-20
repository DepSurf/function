# Function: <code>mmc_card_is_blockaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817707a0)
Location: drivers/mmc/core/core.c:2377
Inline: False
```
**Symbols:**

```
ffffffff817707a0-ffffffff817707be: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e6170)
Location: drivers/mmc/core/core.c:2584
Inline: False
```
**Symbols:**

```
ffffffff817e6170-ffffffff817e618e: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8182f530)
Location: drivers/mmc/core/core.c:2395
Inline: False
```
**Symbols:**

```
ffffffff8182f530-ffffffff8182f54e: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185b7a0)
Location: drivers/mmc/core/core.c:2398
Inline: False
```
**Symbols:**

```
ffffffff8185b7a0-ffffffff8185b7be: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8189f620)
Location: drivers/mmc/core/core.c:2086
Inline: False
```
**Symbols:**

```
ffffffff8189f620-ffffffff8189f63e: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d1bc0)
Location: drivers/mmc/core/core.c:2088
Inline: False
```
**Symbols:**

```
ffffffff818d1bc0-ffffffff818d1bde: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a4320)
Location: drivers/mmc/core/core.c:2036
Inline: False
```
**Symbols:**

```
ffffffff819a4320-ffffffff819a433e: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a73a0)
Location: drivers/mmc/core/core.c:2036
Inline: False
```
**Symbols:**

```
ffffffff819a73a0-ffffffff819a73be: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198c030)
Location: drivers/mmc/core/core.c:1981
Inline: False
```
**Symbols:**

```
ffffffff8198c030-ffffffff8198c04e: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a373c4)
Location: drivers/mmc/core/core.c:1966
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_card_alternative_gpt_sector
```
**Symbols:**

```
ffffffff81a37380-ffffffff81a3739e: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba3f03)
Location: drivers/mmc/core/core.c:1966
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_card_alternative_gpt_sector
```
**Symbols:**

```
ffffffff81ba3eb0-ffffffff81ba3ed4: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d46013)
Location: drivers/mmc/core/core.c:1978
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_card_alternative_gpt_sector
```
**Symbols:**

```
ffffffff81d45fb0-ffffffff81d45fd4: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db07c3)
Location: drivers/mmc/core/core.c:1978
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_card_alternative_gpt_sector
```
**Symbols:**

```
ffffffff81db0760-ffffffff81db0784: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e68b53)
Location: drivers/mmc/core/core.c:1983
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_card_alternative_gpt_sector
```
**Symbols:**

```
ffffffff81e68af0-ffffffff81e68b14: mmc_card_is_blockaddr (STB_GLOBAL)
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
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2ab68)
Location: drivers/mmc/core/core.c:2088
Inline: False
```
**Symbols:**

```
ffff800010b2ab68-ffff800010b2ab9c: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c06390)
Location: drivers/mmc/core/core.c:2088
Inline: False
```
**Symbols:**

```
c0c06390-c0c063b4: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c232d0)
Location: drivers/mmc/core/core.c:2088
Inline: False
```
**Symbols:**

```
c000000000c232d0-c000000000c232f8: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000704fcc)
Location: drivers/mmc/core/core.c:2088
Inline: False
```
**Symbols:**

```
ffffffe000704fcc-ffffffe000704ffa: mmc_card_is_blockaddr (STB_GLOBAL)
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
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81875580)
Location: drivers/mmc/core/core.c:2088
Inline: False
```
**Symbols:**

```
ffffffff81875580-ffffffff8187559e: mmc_card_is_blockaddr (STB_GLOBAL)
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
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c6a20)
Location: drivers/mmc/core/core.c:2088
Inline: False
```
**Symbols:**

```
ffffffff818c6a20-ffffffff818c6a3e: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool mmc_card_is_blockaddr(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e34d0)
Location: drivers/mmc/core/core.c:2088
Inline: False
```
**Symbols:**

```
ffffffff818e34d0-ffffffff818e34ee: mmc_card_is_blockaddr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
