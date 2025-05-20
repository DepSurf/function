# Function: <code>_mmc_select_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff816c56e0)
Location: drivers/mmc/core/mmc_ops.c:91
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
```
**Symbols:**

```
ffffffff816c56e0-ffffffff816c56eb: _mmc_select_card.part.3 (STB_LOCAL)
ffffffff816c56f0-ffffffff816c576d: _mmc_select_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81728560)
Location: drivers/mmc/core/mmc_ops.c:91
Inline: True
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
**Symbols:**

```
ffffffff81728560-ffffffff8172856b: _mmc_select_card.part.3 (STB_LOCAL)
ffffffff81728570-ffffffff817285ed: _mmc_select_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8175ba19)
Location: drivers/mmc/core/mmc_ops.c:80
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81779e89)
Location: drivers/mmc/core/mmc_ops.c:87
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f02d9)
Location: drivers/mmc/core/mmc_ops.c:88
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81839619)
Location: drivers/mmc/core/mmc_ops.c:88
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81865649)
Location: drivers/mmc/core/mmc_ops.c:88
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818a8bf0)
Location: drivers/mmc/core/mmc_ops.c:84
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
**Symbols:**

```
ffffffff818a8bf0-ffffffff818a8c73: _mmc_select_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818db030)
Location: drivers/mmc/core/mmc_ops.c:84
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
**Symbols:**

```
ffffffff818db030-ffffffff818db0b3: _mmc_select_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819ae6b9)
Location: drivers/mmc/core/mmc_ops.c:86
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819b0d19)
Location: drivers/mmc/core/mmc_ops.c:86
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819955f9)
Location: drivers/mmc/core/mmc_ops.c:86
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a411d9)
Location: drivers/mmc/core/mmc_ops.c:91
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81bae769)
Location: drivers/mmc/core/mmc_ops.c:99
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d52039)
Location: drivers/mmc/core/mmc_ops.c:99
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbca49)
Location: drivers/mmc/core/mmc_ops.c:99
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e75019)
Location: drivers/mmc/core/mmc_ops.c:99
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
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
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b35050)
Location: drivers/mmc/core/mmc_ops.c:84
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
**Symbols:**

```
ffff800010b35050-ffff800010b350f4: _mmc_select_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c0fb3c)
Location: drivers/mmc/core/mmc_ops.c:84
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
**Symbols:**

```
c0c0fb3c-c0c0fbdc: _mmc_select_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c2fcb0)
Location: drivers/mmc/core/mmc_ops.c:84
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
**Symbols:**

```
c000000000c2fcb0-c000000000c2fd64: _mmc_select_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070d4ea)
Location: drivers/mmc/core/mmc_ops.c:84
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
**Symbols:**

```
ffffffe00070d4ea-ffffffe00070d560: _mmc_select_card (STB_LOCAL)
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
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8187e9f0)
Location: drivers/mmc/core/mmc_ops.c:84
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
**Symbols:**

```
ffffffff8187e9f0-ffffffff8187ea73: _mmc_select_card (STB_LOCAL)
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
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818cfe90)
Location: drivers/mmc/core/mmc_ops.c:84
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
**Symbols:**

```
ffffffff818cfe90-ffffffff818cff13: _mmc_select_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _mmc_select_card(struct mmc_host *host, struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818ec9b0)
Location: drivers/mmc/core/mmc_ops.c:84
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_deselect_cards
  - drivers/mmc/core/mmc_ops.c:mmc_select_card
```
**Symbols:**

```
ffffffff818ec9b0-ffffffff818eca33: _mmc_select_card (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
