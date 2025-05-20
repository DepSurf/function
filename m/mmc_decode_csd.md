# Function: <code>mmc_decode_csd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff816c3d6a)
Location: drivers/mmc/core/mmc.c:130
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff816c6ef3)
Location: drivers/mmc/core/sd.c:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81727136)
Location: drivers/mmc/core/mmc.c:141
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff81729ec7)
Location: drivers/mmc/core/sd.c:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81759ebc)
Location: drivers/mmc/core/mmc.c:143
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff8175cfc7)
Location: drivers/mmc/core/sd.c:100
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff8177833b)
Location: drivers/mmc/core/mmc.c:135
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff8177b777)
Location: drivers/mmc/core/sd.c:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff817ee738)
Location: drivers/mmc/core/mmc.c:135
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff817f21b7)
Location: drivers/mmc/core/sd.c:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff8183796f)
Location: drivers/mmc/core/mmc.c:135
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff8183b407)
Location: drivers/mmc/core/sd.c:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81863943)
Location: drivers/mmc/core/mmc.c:136
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff81867397)
Location: drivers/mmc/core/sd.c:102
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818a7906)
Location: drivers/mmc/core/mmc.c:133
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff818ab1f3)
Location: drivers/mmc/core/sd.c:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818d9d6d)
Location: drivers/mmc/core/mmc.c:133
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff818dd643)
Location: drivers/mmc/core/sd.c:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_decode_csd(struct mmc_card *card);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:133
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:99
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff819aa2e0-ffffffff819aa46a: mmc_decode_csd (STB_LOCAL)
ffffffff819ad47f-ffffffff819ad4ae: mmc_decode_csd.cold (STB_LOCAL)
ffffffff819af530-ffffffff819af7a7: mmc_decode_csd (STB_LOCAL)
ffffffff819b0fc5-ffffffff819b0fed: mmc_decode_csd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_decode_csd(struct mmc_card *card);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:133
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:99
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff819ace80-ffffffff819ad00a: mmc_decode_csd (STB_LOCAL)
ffffffff81c2a614-ffffffff81c2a643: mmc_decode_csd.cold (STB_LOCAL)
ffffffff819b1930-ffffffff819b1ba7: mmc_decode_csd (STB_LOCAL)
ffffffff81c2ae15-ffffffff81c2ae3d: mmc_decode_csd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_decode_csd(struct mmc_card *card);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:133
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:99
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81991700-ffffffff8199188e: mmc_decode_csd (STB_LOCAL)
ffffffff81c1ca1c-ffffffff81c1ca47: mmc_decode_csd.cold (STB_LOCAL)
ffffffff81996140-ffffffff819963de: mmc_decode_csd (STB_LOCAL)
ffffffff81c1d18e-ffffffff81c1d1b6: mmc_decode_csd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_decode_csd(struct mmc_card *card);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:134
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:107
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81a3cee0-ffffffff81a3d074: mmc_decode_csd (STB_LOCAL)
ffffffff81d2d621-ffffffff81d2d64c: mmc_decode_csd.cold (STB_LOCAL)
ffffffff81a42000-ffffffff81a422aa: mmc_decode_csd (STB_LOCAL)
ffffffff81d2e040-ffffffff81d2e068: mmc_decode_csd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int mmc_decode_csd(struct mmc_card *card);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:142
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:116
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81ba9fe0-ffffffff81baa182: mmc_decode_csd (STB_LOCAL)
ffffffff81ef9a52-ffffffff81ef9a8f: mmc_decode_csd.cold (STB_LOCAL)
ffffffff81baf790-ffffffff81bafa39: mmc_decode_csd (STB_LOCAL)
ffffffff81efa464-ffffffff81efa4a0: mmc_decode_csd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int mmc_decode_csd(struct mmc_card *card);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81d4cee0)
Location: drivers/mmc/core/mmc.c:142
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff81d532b0)
Location: drivers/mmc/core/sd.c:116
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81d4cee0-ffffffff81d4d0bd: mmc_decode_csd (STB_LOCAL)
ffffffff81d532b0-ffffffff81d53591: mmc_decode_csd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int mmc_decode_csd(struct mmc_card *card);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81db7840)
Location: drivers/mmc/core/mmc.c:142
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff81dbdc80)
Location: drivers/mmc/core/sd.c:116
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81db7840-ffffffff81db7a15: mmc_decode_csd (STB_LOCAL)
ffffffff81dbdc80-ffffffff81dbdf56: mmc_decode_csd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int mmc_decode_csd(struct mmc_card *card);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81e6fd10)
Location: drivers/mmc/core/mmc.c:153
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff81e762b0)
Location: drivers/mmc/core/sd.c:116
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
```
**Symbols:**

```
ffffffff81e6fd10-ffffffff81e6fef0: mmc_decode_csd (STB_LOCAL)
ffffffff81e762b0-ffffffff81e76586: mmc_decode_csd (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffff800010b341a8)
Location: drivers/mmc/core/mmc.c:133
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffff800010b3796c)
Location: drivers/mmc/core/sd.c:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c0c0ecdc)
Location: drivers/mmc/core/mmc.c:133
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (c0c122b8)
Location: drivers/mmc/core/sd.c:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c000000000c2ea08)
Location: drivers/mmc/core/mmc.c:133
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (c000000000c332c0)
Location: drivers/mmc/core/sd.c:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffe00070c7a8)
Location: drivers/mmc/core/mmc.c:133
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffe00070f8de)
Location: drivers/mmc/core/sd.c:99
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff8187d72d)
Location: drivers/mmc/core/mmc.c:133
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff81881003)
Location: drivers/mmc/core/sd.c:99
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818cebcd)
Location: drivers/mmc/core/mmc.c:133
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff818d24a3)
Location: drivers/mmc/core/sd.c:99
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818eb6ed)
Location: drivers/mmc/core/mmc.c:133
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
```
In drivers/mmc/core/sd.c (ffffffff818eefc3)
Location: drivers/mmc/core/sd.c:99
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
